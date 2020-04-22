# Sort 

- 버블정렬, 선택 정렬, 삽입 정렬은 O(n^2)이라 잘 쓰지 않는다.
- Quick Sort, Merge Sort, Heap Sort는 O(nlogn) 이라 많이 사용
    - Quick Sort는 최악의 경우 O(n^2)이지만 O(nlogn) 일때는 셋 중 가장 빠름
        - 최악의 경우를 피하려면, pivot 값을 random으로 잡거나, 중앙값 사용
    - 최악의 상황에서도 Merge Sort와 Heap Sort는 O(nlogn)을 유지

- sort, sorted 비교
    - sort는 이미 존재하는 list를 정렬 (list.sort())
    - sorted는 존재하는 list를 가져다가 새로운 객체(list)를 생성하고 정렬 (sorted(list))