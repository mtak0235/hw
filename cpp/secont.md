# 주어진 다항식의 차수는 n,m이고, add 수행시 두 다항식 중 높은 차수가 n이라고 가정할 때, Polynomial 클래스의 메소드인 add 연산의 시간복잡도를구하여 제출하시오

add 의 연산은 배열에 0 할당하는 n번, 새 배열에 값을 복사하는 것 n + m번 총 2n + m번이다. 빅오로 표기하면 O(n)이다. 