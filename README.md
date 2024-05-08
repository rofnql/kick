# Kick 채팅 봇


# 설치

1. 저장소 복제하기
```bash
git clone https://github.com/rofnql/kick-marble.git
```

2. 필요한 node.js 라이브러리 설치하기
```bash
npm install
```
3. ``settings.json.example`` 파일의 이름을 ``settings.json``으로 변경한 후, Kick 채널 ID를 입력하세요.

4. 시작하기
* 명령어 받는 봇 시작하기
```bash
node ./chatbot/index.js
```
* 신청곡 받는 서버 시작하기
```bash
node ./server/index.js
```

# 명령어 
``!sr 유튜브링크`` : 곡 신청 합니다. 한 사람당 최대 3개만 가능<br>
``!play`` : 게임 참여<br>
``!stop`` : 게임 참가자를 그만 받습니다. (스트리머 전용)<br>
``!reset`` : 참가자 초기화하고 다시 참가자를 받습니다. (스트리머 전용)<br>

# 영도 사용법
### 사용을 원하지 않는다면 신청곡 받는 서버 시작 안하면 됩니다.
1. obs 브라우저 소스에 http://localhost:29523 추가 해상도 적절하게 1280 720 이상
2. http://localhost:29523/control 에서 현재 재생중인거 스킵 가능

# 구슬치기 사용법
1. 설정 버튼을 클릭합니다.<br>
<img src="https://github.com/theboocchirock/Kickbot/blob/main/marble1.png?raw=true">

2. "Use Custom Names" 옵션을 체크한 후, "Add Names"를 클릭합니다.<br>
<img src="https://github.com/theboocchirock/Kickbot/blob/main/marble2.png?raw=true">

3. "Open"을 클릭하고 marble.csv 파일을 불러옵니다.<br>
<img src="https://github.com/theboocchirock/Kickbot/blob/main/marble3.png?raw=true">

4. 원하는 맵을 선택하고, Race Type은 Bot을 선택합니다. Max Racer는 Name Count와 동일하게 설정하고, "Play"를 클릭합니다.<br>
<img src="https://github.com/theboocchirock/Kickbot/blob/main/marble4.png?raw=true">

5. 즐겜

# 주의
* VPN을 사용하면 차단될 가능성이 높습니다.
  *  터널링을 사용해 node 명령를 실행하는 프로그램(cmd)은 vpn에서 예외처리 하는게 바랍직합니다<br>
* Kick 사이트를 2개 이상 동시에 열어두면 차단될 가능성이 높습니다.

# 라이센스
MIT 라이센스입니다 (이거로 하라고 배움)
