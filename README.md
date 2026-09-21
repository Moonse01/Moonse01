# 문석용 · Moonse01

### 사용자의 선택이 실제 결과로 이어지는 서비스를 만듭니다.

Java · Spring Boot로 API와 데이터 흐름을 구현하고, React 화면부터 외부 API 연동·배포까지 연결한 경험을 쌓고 있습니다.

---

## Featured project

### [triplan — 친구들이 함께 결정하는 여행 플래너](https://github.com/Moonse01/triplan)

**단톡방 대화 → AI A/B 일정 → 장소별 투표 → 최종 여행 일정**

2인 캡스톤 프로젝트에서 서비스 기획과 주요 개발·통합을 주도했습니다. AI가 만든 결과를 검증하고, 친구들의 선택이 최종 일정에 반영되는 흐름을 구현해 KT Cloud 배포·시연까지 진행했습니다.

| 집중한 문제 | 구현한 해결 방식 |
| :--- | :--- |
| 생성된 일정을 실제 장소와 연결하기 | 조건 파싱·A/B 생성 분리, 일정 규칙 검사, 카카오 장소 검증과 대체 처리 |
| 로그인 이동 중 투표 선택을 보존하기 | 브라우저 임시 저장, 로그인 복귀 후 제출, 사용자·장소별 재투표 갱신 |
| A/B 중 하나를 고르는 데서 더 나아가기 | 장소별 선호와 기존 장소 ID를 활용해 최종 일정 재구성 |

**[프로젝트 살펴보기 →](https://github.com/Moonse01/triplan)** · **[개인 기여와 의사결정 →](https://github.com/Moonse01/triplan/blob/main/docs/contribution.md)**

## Technologies used

| 분야 | 프로젝트에서 사용한 기술 |
| :--- | :--- |
| Backend | Java 17 · Spring Boot · Spring Data JPA · Spring Security · MySQL |
| Frontend | React · JavaScript · Tailwind CSS · Axios |
| Integration & deployment | OpenAI API · Kakao API · Web Push · Docker Compose · Nginx · KT Cloud |

## 개발에서 중요하게 생각하는 것

- 기능의 목표와 실제 출력이 일치하는지 사용자 흐름으로 확인합니다.
- 외부 API가 실패했을 때의 복구와 대체 경로를 함께 고민합니다.
- 구현한 기능, 직접 검증한 결과, 앞으로 개선할 부분을 구분해 기록합니다.
