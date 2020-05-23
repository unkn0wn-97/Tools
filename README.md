# Tools - V1.0.1 | 서버 설정 도우미, 입퇴장 알림, 플레이어 데이타 수집

## 다운로드
[Tools 다운로드](https://drive.google.com/file/d/1SxmwALzFfsKLzn8BAE_hk0qg9FOrvVO1/view?usp=sharing)

## 업데이트
* 1.0.1
    * 입장 시 국가 표시
    * 퇴장 시 퇴장 이유 표시
    (입장,퇴장 플레이어 이미지로 변경됨.)
    * 콘피그 콘솔 로그 추가됨.
    * 언어 변경됨.

## 미래 계획 -
* ~~접속 국가 체크~~
* 코드 최적화
* ~~왼쪽 이미지 플레이어 아이콘 또는 서버 지정~~
* 알림 시스템

## 콘피그(Config) -
```
oxide/config/Tools.json 에서 플러그인을 수정할수있습니다.
{
  "0. true - 활성화 / false - 비활성화": "이부분은 건들지마시오!",
  "0. 플러그인 칭호 설정": "<color=#00ffff>[ 알림 ] - </color>",
  "0. 콘솔 로그": true,
  "1. 서버 제목 설정 ON/OFF": false,
  "1. 서버 제목 설정": "서버 제목을 적어주세요.",
  "2. 서버 URL 설정 ON/OFF": false,
  "2. 서버 URL 설정 (URL 링크만)": "https://discord.gg/XUEHw7M",
  "3. 서버 설명 ON/OFF": false,
  "3. 서버 설명 (서버 설명할만한걸 적으면된다.)": "여기는 무슨서버이다~ 설명글!\n엉덩이 팡팡!",
  "4. 서버 이미지(로고) 설정 ON/OFF": false,
  "4. 서버 이미지(로고) 설정 (이미지링크)": "https://i.imgur.com/mHpQINh.png",
  "5. 서버 처음 접속 입장 알림 ON/OFF": false,
  "6. 서버 접속 입장 알림 ON/OFF": false,
  "7. 서버 퇴장 입장 알림 ON/OFF": false,
  "8. 서버 규칙 알림 ON/OFF": false
}
```
## 데이타(Data) -
```
oxide/data/Tools_PlayerData.json 에서 플레이어 데이터를 볼수있습니다.
  "76561198866308187": {
    "DisplayName": [
      "KR_WOLF",
      "[1234] KR_WOLF"
    ],
    "IP": [
      "127.0.0.1"
    ],
    "Dis_ConnectTime": [
      "처음 접속 | 04/27/2020 18:39:30 | 127.0.0.1 | KR_WOLF | 76561198866308187",
      "퇴장 | 04/27/2020 23:07:05",
      "접속 | 04/27/2020 23:07:50",
      "퇴장 | 04/27/2020 23:21:44",
      "접속 | 04/27/2020 23:22:08",
      "퇴장 | 04/27/2020 23:55:37",
      "접속 | 04/28/2020 19:07:50",
      "퇴장 | 04/28/2020 20:15:23",
      "접속 | 04/28/2020 20:15:58",
      "퇴장 | 04/28/2020 21:45:41",
      "접속 | 04/29/2020 22:29:59",
      "퇴장 | 04/29/2020 22:47:57",
      "접속 | 04/29/2020 23:05:40",
      "퇴장 | 04/29/2020 23:24:09",
      "접속 | 04/30/2020 00:37:50",
      "퇴장 | 04/30/2020 02:09:25",
      "접속 | 04/30/2020 02:09:47",
      "퇴장 | 04/30/2020 02:46:24",
      "접속 | 04/30/2020 02:46:47",
      "퇴장 | 04/30/2020 02:55:33"
    ],
    "PlayerID": "76561198866308187",
    "ConnectCount": 9
  },
```
## 언어(Lang) -
```
oxide/lang/en/Tools.json 에서 플러그인 언어을 수정할수있습니다.
{
  "처음입장": "{0}님이 서버에 처음 접속하셨습니다. [국가: {1}]",
  "입장": "{0} 님이 서버에 접속하셨습니다. [국가: {1}]",
  "입장알수없음": "{0}님이 서버에 접속하셨습니다. [국가: 알수없음]",
  "퇴장": "{0} 님이 서버에서 퇴장하셨습니다. [이유: {1}]",
  "권한": "<color=red>당신은 권한이 없습니다.</color>",
  "규칙": "{0}님 서버에 접속하셨습니다. 규칙 읽어주세요.\n1. 핵 사용 금지\n2. 욕설/비하 금지\n3. 서로 존중하기"
}
```
