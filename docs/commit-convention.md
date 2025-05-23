### 📌 Commit Message Convention

커밋 메시지는 다음 형식을 따릅니다:

```
<타입>: [카테고리] 작업내용 요약
```

#### ✅ 예시
```
Add: [Docs] 프로젝트 계획서 추가
Fix: [Course] 추천 경로 null 예외 처리
Update: [UI] 버튼 스타일 수정
Delete: [Auth] 사용하지 않는 토큰 유틸 제거
Refactor: [Map] 경로 처리 로직 리팩토링
```

---

### ✏️ 타입 (Type)

| 타입       | 설명                                                  |
|------------|-------------------------------------------------------|
| `Add`      | 새 기능, 파일, 모듈을 추가할 때                      |
| `Update`   | 기존 코드에 기능 추가 또는 설정 변경 시              |
| `Fix`      | 버그 수정                                             |
| `Modify`   | 코드 기능 일부 수정 (버그가 아닌 일반 수정)         |
| `Delete`   | 코드, 파일, 모듈 삭제 시                              |
| `Refactor` | 리팩토링 (동작은 그대로, 코드 구조 개선)             |
| `Docs`     | 문서 수정 (README, 계획서 등)                         |
| `Test`     | 테스트 코드 추가 또는 수정                            |
| `Chore`    | 빌드, 패키지, 설정 파일 등 기타 변경사항             |

---

### 🗂 카테고리 (Category)

- `Docs`: 문서 관련
- `Auth`: 로그인, 회원가입, 인증 관련
- `Course`: 러닝 코스 관련
- `Crew`: 크루 기능 관련
- `Community`: 커뮤니티 기능
- `Record`: 러닝 기록 관련
- `Notification`: 알림 관련
- `Map`: 지도, 위치 관련
- `Config`: 설정, 환경설정 관련
- `UI`: 프론트 UI 관련
- `Common`: 공통 유틸, 인터셉터 등

---

### 💡 팁
- 메시지는 **명확하고 간결하게** 작성합니다.
- 여러 변경이 있을 경우 **여러 커밋**으로 나누는 것이 좋습니다.
- PR 제목과도 일관성을 유지하세요.
