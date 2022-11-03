### Blackjack With Monte-Carlo Control
강화학습 BlackJack 프로젝트
- 최적 Policy를 학습시킨 Agent를 사용하여, 블랙잭 게임을 시뮬레이션한 뒤 승률을 계산
- Evaluation, Improvement를 optimal policy 파이를 구할 때까지 반복
- Blackjack 학습 알고리즘
  - 높은 승률을 달성할 수 있는 최적의 policy를 찾음
  
요구사항
- 플레이어 학습
- 플레이어와 딜러가 1000번의 게임 진행
- 1000번의 게임이 끝난 후 플레이어의 승률을 계산
- 매 게임별 플레이어의 소지금 변화를 그래프로 시각화
- 딜러는 게임이 끝났을 때, 남은 카드의 수를 확인
  - 15장 이상이라면 해당 덱을 다음 게임에서 그대로 사용
  - 15장 미만이라면 52장의 셔플된 새로운 카드를 기존 덱에 추가