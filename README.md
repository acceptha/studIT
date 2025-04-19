# Backend-Interview-Question

## Information

백엔드에대한 전반적인 기초지식향상과 면접준비를위한 스터디입니다.

# CS 관련 지식

## 네트워크

- 웹 통신의 큰 흐름: <a href="./network/connect_url.md">https&#58;//www&#46;google&#46;com/을 접속</a>할 때 일어나는 일.
- <a href="./network/tcp_udp.md">TCP와 UDP</a>의 각각의 기능과 차이점 대해서 설명해보세요.
- <a href="./network/osi7_tcpIp.md">OSI 7계층과 TCP/IP 4계층</a>에 대해 설명해보세요.
- <a href="./network/routing_web.md">라우팅 기능 및 웹 서버 소프트웨어(Apache, Nginx)</a>는 OSI 7계층 중 어디서 작동하는지 설명해보세요.
- <a href="./network/websocket.md">웹 소켓(WebSocket)</a>이란 무엇이며, 언제 사용하나요?
- <a href="./network/ip.md">공인(public) IP와 사설(private) IP</a>의 차이에 대해 설명해주세요.
- CDN(<a href="./network/cdn.md">Content Delivery Network</a>)이란 무엇이며, 왜 사용하나요?
- 상태비저장(<a href="./network/cdn.md">Stateless</a>) 프로토콜이란 무엇인가요?
- <a href="./network/cookie_session.md">쿠키(Cookie)와 세션(Session)</a>의 차이점에 대해 말해주세요.
- <a href="./network/cors.md">CORS</a>란 무엇이며 이것에 대해서 설명해보세요.
- 참고자료: [유튜버 쉬운코드 네트워크](https://www.youtube.com/watch?v=oFKYzp6gGfc&list=PLcXyemr8ZeoSGlzhlw4gmpNGicIL4kMcX) 

## 운영체제

- <a href="./operating_system/process.md">프로세스</a>에 대해 설명해주세요.
- <a href="./operating_system/context_swich.md">컨텍스트 스위칭</a>에 대해 설명해보세요.
- <a href="./operating_system/thread.md">스레드</a>에 대해 설명해주세요.

- 멀티프로세스와 멀티스레드에 대해 설명해보세요.

<summary><ins>교착상태와 기아상태의 해결방법 및 스핀락, 세마포어, 뮤텍스에 대해 설명해주세요.</ins></summary>

<details>
  <summary><ins>운영체제에서 시스템콜(system call)과 인터럽트(Interrupt)는 무엇이며, 어떻게 동작하나요?</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/운영체제/시스템콜과 인터럽트/시스템콜과 인터럽트.md">시스템콜과 인터럽트</a></p>
</details>

- 프로세스 스케줄링이란 무엇이며, 어떤 알고리즘들이 사용되나요?
- 동기와 비동기의 차이(블로킹, 넌블로킹) / 장단점에 대해 설명해보세요.
- Thread-safe 하다는 의미와 설계하는 법을 설명해보세요.
- 프로세스 동기화에 대해 설명해보세요.
- 가상 메모리에 대해 설명해보세요.
- 캐시의 지역성에 대해 설명해보세요.
- 운영체제의 주요 기능은 무엇인가요?
- 부팅 과정에 대해 설명해보세요.
- 메모리 단편화(Fragmentation)란 무엇이며, 이를 해결하기 위한 방법은 무엇인가요?
- 파일 시스템의 역할과 종류에 대해 설명해보세요.
- I/O 관리와 I/O 스케줄링에 대해 설명해보세요.
- 스왑 공간(Swap Space)과 그 역할에 대해 설명해보세요.

## 데이터베이스

<details>
  <summary><ins>데이터베이스에서 인덱스를 사용하는 이유 및 장단점 그리고 알고리즘에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/인덱스/데이터베이스에서 인덱스.md">데이터베이스 인덱스</a></p>
</details>

<details>
  <summary><ins>트랜잭션및 격리수준에 대해서 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/트랜잭션/트랜잭션과 격리수준.md">트랜잭션과 격리수준.md</a></p>
</details>

<details>
  <summary><ins>ACID에 대해서 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/ACID.md">acid.md</a></p>
</details>

<details>
  <summary><ins>정규화에 대해서 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/정규화.md">정규화.md</a></p>
</details>

<details>
  <summary>JOIN에 대한 설명과 원리 그리고 종류.</summary>
  </br>
</details>

<details>
  <summary>RDBMS vs NOSQL에 대해서 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>Redis에 대해서 간단히 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>Redis와 Memcached의 차이에 대해서 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary><ins>Elastic Search에 대해서 간단히 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/인덱스/ElasticSearch.md">Elastic Search!!!!!</a></p>
</details>

<details>
  <summary><ins>Elastic Search의 인덱스구조와 RDBMS의 인덱스 구조의 차이에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/인덱스/ElasticSearch.md">Elastic Search!!!!!</a></p>
</details>

<details>
  <summary><ins>Elastic Search의 키워드 검색과 RDBMS의 LIKE 검색의 차이에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/인덱스/ElasticSearch.md">Elastic Search!!!!!</a></p>
</details>

<details>
  <summary>MongoDB에 대해서 간단히 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>CAP 이론과, Eventual Consistency에 대해서 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary><ins>옵티마이저에 대해 설명하세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/옵티마이저/옵티마이저.md">옵티마이저</a></p>
</details>

<details>
  <summary><ins>파티셔닝 리플리케이션 샤딩에 대해 설명하세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/데이터베이스/파티셔닝_리플리케이션_샤딩.md">파티셔닝_리플리케이션_샤딩</a></p>
</details>

<details>
  <summary>postgresql과 mysql의 차이점.</summary>
  </br>
</details>

## 자료구조/알고리즘

보통의 자료구조/알고리즘적 지식은 코딩테스트로 검증합니다.  
하지만 아래의 개념을 적어도 이해는 한다고 생각하니, 혹시 모르는 부분이 있을 경우 학습을 권장합니다.
<p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/01_자료구조.md">자료구조 및 알고리즘</a></p>

<details>
  <summary><ins>시간 복잡도에대한 예시와 설명.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/02_시간복잡도.md">시간복잡도</a></p>
</details>

<details>
  <summary><ins>배열과 링크드 리스트의 차이를 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/03_배열과링크드리스트.md">배열과 링크드 리스트</a></p>
</details>

<details>
<summary><ins>List와 Set의 차이에 대해서 설명해주세요.</ins></summary>
</br>
<p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/04_List와Set.md">List와Set</a></p>
</details>

<details> 
  <summary><ins>Hash Function, HashTable에 대해서 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/05_hashFuntion_HashTable.md">hashFuntion_HashTable</a></p>
</details>

<details>
  <summary><ins>Stack과 Queue, Tree와 Heap의 구조에 대해 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/06_Stack_Queue_Tree_Heap.md">Stack_Queue_Tree_Heap</a></p>
</details>

<details>
  <summary><ins>Tree, Binary Tree, BST, AVL Tree에 대해서 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/07_Tree_BinaryTree_BST_AVL.md">Tree, Binary Tree, BST, AVL Tree</a></p>
</details>

<details>
  <summary><ins>피보나치 수열을 코드로 구현하는 방법에 대해서 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/08_피보나치.md">피보나치 수열을 코드로 구현하는 방법</a></p>
</details>

<details>
  <summary><ins>DFS, BFS에 대해서 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/09_DFS_BFS.md">DFS, BFS</a></p>
</details>

<details>
  <summary><ins>정렬, 탐색에 대해 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/10_정렬과탐색.md">정렬 탐색</a></p>
</details>

<details>
  <summary><ins>동적프로그래밍에 대해 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/자료구조/11_동적프로그래밍.md">동적프로그래밍</a></p>
</details>

## 암호학/보안(간단한 정도)

<details>
  <summary><ins>CSRF(Cross-Site Request Forgery)와 XSS(Cross-Site Scripting)의 차이점과 방지 방법에 대해 설명해주세요.</ins></summary>
  </br>
      <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/네트워크/5주차/xss_csrf.md">CSRF(Cross-Site Request Forgery)와 XSS(Cross-Site Scripting)</a></p>
</details>

<details>
  <summary>비대칭키 암호화, 대칭키 암호화에 대해 간단히 설명해주세요.</summary>
  </br>
</details>

<details>01_단방향암호화
  <summary>단방향 암호화에 대해서 간단히 설명해주세요.</summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/암호학_보안/01_단방향암호화.md">단방향암호화</a></p>
</details>

<details>
  <summary><ins>JWT에 대해서 간단히 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/%EB%B3%B4%EC%95%88/JWT_OAuth/jwt.md">JWT 설명</a></p>
</details>

<details>
  <summary><ins>OAuth에 대해서 간단히 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/%EB%B3%B4%EC%95%88/JWT_OAuth/oauth.md">OAuth 설명</a></p>
</details>

<details>
  <summary><ins>JWT와 OAuth의 차이는 무엇이 있을까요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/%EB%B3%B4%EC%95%88/JWT_OAuth/jwt vs oauth.md">JWT vs OAuth</a></p>
</details>

<details>
  <summary><ins>SQL Injection에 대해서 간단히 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/암호학_보안/02_SQL_injection.md">SQL_injection</a></p>
</details>

<details>
  <summary>XSS에 대해서 간단히 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>CSRF에 대해서 간단히 설명해주세요.</summary>
  </br>
  <p></p>
</details>

## 컴파일러

<details>
  <summary>스크립트 언어와 컴파일 언어를 나열하고 차이점을 설명해주세요.</summary>
  </br>
</details>

# 언어 관련

## Python

<details>
  <summary>List와 Tuple의 차이에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary><ins>파이썬 코루틴에 대해 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/코루틴/코루틴.md">코루틴</a></p>
</details>

<details>
  <summary>파이썬 데코레이터에 대해 아는대로 설명해주세요.</summary>
  </br>
</details>


<details>
  <summary>MRO에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>Magic Method에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>__new__와 __init__의 차이에 대해 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>__repr__와 __str__의 차이에 대해 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>r string과 u string에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>Call by Assignment에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>파이썬에서의 접근제어지시자에 대해 아는대로 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>global과 nonlocal 키워드의 차이에 대해 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>classmethod와 staticmethod의 차이에 대해 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>파이썬의 주요 특징은 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary><ins>파이썬의 GIL(Global Interpreter Lock)이란 무엇인가요?</ins></summary></br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/GIL/gil.md">GIL 설명</a></p>
</details>

<details>
  <summary><ins>파이썬의 메모리 모델에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/Memory/model.md">Python Memory Model</a></p>
</details>

<details>
  <summary><ins>파이썬에서 메모리 관리는 어떻게 이루어지나요?</ins></summary></br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/Memory/management.md">Python Memory Management</a></p>
</details>

<details>
  <summary><ins>파이썬의 가비지 컬렉션(Garbage Collection)은 어떻게 작동하나요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/Memory/garbage_collections.md">Python Garbage Collections</a></p>
</details>

<details>
  <summary></summary>
  </br>
</details>

<details>
  <summary>람다 함수(lambda function)란 무엇이며, 언제 사용하나요?</summary>
  </br>
</details>

<details>
  <summary>파이썬에서 예외 처리 방법에 대해 설명해 주세요.</summary>
  </br>
</details>

<details>
  <summary></summary>
  </br>
</details>

<details>
  <summary>파이썬의 모듈(Module)과 패키지(Package)에 대해 설명해 주세요.</summary>
  </br>
</details>

<details>
  <summary>정규 표현식(Regular Expressions)을 사용하여 문자열을 처리하는 방법은 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary><ins>파이썬의 클래스와 객체 지향 프로그래밍(OOP)에 대해 설명해 주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/객체지향 프로그래밍/객체지향 프로그래밍.md">파이썬 객체지향 프로그래밍</a></p>
</details>

<details>
  <summary><ins>파이썬에서 다중 상속(Multiple Inheritance)은 어떻게 구현하나요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/다중상속/다중상속.md">다중상속</a></p>
</details>

<details>
  <summary>파이썬의 with 구문에 대해 설명해 주세요.</summary>
  </br>
</details>

<details>
  <summary>파이썬의 `*args`와 `**kwargs`는 무엇이며, 어떻게 사용하나요?</summary>
  </br>
</details>

<details>
  <summary>파이썬에서 데이터베이스에 접근하는 방법에 대해 설명해 주세요.</summary>
  </br>
</details>

<details>
  <summary><ins>파이썬의 `asyncio` 라이브러리를 사용하여 비동기 프로그래밍을 하는 방법은 무엇인가요?</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/asyncio/asyncio.md">asyncio</a></p>
</details>

<details>
  <summary>파이썬의 정적 타이핑(Static Typing)을 지원하는 방법은 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary>파이썬에서 메타 클래스(Metaclass)는 무엇이며, 어떻게 사용하나요?</summary>
  </br>
</details>

<details>
  <summary>파이썬의 `deepcopy`와 `shallow copy`의 차이는 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary>파이썬에서의 변수 범위(Scope)와 네임스페이스(Namespace)에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>파이썬의 예외 클래스 계층 구조에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>파이썬의 다중 상속 문제를 해결하기 위한 방법은 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary>파이썬의 duck typing에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>파이썬에서의 'Non-Local' 변수는 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary>파이썬에서의 `super()` 함수는 어떻게 작동하나요?</summary>
  </br>
</details>

- 파이썬의 동적 타이핑(Dynamic Typing)과 정적 타이핑(Static Typing)의 차이는 무엇인가요?
- 파이썬의 인터프리터(Interpreter)와 컴파일러(Compiler)의 차이는 무엇인가요?
- 파이썬의 컴프리헨션(Comprehension) 종류에 대해 설명해주세요.
- 리스트 컴프리헨션(List Comprehension)이란 무엇인가요?
- 파이썬의 제너레이터(Generator)와 이터레이터(Iterator)의 차이점은 무엇인가요?
- 파이썬의 컨텍스트 매니저(Context Manager)와 `with` 구문에 대해 설명해주세요.
- 파이썬의 `__slots__`은 무엇이며, 언제 사용하나요?
- 파이썬의 `None` 타입은 무엇이고 어떻게 사용하나요?
- 파이썬에서의 자료형 힌팅(Type Hinting)은 무엇이며, 어떻게 사용하나요?
- 파이썬의 프로퍼티(Property)와 게터(Getter), 세터(Setter)에 대해 설명해주세요.
- 파이썬의 문서화 도구(Documentation Tools)에 대해 설명해주세요 (예: Sphinx).

<details>
  <summary><ins>파이썬의 내장시퀀스에대해서 설명해주세요</ins></summary>
  </br>
<p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/파이썬 내장시퀀스/내장시퀀스.md">내장시퀀스</a></p>
</details>

<details>
  <summary><ins>gunicorn,uvicorn,fastapi들의 각각의 역할과 흐름에대해서 설명해주세요</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/python/fastapi/gunicorn,uvicorn,fastapi 등 프로세스.md">gunicorn,uvicorn,fastapi</a></p>
</details>

## Go

<details>
  <summary><ins>Go의 주요 특징은 무엇인가요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/go의 주요특징/go의 주요특징.md">go의 주요특징</a></p>
</details>

<details>
  <summary><ins>Go의 패키지 시스템에 대해 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/패키지 시스템/패키지 시스템.md">패키지 시스템</a></p>
</details>

<details>
  <summary><ins>Go에서 변수 선언 방법에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/변수 선언 방법/변수선언방법.md">변수선언방법</a></p>
</details>

<details>
  <summary><ins>Go의 포인터(Pointer)에 대해 설명해주세요.</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/go의 포인터/go포인터.md">go포인터</a></p>
</details>

<details>
  <summary>Go의 구조체(Struct)와 인터페이스(Interface)의 차이는 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary><ins>Go의 고루틴(Goroutine)과 Go에서 채널(Channel) 이란 무엇인가요?</ins></summary>
  </br>
  <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/고루틴과 고채널/고루틴과 고채널.md">고루틴과 고채널</a></p>
</details>

<details>
  <summary><ins>Go의 defer 키워드에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/defer함수/defer.md">defer 함수</a></p>
</details>

<details>
  <summary><ins>Go에서 슬라이스(Slice)와 배열(Array)의 차이는 무엇인가요? & Go에서 map이란 무엇인가요?
  </ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/배열과슬라이스/배열과슬라이스.md">배열과슬라이스</a></p>
</details>

<details>
  <summary>Go의 가비지 컬렉션(Garbage Collection)은 어떻게 작동하나요?</summary>
  </br>
</details>

<details>
  <summary><ins>Go의 메서드(Method)와 함수(Function)의 차이는 무엇인가요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/프로그래밍 언어/golang/go의 메소드vs함수/go의 메소드vs함수.md">go의 메소드vs함수</a></p>
</details>

<details>
  <summary>Go에서 인터페이스(Interface)는 어떻게 사용하나요?</summary>
  </br>
</details>

<details>
  <summary>Go에서 에러 처리 방법에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>Go의 빌트인 테스트 도구에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>Go 모듈(Module)이란 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary>Go의 동시성(Concurrency)과 병렬성(Parallelism)의 차이는 무엇인가요?</summary>
  </br>
</details>

<details>
  <summary>Go에서 context 패키지는 언제 사용하나요?</summary>
  </br>
</details>

<details>
  <summary>Go의 panic과 recover에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>Go에서 HTTP 서버를 만드는 방법에 대해 설명해주세요.</summary>
  </br>
</details>

## 최신기술관련

### gRPC

<details>
  <summary><ins>gRPC란 무엇인가요? gRPC의 주요 장점과 단점은 무엇인가요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/최신기술/grpc/grpc.md">gRPC</a></p>
</details>

<details>
  <summary>gRPC에서 프로토콜 버퍼(Protocol Buffers)는 무엇이며, 어떻게 사용하나요?</summary>
  </br>
</details>

<details>
  <summary>gRPC에서 서비스 정의 파일(.proto 파일)은 어떻게 작성하나요?</summary>
  </br>
</details>

<details>
  <summary>gRPC의 스트리밍(Stream) 기능에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>gRPC의 보안(예: TLS/SSL) 설정 방법에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>gRPC의 로드 밸런싱(Load Balancing) 기능에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary>gRPC의 인터셉터(Interceptor)란 무엇이며, 어떻게 사용하나요?</summary>
  </br>
</details>

<details>
  <summary>gRPC의 버전 관리(versioning) 방법에 대해 설명해주세요.</summary>
  </br>
</details>

<details>
  <summary><ins>RESTful과 GRAPHQL이란 무엇인지 + gRPC와 RESTful API의 차이점은 무엇인가요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/네트워크/7주차/restful_graphql_grpc.md">REST와 GraphQL, gRPC</a></p>
</details>

### Apache Kafka

<details>
  <summary><ins>Apache Kafka란 무엇인가요?<br>
 + Kafka의 주요 구성 요소는 무엇인가요?<br>
 + Kafka의 프로듀서(Producer)와 컨슈머(Consumer)의 역할은 무엇인가요?<br>
 + Kafka에서 토픽(Topic)과 파티션(Partition)의 개념에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/최신기술/kafka/kafka.md">Kafka</a></p>
</details>

<details>
  <summary><ins>Kafka의 브로커(Broker)와 클러스터(Cluster)의 차이는 무엇인가요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/최신기술/kafka/kafka_ecosystem.md">Kafka System</a></p>
</details>

<details>
  <summary>Kafka의 Zookeeper는 어떤 역할을 하나요?</summary>
  </br>
</details>

<details>
  <summary><ins>Kafka의 메시지 보장(Messaging Guarantees)에 대해 설명해주세요.</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/최신기술/kafka/messaging_guarantee.md">Messaging Guarantees</a></p>
</details>

<details>
  <summary><ins>Kafka에서 Consumer Group이란 무엇이며, 어떻게 작동하나요?</ins></summary>
  </br>
    <p><a href="https://github.com/ssr-snj-study/Backend-Interview-Study/blob/main/최신기술/kafka/consumer_group.md">Consumer Group</a></p>
</details>

<details>
  <summary>Kafka의 리플리케이션(Replication)과 데이터 복제는 어떻게 이루어지나요?</summary>
  </br>
</details>

<details>
  <summary>Kafka에서 메시지의 오프셋(Offset)이란 무엇인가요?</summary>
  </br>
</details>

### 디자인 패턴

- 싱글톤 패턴에 대해서 설명해주세요.
- 가교 패턴(브릿지 패턴)에 대해서 설명해주세요.
- 전략 패턴에 대해서 설명해주세요.
- 빌더 패턴에 대해서 설명해주세요.
- 팩토리 메서드 패턴에 대해서 설명해주세요.
- 퍼사드 패턴에 대한 예를 들어주세요.

### 테스트

<details>
  <summary>테스트 코드에 대해서 어떻게 생각하고, 작성하나요?</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>TDD를 알고 있나요? TDD에 대해서 어떻게 생각하나요?</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>테스트 커버리지에 대해서 어떻게 생각하나요?</summary>
  </br>
</details>

### 인프라/클라우드

<details>
  <summary>AWS 인프라를 구축해보았다면 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>로드 밸런서에 대해서 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>리버스 프록시에 대해서 설명해주세요.</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>Fault-tolerant(무정지) 시스템으로 가기 위해 필요한 방법에 대한 생각을 말해주세요. </summary>
  </br>
</details>

### 컨테이너

제가 아직 도커, 쿠버네티스에 익숙하지 않아 공부가 좀 더 필요합니다.  
관련해서 질문을 받아본적은 없으나, 일반적인 질문을 담아보았습니다.

<details>
  <summary>Docker란 무엇이고 컨테이너 가상화를 왜 사용할까요?</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>컨테이너 환경에서의 디버깅은 어떤식으로 하며 상대적으로 어려운 점은 무엇인가요?</summary>
  </br>
  <p></p>
</details>

### DevOps

<details>
  <summary>CI/CD가 무엇인가요? 왜 CI/CD가 장점이 될까요?</summary>
  </br>
</details>

## 면접 꿀팁

회사의 기술스택에 관심을 가져보세요. 학습능력이 좋음을 어떤식으로 보여줄 수 있을까요?

본인이 수행한 프로젝트를 유의미한 트래픽이 나올정도로 해본 경험을 높게 평가하는 회사가 많습니다.

두괄식으로 답변하도록 합시다. (사실 힘듭니다. 그렇게 될 수 있게끔 연습 또 연습!)

프로젝트를 수행할 때, 내가 이 기술을 단순히 좋아보여서 사용한 것이 아니라, 많은 고민을 했음을 보여주도록 하세요. 가장 간단한 질문으로는 '왜 그 기술을 사용했나요?', '그 기술 말고 다른 기술은 왜 사용하지 않았나요?', '대체할만한 기술이 있나요?' 등이 있습니다.

#### 참고자료나 영상출처

[백엔드면접팁2](https://www.youtube.com/watch?v=NzlFLoALqYs&t=2s)
[면접 꿀팁 영상!](https://youtu.be/4XNJFAPnZrY)
