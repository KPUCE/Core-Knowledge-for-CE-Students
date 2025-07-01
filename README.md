# Core-Knowledge-for-CE-Students
  * 컴퓨터공학을 전공하는 개발자가 필수적으로 알아야 하는 핵심 지식 정리
  * 아래의 개념들을 본인 스스로 종이와 연필을 이용하여 1/2페이지에서 1페이지 내로 정리한 후, 온라인 매체에 다시 기록한 후 해당 개념은 별도로 찾지 않아도 머리 속에 남아있도록 학습 필요
  * 개념만을 요약해서 정리하며, 세부 사항은 추후 찾아서 학습하면 됨

## 1. 기본 개념

### 캐싱(Caching)
  * 캐싱의 기본 개념, 캐싱의 장점, 캐싱이 효용성을 가지기 위한 조건, 캐싱의 제약점, 캐싱의 응용분야(캐시메모리, 버퍼캐시, 가상메모리, 웹 캐싱, 분산데이터베이스, CDN 등)

### 해싱(Hashing: Hash Table, Hash Map)
  * 해싱의 기본 개념, 해싱의 특징, 장점, 제약점, 해싱의 응용분야
    
## 2. 자료 구조와 알고리즘

### 시간복잡도(time Complexity)
  * 시간복잡도의 정의, 시간복잡도가 중요한 이유, 대표적인 자료구조들의 시간 복잡도

### 배열(array)과 연결리스트(linked list)
  * 특징, 응용분야, 삽입/삭제 시간복잡도, 탐색 시간복잡도

### 스택(Stack)과 큐(Queue)
  * 특징, 응용분야, 삽입/삭제 시간복잡도, 탐색 시간복잡도

### 트리(Tree), 이진트리, heap, 이진탐색트리(Binary Search Tree), **균형이진탐색트리(Balanced Binary Search Tree)**
  * 특징, 응용분야, 삽입/삭제 시간복잡도, 탐색 시간복잡도
  * 균형이진탐색트리의 종류(AVL 트리, Red-Black Tree, B tree, B+ Tree), 균형이진탐색트리의 장점 및 다양한 응용분야

### 정렬과 탐색 알고리즘 (Sorting and Searching algorithm)
  * 정렬 알고리즘(합병정렬, 퀵정렬, 힙정렬)
  * 탐색 알고리즘(이진탐색, 해시기반탐색)
    
### graph 자료구조의 주요 알고리즘
  * 그래프 탐색 알고리즘(Depth-First Search, Breadth-First Search)
  * 최단경로 알고리즘(Shortest Path Algorithm): 개념, 응용분야
  * 최소신장트리 알고리즘(Minimum Spanning Tree Algorithm): 개념, 응용분야

## 3. 운영체제와 UNIX 시스템프로그래밍

### Process와 Thread 개념 이해
  * Process와 thread의 개념 이해, process 상태(특히 ready, running, block 상태), 문맥교환(context switching) 이해, Multithreading을 사용하는 이유
  * Process Scheduling 기법의 이해, 성능 지표 이해

### *병행처리(Concurrent Processing)*
  * 병행처리의 개념 이해, 병행처리의 장점, 병행처리시 문제점(race condition), 문제점 해결 방안 개념이해, 상호배제와 동기화의 이해
  * 상호배제와 동기화 툴: Mutually exclusive lock, Semaphore(binary semaphore, counting semaphore), reader/writer lock, condition variable, monitor
  * 병행처리 문제점: deadlock과 starvation의 이해, dining philosopher 문제의 애해 및 해결방법 이해

### 메모리 관리(Memory Management)
  * 메모리 관리 기법(특히 paging과 segmentation 기법의 이해)
  * 가상메모리(Virtual Memory)의 개념 이해, page replacement algorithm의 이해

### File System과 File, Directory
  * 파일시스템의 구조, Virtual File System의 이해
  * file과 관련된 primitive의 동작 원리 이해
  * Directory 구조에 대한 이해, 경로명을 찾는 방법 이
    
### 프로세스간 통신기법(IPC: Inter Process Communication)
  * IPC 기법이 필요한 이유, 대표적인 IPC 기법(pipe, message passing, shared memory, semaphore, socket)

