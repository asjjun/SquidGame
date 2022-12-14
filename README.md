# SquidGame

<p align="center">
<img width="500px" src="https://user-images.githubusercontent.com/29851772/209011490-05bb86ec-b1d3-4d11-8952-e4679aba01b5.png">
<br>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/>
</p>


## 프로젝트 소개
 > Netflix '오징어게임'이 나왔을 당시 게임으로 구현해보고자 시작한 프로젝트                           
 > 책 "C언어로 쉽게 풀어쓴 자료구조"를 공부하며 여러 자료구조를 활용하여 만들어본 간단한 게임
 
## 환경 설정
     코드 상으로 pthread를 사용하는데 윈도우 환경에서도 pthread를 사용하고 싶다면 파일 다운로드 필요
     아래 사진과 같이 (C:\)경로에 다운받은 pthread 파일 넣기
     
     게임 실행 방법 - squidgame 파일 다운로드 후 sample.sln 열어서 실행
     
   <img width="450px" src="https://user-images.githubusercontent.com/29851772/199258011-919c859f-bca3-4544-8937-8d62c6eb17fa.png">
   
## 플레이 영상

<p align="center">
<<<<<<<<<< 그대로 재생하면 영상이 작아서 잘 안보이니 전체화면으로 보는걸 추천 >>>>>>>>>>
<br>
</p>

https://user-images.githubusercontent.com/29851772/209004869-fe730052-d0da-49ed-a13f-46bcffd958c3.mp4

- 게임이 시작되면 게임의 안내가 나오고 첫번째 게임 '무궁화 꽃이 피었습니다' 시작             
- 영희가 뒤돌아있을때만 움직이며 도착선 까지 도달하면 생존하며 다음 스테이지로 넘어감
  - 초록색 원: 주인공 (플레이어가 직접 움직임)
  - 하늘색 원: 다른 참가자들 (영희가 관계없이 랜덤으로 움직임, 따라서 도착지점에 도달하는것이 거의 불가능)
  - 자주색 원: 게임주최측 요원들 (게임 컨셉상 넣어봄)
  - 빨간색 세모: 총알 (영희가 돌아봤을때 움직이면 빨간 세모모양의 총알이 발사되고 닿으면 죽음)
<br>

https://user-images.githubusercontent.com/29851772/209017346-3309d85e-cb6c-4772-b252-4269443e73a1.mp4

- 주인공인 플레이어가 영희가 앞을 볼 때 움직여 총에 맞았다면 게임오버
<br>

https://user-images.githubusercontent.com/29851772/209004886-794973ac-2d24-4983-8ee1-7e8219e6c70f.mp4

- 첫번째 게임에서 생존하고 넘어왔다면 두번째 게임 '줄다리기' 시작
- 타자연습 게임에 자주 나오는 단어 타이핑 게임
- 일정 시간마다 상대방 쪽으로 줄이 당겨지고 열심히 단어를 타이핑 해 내 쪽으로 줄을 많이 당기면 승리
- 양쪽의 ◆가 기준이고 ■는 중심 점
<br>

https://user-images.githubusercontent.com/29851772/209010265-062ea2e7-0a07-4975-a3a2-1986af9a8603.mp4

- 세번째 게임은 '유리 징검다리 건너기' 게임
- 남은 참가자수: 20 이라는 부분이 있는데 게임 플레이어의 도전 횟수와 같음
- 영상에선 수월하게 건너가기 위해 '죽'이라는 단어로 떨어지는곳을 표시 (실제로는 모두 □)
<br>

https://user-images.githubusercontent.com/29851772/209010281-769f5da6-cf51-4878-805b-f4b9a4bf391d.mp4
- 마지막 게임은 '오징어 게임'
- Netflix에선 최종 2인이 결투를 하는데 플레이어와 컴퓨터가 대결하는것으로 구현
- 임의로 정해진 숫자 목록에 해당하는 숫자를 맞추면 오징어에게 피해를 줄 수 있고 한번 입력한 숫자는 중복 입력 불가
- 오징어의 체력을 0으로 만들게되는 마지막 공격을 한 플레이어가 승리(사실상 운 게임) 
- 영상에선 정답 숫자를 처음에 아래쪽에 띄워줘서 답지로 사용 






















