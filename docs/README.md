# **구현할 기능 목록**

1. 게임 시작 기능
2. 숫자 생성 기능
   1. 컴퓨터가 1에서 9까지 서로 다른 임의의 수 3개를 선택하기
3. 숫자 입력 기능
   1. 사용자가 1에서 9까지 서로 다른 3자리 숫자를 입력하는 기능
   2. 예외처리
      1. 숫자가 아닌 문자를 입력하는 경우
      2. 숫자 범위를 벗어난 경우
      3. 세 자리 수가 아닌 경우
      4. 입력한 수가 서로 다른 숫자가 아닌 경우
4. 숫자 출력 기능
   1. 입력한 숫자의 스트라이크, 볼, 낫싱을 판별하는 기능
      1. 스트라이크 : 입력한 숫자의 자리 별로 2번의 숫자와 비교하고, 같은 자리에 같은 숫자가 몇 개 있는지 판별
      2. 볼 : 입력한 숫자의 자리 별로 2번의 숫자와 비교하고, 다른 자리에 같은 숫자가 몇 개 있는지 판별
      3. 낫싱 : 겹치는 숫자가 없는 경우
   2. 판별한 결과를 화면에 출력하는 기능
      1. 스트라이크와 볼 개수를 출력
      2. 볼과 스트라이크가 같이 출력될 경우, 볼을 먼저 출력한다.
5. 게임 종료 기능
   1. 컴퓨터가 저장한 숫자를 맞히면 게임이 종료되는 기능
   2. 게임 종류 후, ‘다시 시작하기’ 혹은 ‘게임 종료하기’를 선택할 수 있는 기능
6. 게임 커맨드 입력 기능
   1. 5번에 이어, '1'을 입력할 경우 게임 재시작, '2'를 입력할 경우 프로그램을 종료하는 기능.
7. 잘못된 값을 입력한 경우, `throw` 예외 처리로 애플리케이션을 종료하는 기능
