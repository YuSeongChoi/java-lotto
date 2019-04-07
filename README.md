# 우아한 테크코스 3주차 미션 - "로또 만들기"
 - 최유성
 
# 기능 요구사항
 1. 로또 게임 기능을 구현한다. (로또 규칙에 맞게)
 2. 로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야한다.
 3. 로또 1장의 가격은 1000원이다.
 4. 로또 당첨 금액은 고정되어 있다고 가정한다.
 5. 총 수익률을 계산해 출력해야한다.
 
# 고려해야할 문제
 1. 8500원등 1000원으로 나누어 떨어지지않을경우는? ->  구입이 가능한 수의 로또만을 발급해야한다.
 2. 만약에 돈을 입력하지 않는다면? -> 다시 입력하라는 메시지를 출력하자!
 3. 만약에 돈을 1000원 미만으로 입력한다면? -> 다시 입력하라는 메시지를 출력하자!
 
# 어떻게 구현할 것인가
 1. 1개의 클래스는 Lotto에 대한 Data를 관리하자(Lotto)!
 2. 다른 클래스는 Lotto에 대한 값을 받아 당첨되었는지 확인하자!(WinningLotto)
 3. 다른 클래스는 Lotto게임 규칙에 따라 값을 계산하자!
 4. 다른 클래스는 위의 클래스를 활용해 프로그램을 돌아가게하자!
 
