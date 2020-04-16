# Queue

- 줄을 서는 것과 유사
- FIFO (First-In, First-Out) 방식

- list를 queue 또는 deque로 사용하면 안된다. 코테 진행시 collections.deque를 써야함.
- queue.Queue는 멀티스레딩을 위해 만드러진 큐이고 매우 느림 (스레드 간 작업 조율에 사용)
