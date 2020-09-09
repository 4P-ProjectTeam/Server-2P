# 2P
**2인용**은 쉽고 간단한 게임을 온라인으로 친구와 즐길 수 있는 게임 웹페이지 입니다. 회원가입을 하여 게임을 즐기신 후 그 동안의 게임 전적을 확인 할 수도 있어요.

직접 친구와 얼굴을 맞대어 연필을 잡고, 혹은 동전을 가지고 오락실을 갔던 그 시절 그 재미보다 덜 할 수 있지만 짧은 시간에 친구와 함께 **2인용**을 통해 옛 추억에 대한 향수와 재미를 찾아보시길 바랍니다

게임은 계속해서 업데이트 됩니다 :)

# 2P-server

## start
```npm install```

```npm start```

## severs

### web_server
로그인, 회원가입, 마이페이지, 로그아웃과 같은 유저정보 관련 API와 대기방의 목록, 생성, 참가, 삭제와 같은 대기방 정보 관련 API들로 구성된 express서버입니다.

**포트번호:** 3001

### chat_server
대기방에서 진행되는 채팅에 관한 socket 서버입니다.

**포트번호:** 3002

### game_mole
두더지게임에 관한 socket 서버입니다.

**포트번호:** 3009

### bdman
구슬동자 게임에 관한 socket 서버입니다.

**포트번호:** 3005

### numsgame
숫자야구게임에 관한 socket 서버입니다.

**포트번호:** 3006
