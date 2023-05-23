# 04-객체

- 사용자로부터 2차원 그래프의 좌표(x, y)를 입력 받는 Void2D 객체를 정의하시오.
- Void2D 객체는 생성자(__init__)와 distance 함수를 가짐.
- 생성자에서는 x, y 좌표의 값을 초기화하고 지금까지 생성자가 몇번 호출되었는지 횟수를 나타내는 변수 total을 1씩 증가시킴.
- distance 함수에서는 (0, 0)으로부터 생성자를 통해 설정한 좌표 (x,y) 까지의 거리를 계산하여 반환함.
- 자동으로 x, y 좌표가 초기화 된다고 할때 distance 함수를 이용하여 (0, 0)에서 (x, y)까지의 거리와 생성자의 호출 횟수를 출력하는 파이썬 프로그램을 작성하시오.

*주의
1) 생성자는 채점 프로그램에서 자동으로 호출함
2) total 변수는 객체 전체가 공유해야함
3) distance 함수에서 출력하는 것이 아닌 distance 함수의 반환값과 total 값을 print() 함수를 이용하여 출력해야함
4) 출력할 때 거리는 소수점 둘째자리까지 출력
5) distance 함수에서 거리 계산 시, math 모듈의 sqrt, pow 함수를 활용한다. (e.g., math.sqrt(A): A의 제곱근, math.pow(A, B): A의 B제곱)
  
- 출력 예제
  * Distance: 5.83, Initialization: 2
