# black-jack-cpp
Command line black jack game with cpp programming language

# 블랙잭의 규칙
0. 게임의 최소 ~ 최대 배팅금액을 통해 시작
1. 딜러가 플레이어에게 카드를 한장씩 돌리고 자신의 카드를 오픈
2. 딜러가 다시 플레이어에게 카드를 한장씩 돌리고 두번째 딜러의 카드는 비공개(플레이어의 카드는 전부 공개)
3. 플레이어는 자신의 오픈된 카드와 딜러의 카드를 보고 자신의 카드 숫자의 합을 21에 맞게 맞춰야한다.
4. A카드는 1또는 11로 사용될 수 있음. -> 따라서 카드가 두장일 때 블랙잭의 조합은 A카드 + 10카드
5. 현재 카드의 합이 20이하라면 카드를 더 받을 수 있지만, 받은 카드와의 총 합이 21을 넘어가면 패배(버스트)
6. 플레이어의 차례가 종료되면, 딜러의 차례가 시작된다. 딜러는 비공개 카드를 공개하고, 합이 16이하면 무조건 히트, 17이상이면 무조건 스테이한다.

# 블랙잭의 용어
0. 히트(hit) : 처음 두 장의 상태에서 카드를 한장 더 받는 것
1. 스테이(stay) : 카드를 더 뽑지 않고 차례를 마치는 것.
2. 보험(insurance) : 딜러의 오픈된 카드가 에이스라면 보험금을 걸 수 있다. 
   - 딜러가 블랙잭이라면 플레이어는 보험금의 두 배를 보상 받는다.
   - 딜러가 블랙잭이아니라면 플레이어는 보험금을 잃는다.
3. 푸쉬(push) : 플레이어와 딜러의 카드 합이 같은 경우 비기게 되고 배팅 금액을 돌려받는다.
4. 서렌더(surrender) : 플레이어가 게임을 포기하고 배팅 금액의 절반을 돌려받는다. 단, 딜러가 블랙잭을 가지고 있을 경우 게임 포기는 불가하다.

# TODO
- Card class

- Deck class

- Player class

- Dealer class

- UserInterface class//

- BlackJack class
