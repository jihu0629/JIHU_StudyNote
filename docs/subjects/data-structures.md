---
tags:
  - 자료구조
  - 알고리즘
---

# 자료구조 (예시 페이지)

이 페이지는 MkDocs Material의 다양한 기능을 보여주기 위한 예시입니다. 실제 내용으로 자유롭게 바꿔서 사용하세요.

## 스택 (Stack)

스택은 **LIFO(Last In First Out)** 구조를 가지는 자료구조입니다.

!!! note "핵심 연산"
    - `push(x)`: 원소 `x`를 스택 맨 위에 추가
    - `pop()`: 스택 맨 위 원소를 제거하고 반환
    - `peek()`: 맨 위 원소를 제거하지 않고 확인

=== "Python"

    ```python
    stack = []
    stack.append(1)   # push
    stack.append(2)
    top = stack.pop()  # pop -> 2
    ```

=== "Java"

    ```java
    Deque<Integer> stack = new ArrayDeque<>();
    stack.push(1);
    stack.push(2);
    int top = stack.pop(); // 2
    ```

## 큐 (Queue)

큐는 **FIFO(First In First Out)** 구조입니다.

!!! warning "헷갈리기 쉬운 점"
    스택과 큐는 삽입은 같지만, 꺼내는 순서가 반대입니다. 시험에서 자주 나오는 함정이니 주의하세요.

## 체크리스트

- [x] 스택 개념 정리
- [x] 큐 개념 정리
- [ ] 트리(Tree) 개념 정리
- [ ] 그래프(Graph) 개념 정리

## 참고 자료

- [ ] 교재 3장 다시 읽기
- [ ] 관련 백준 문제 5개 풀기
