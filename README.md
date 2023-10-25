# Real World

## Convention

#### Commit

| Tag Name           | Description                                                                                   |
| ------------------ | --------------------------------------------------------------------------------------------- |
| `feat`             | 새로운 기능을 추가                                                                            |
| `fix`              | 버그 수정                                                                                     |
| `design`           | CSS 등 사용자 UI 디자인 변경                                                                  |
| `!BREAKING CHANGE` | 커다란 API 변경의 경우                                                                        |
| `!HOTFIX`          | 급하게 치명적인 버그를 고쳐야하는 경우                                                        |
| `style`            | 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우                                         |
| `refactor`         | 프로덕션 코드 리팩토링                                                                        |
| `comment`          | 필요한 주석 추가 및 변경                                                                      |
| `docs`             | 문서 수정                                                                                     |
| `test`             | 테스트 코드, 리펙토링 테스트 코드 추가, Production Code(실제로 사용하는 코드) 변경 없음       |
| `chore`            | 빌드 업무 수정, 패키지 매니저 수정, 패키지 관리자 구성 등 업데이트, Production Code 변경 없음 |
| `rename`           | 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우                                            |
| `remove`           | 파일을 삭제하는 작업만 수행한 경우                                                            |

#### Code Style

[에어비앤비 룰](https://github.com/airbnb/javascript)을 준수하여 코드를 작성합니다

#### File Structure

```bash
├── public
├── src
│   ├── pages
│   │   ├── main
│   │   ├── signin
│   │   ├── signup
│   │   ├── article
│   │   └── member
│   ├── components
│   │   ├── common
│   │   └── ${component}
│   ├── lib
│   ├── App.jsx
│   └── main.jsx
└── vite.config.js
```

## Library

`redux`
`emotion`
