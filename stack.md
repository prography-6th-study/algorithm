# Stack

- LIFO (Last-In, First-Out)

- push() : 데이터를 스택에 넣기
    - python에서는 list.append()로 push 구현
- pop() : 데이터를 스택에서 꺼내기
    - python에서 list.pop() 메서드 사용 가능

- 장점
    - list를 가져다 쓰는 등 구현이 쉽다. 
    - 데이터 저장/ 읽기 속도가 빠르다.

- 단점
    - 파이썬의 경우 재귀 함수는 1000번까지 호출 가능 (sys.setrecursionlimitdmf 이용해서 재귀 최대깊이 조정 가능)
    - 데이터 검색 속도는 최악의 경우 O(n)의 시간복잡도