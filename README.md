# 백준 algorithm
<br>

## 👻 여러가지 자료구조를 이용한 문제풀이

### 1. 배열과 리스트
배열 : 데이터를 삭제할때 O(n)만큼의 시간이 걸린다.<br>
연결리스트 : 삭제할 위치를 정확하게 알고있으면 연결을 끊어주면 되기 때문에 O(1)이 소요된다.<br>
<br>

### 2.스택
1.push(맨뒤에 새로운 요소 삽입) - O(1)<br>
2.Pop(맨뒤에 원소 추출) - O(1)<br>
3.top(맨위의 요소 확인) - O(1)<br>
.empty(비어있는지 확인) - O(1)<br>

문제1. 키로거 https://www.acmicpc.net/problem/5397

### 3. 큐
먼저 들어간 데이터가 먼저 나오는 형식<br>
연결리스트+큐 조합이 수행 시간 관점에서 효율적<br>
JS에서는 Dictionary 자료형을 이용하면 큐를 쉽게 구현할 수 있다.<br>

### 4. 집합
항목이 유일한지 확인할때 필요한 강력한 자료 구조중 하나.<br>
집합은 해시 테이블의 구현을 기초로 하기때문에 O(1)상수 시간에 유일한 항목을 확인하고 추가할 수 있다.<br>
js의 Set 객체는 중복되지 않은 고유한 값을 저장하기 때문에 순서가 중요하지 않고 중복된 값은 허용하지 않는다.
