#  https://www.google.com/ 을 접속할 때 일어나는 일

특정 url을 호출하면 굉장히 많은 일이 일어나지만 크게 보면 아래와 같은 흐름으로 연결이 됩니다.

url을 웹 브라우저에서 호출을 하면 일단은 해당 url이 어디 주소(ip)를 가리키는지 알아내기 위해서 DNS 서버에 이름을 검색을 합니다.

해당 IP를 찾으면 앞에 https:// 에 나와있듯이 https 프로토콜을 사용하여 메세지를 생성하고 https 는 443 포트를 사용하는것을 약속을 하고 있음으로 xxx.xxx.xxx.xxx:443 포트로 TCP 연결을 하여 데이터를 요청을 하게 되고 요청을 받은 서버는 리턴값을 되돌려 주어서 해당 데이터를 웹브라우저가 랜더링을 해주어 우리가 흔히 보는 https://www.google.com/ 에 접속이 가능하게 해줍니다.

# DNS server 란
특정 도메인 주소와 연결된 IP를 알려주는 Server 입니다.
예를 들어 naver.com 은 naver.com 으로 바로 연결이 되는게 아니라 naver.com 을 도메인으로 쓰는 특정 IP가 있는데 해당 아이피를 이어 주는 역할을 합니다.

![dns.png](../img/dns.png)

# TCP 연결이란
통신의 종류는 크게 TCP/ UDP 방식이 존재하고 있는데 둘의 차이점은 데이터의 손실에 있습니다 TCP 는 3way-handshake 방식으로 통신할 서버와 연결을 하여 속도는 상대적으로 UDP 에 비해 느려도데이터의 손실 없이 데이터를 전송을 받습니다.
![hand.png](../img/hand.png)


TCP는 애플리케이션, 전송, 인터넷, 네트워크 액세스의 네 가지 계층으로 구성이 되는데 흔히 보는 OSI 7 Layer 와 비슷해 보이지만 관련은 없다고 합니다.

**참고 사항**
- 4계층

    어플리케이션 계층

    HTTP(Hyper Text Trasfer Protocol)

    FRP(File Transfer Protocol)

    SMTP(Simple Mail Trasfer Protocol)

    OSI 7계층으로 생각하면, 7계층(응용계층), 6계층(표현계층), 5계층(세션계층)

- 3계층

    트랜스포트 계층

    TCP(Transmisson Control Protocol)

    UDP (User Datagram Protocol)

    OSI 7계층으로 생각하면, 4계층(전송계층)


- 2계층

    인터넷 계층

    IP(Internet Protocol)

    ARP(Address Resolution Protocol)

    OSI 7계층으로 생각하면, 3계층(네트워크계층)

- 1계층

    인터페이스 계층

    이더넷

    프레임 릴레이

    PPP(Point-to Point Protocol)

    OSI 7계층으로 생각하면, 2계층(데이터링크계층), 1계층(물리계층)
![3way.png](../img/3way.png)

**질문사항**
- Q1. TCP 전송은 데이터를 한번에 전송하기도 하지 않나요? 꼭 나눠서 패킷별로 전송하고 있나요?
- A1. 한번에 여러개를 전송을 하기도 합니다. 송신자와 수신자는 서로 성능이나 사양이 다를 수 있어서 효율적으로 데이터를 주고 받기 위해서 흐름제어라는 방식을 사용합니다. 흐름제어는 슬라이딩 윈도우 (Sliding Window) 라는 방식을 사용을 하고 있는데 윈도우 즉 받을 수 있는 메모리의 양을 적어두고 해당 메모리의 양만큼 패킷을 전송하는 방식입니다. 중간에 데이터가 유실되면 유실된 부분 부터 해서 메모리를 다시 보내줍니다. 
https://velog.io/@haero_kim/TCP-%ED%9D%90%EB%A6%84%EC%A0%9C%EC%96%B4-%EA%B8%B0%EB%B2%95-%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0
참고

- Q2. SOCKET와 TCP의 차이점? 다른점?
- A1. socket은 해당 연결의 목적지의 역할입니다. 마치 IP와 비슷한 느낌이라고 생각을 하시면 됩니다. TCP 는 프로토콜 즉 통신 방식으로 SOCEKET 연결에 TCP 프로토콜을 사용을 할 수 가 있습니다.

소켓: 네트워크 통신을 위한 인터페이스, 다양한 프로토콜(TCP, UDP 등) 사용 가능.
TCP: 신뢰성 있고 순서가 보장된 데이터 전송을 제공하는 전송 계층 프로토콜.