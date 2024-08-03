---
배열:
  - 데이터 순서==메모리 물리적 순서
  - 탐색 O(1)
연결리스트:
  - 데이터 순서 != 메모리 물리적 순서
  - 탐색 O(n)
---
- ArrayList와 LinkedList는 모두 List 인터페이스를 구현하지만, 내부 구현과 성능 특성이 다릅니다.  
- ArrayList는 배열 기반으로, 랜덤 접근이 빠르지만 삽입/삭제가 느립니다.  
- LinkedList는 노드 기반으로, 순차 접근이 필요하지만 삽입/삭제가 빠릅니다.  
  - 싱글리 링크드 리스트는 다음노드 참조만(단방향) 가지는 링크드 리스트입니다.  
  - 더블리 링크드 리스트는 이전노드, 다음노드 참조(양방향 참조)를 가지는 링크드 리스트입니다.