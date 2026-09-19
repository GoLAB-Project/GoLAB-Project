# GoLAB-Project

대화 기반 변론 게임. 이름은 GoLAB, 말장난으로 **고래**입니다. 지금은 **연습전 vs AI**만 플레이할 수 있습니다.

한 판은 약 3분입니다. 주제와 입장이 추첨되고, 오프닝·크로스·클로징 뒤에 심판이 승패를 가릅니다. 사람이 없어도 AI 상대와 AI 심판으로 바로 한 판이 끝납니다.

## 지금 되는 것

- 연습전 vs AI (페르소나: 검사 / 댓글러 / 교수)
- 제약 카드 (금기어, 필수어, 비유)
- 배심원 미터와 승패 판정
- GPT 키가 없으면 로컬 상대·심판으로 진행

## 저장소

| 저장소 | 역할 |
| --- | --- |
| [GoLAB-frontend](https://github.com/GoLAB-Project/GoLAB-frontend) | React 화면 |
| [GoLAB-backend](https://github.com/GoLAB-Project/GoLAB-backend) | Spring Boot API |
| 이 저장소 | 컨셉, 변경점, 라이브 커밋 기록 |

## 로컬 실행

1. 백엔드: `GoLAB-backend`에서 `./gradlew bootRun` (Windows는 `gradlew.bat bootRun`)
2. 프론트: `GoLAB-frontend`에서 `npm start`
3. 브라우저에서 `http://localhost:3000` → 연습전 시작

OpenAI를 쓰려면 백엔드 환경 변수 `CHATGPT_API_KEY`를 넣습니다. 없어도 연습전은 됩니다.

## 라이선스

Go-LAB &copy; [NoHack](mailto:brotherjun96@gmail.com)
