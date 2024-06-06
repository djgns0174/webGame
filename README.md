# webGame

- 팀 이름 : Fortress Duels: Dynamic Warfare
- 프로젝트 주제 : 2인용 포트리스 심화 (로컬코옵)

- 추진계획 : UI 및 컨셉 기본 게임 틀 - 스킬 및 공격 구체화 - 캐릭터 및 움직임 구현 - 지형 구현 - UX 및 버그 잡기

1. UI 및 컨셉 기본 게임 틀

   - [x] 1.1 배경,폰트, 색상 결정
   - [x] 1.2 HTML 구조 설계
   - [x] 1.3 Mode (Battle, Target) 구분
   - [x] 1.4 대포 발사 매커니즘 구현
   - [x] 1.5 대결 구도 구현
   - [x] 1.6 HP, 스코어 구현
   - [x] 1.7 Battle 모드 틀, Target 모드 틀

2. 스킬 및 공격 구체화

   - [x] 2.1 스킬 적용 매커니즘 디자인
   - [x] 2.2 Tank 선택 가능
   - [x] 2.3 공격 스킬 매커니즘 디자인
   - [x] 2.4 공격 스킬 매커니즘 적용
   - [x] 2.5 방어 스킬 매커니즘 디자인
   - [x] 2.6 방어 스킬 매커니즘 적용
   - [x] 2.7 포탄 쏠 때 효과음
   - [x] 2.8 좌우로 움직일 때 효과음
   - [x] 2.9 포탄각도 조절할 때 효과음
   - [x] 2.10 맞았을 때 효과음
   - [x] 2.11 스킬 사용 시 효과음
   - [x] 2.12 게임 엔딩 시 효과음
   - [x] 2.13 맞지 않았을 때 효과음
   - [x] 2.14 스킬에 이미지 적용
   - [x] 2.15 target 모드에도 적용
   - [x] 2.16 target 모드에서 과녁?? 이미지 디자인 및 적용
   - [ ] 2.17 page 마다 bgm 적용
   - [ ] 2.18 모든 스킬은 한 턴에 한 번 사용할 수 있게 (이건 제일 마지막에 할 거임)

- battle 모드

공격스킬

area : 상대 탱크 크기 증가
chance : 2회 기회
damage : 공격력 2배
big : 본인 포탄 크기 증가

방어스킬

small : 다음 턴에 상대 미사일 크기 감소
decrease : 다음 턴에 내 탱크 크기 감소
move : 이동거리 2배 증가
hp : 체력 50 회복

- target 모드

area : 목표물 크기 증가
chance : 2회 기회
damage : 점수획득 2배
big : 본인 포탄 크기 증가

3. 캐릭터 및 움직임 구현

   - [x] 3.1 캐릭터 디자인
   - [x] 3.2 캐릭터 고유 색상 및 특성 구현
   - [x] 3.3 캐릭터 움직임 구현
   - [ ] 3.4 캐릭터 고를 때 마우스 올리면 스킬 보여주기

4. 지형 구현

   - [ ] 4.1 지형 디자인
   - [ ] 4.2 지형 구현

5. Manual 적용해야 하는 부분

   - [ ] 5.1 manual_mode.html - battle mode (battle 모드의 개념)
   - [ ] 5.2 manual_mode.html - target mode (target 모드의 개념)
   - [ ] 5.3 select_tank(easy_battle).html (스킬 설명) - target mode랑 스킬 조금 다름
   - [ ] 5.4 select_tank(easy_target).html (스킬 설명) - battle mode랑 스킬 조금 다름
   - [ ] 5.5 select_tank(easy_battle).html (스킬 설명)
   - [ ] 5.6 select_tank(easy_battle).html (스킬 설명)

6. UX 및 버그 잡기
   - [ ] 5.1 유지보수
   - [ ] 5.2 ending 화면 진입 시 축하표현
