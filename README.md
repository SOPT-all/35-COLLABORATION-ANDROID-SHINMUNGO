# 🦺 안전 신문고 - Android 🦺
> 합동세미나 모바일 앱 8팀 안전신문고

## 👷 Contributors
| <img src="https://avatars.githubusercontent.com/u/101652649?v=4" width = "200"/> | <img src="https://avatars.githubusercontent.com/u/89915076?v=4" width = "200" /> | <img src="https://avatars.githubusercontent.com/u/63749140?v=4" width = "200"/> | <img src="https://avatars.githubusercontent.com/u/182846193?v=4" width = "200"/> | 
|:-------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
|                      [이석준](https://github.com/boiledEgg-s)                      |                        [김채린](https://github.com/chrin05)                        |                       [이황근](https://github.com/yihwanggeun)                        |                       [장재원](https://github.com/jangsjw)                        |
| `담당 기능` | `담당 기능` | `담당 기능` | `담당 기능` |

## 💻 Git Convention

1. **이슈/커밋 유형**
  ```
  [FEAT] : 새로운 기능 구현
  [MOD] : 코드 수정 및 내부 파일 수정
  [ADD] : 부수적인 코드 추가 및 라이브러리 추가, 새로운 파일 생성
  [CHORE] : 버전 코드 수정, 패키지 구조 변경, 타입 및 변수명 변경 등의 작은 작업
  [DEL] : 쓸모없는 코드나 파일 삭제
  [UI] : UI 작업
  [FIX] : 버그 및 오류 해결
  [HOTFIX] : issue나 QA에서 문의된 급한 버그 및 오류 해결
  [MERGE] : 다른 브랜치와의 MERGE
  [MOVE] : 프로젝트 내 파일이나 코드의 이동
  [RENAME] : 파일 이름 변경
  [REFACTOR] : 전면 수정
  [DOCS] : README나 WIKI 등의 문서 개정
  ```
2. **이슈 컨벤션**
  ```
  [유형] 작업 내용
  ```
3. **브랜치 컨벤션**
  ```
  유형/#이슈번호-작업내용
  ```
4. **PR 컨벤션**
  ```
  [유형/#이슈번호] 작업내용
  ```
5. **이슈 및 PR 템플릿**: [노션 페이지에서 확인]()

## 📦 Package Convention
```
📦com.sopt.shinmungo
├─📂app
|  ├─📂di
├─📂core
│  ├─📂designsystem
│  │  └─📂component
│  ├─📂util
├─📂data
|  ├─📂data class
│  ├─📂dto
│  │  └─📂response
│  │  └─📂request
│  ├─📂service
├─📂domain
│  ├─📂repository
│  ├─📂entity
├─📂feature
```

## 🖥️ Coding Convention
- **변수** : 명사, 카멜 케이스
- **함수** : 동사, 카멜 케이스
- **Composable 함수** : 의도+컴포넌트명 (ex. CircularIconButton)
- **리소스 파일** : 스네이크 케이스
  - 문자열: `[where]_[what]`
  - 아이콘: `ic_[where]_[what]_[size].xml`
 
## Tech Stack
| Title | Content |
| ------------ | -------------------------- |
| Architecture | MVVM |
| UI Framework  | Jetpack Compose  |
| Build Tools  | Gradle Version Catalog |
| Dependency Injection | Hilt  |
| Network | Retrofit2, OkHttp  |
| Asynchronous Processing | Coroutine, Flow |
| Third Party Library |   |
| Other Tools |   |\
