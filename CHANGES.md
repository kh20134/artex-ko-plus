# 이 포크의 변경

저장소: [kh20134/artex-ko-plus](https://github.com/kh20134/artex-ko-plus)

상위: [bdg9412/artex-ko-plus](https://github.com/bdg9412/artex-ko-plus) (AGPL-3.0)

원본 프로그램: [Autumn-27/ARTEX](https://github.com/Autumn-27/ARTEX)

한국어 현지화로 코드와 문서가 가리키는 저장소: [jiwoochris/artex-ko](https://github.com/jiwoochris/artex-ko)

검증 방법과 각 층의 범위는 [NOTICE](NOTICE)와 [README.md](README.md)의 「출처 및 라이선스」에 적혀 있음.

## 2026-10-11 · 문서만 보강

프로그램 동작은 바꾸지 않음. Go·웹·스키마·API·설정 해석·에이전트 프롬프트는 상위 커밋 `8873bb0e88cd5138bf49ea654191c7ce30998778` 과 같음.

- README 상단에 「출처 및 라이선스」와 개조식 운영 설명을 추가함.
- 상위 체인, 각 층에서 확인한 추가분, AGPL-3.0 의무, 이 포크의 변경 목록을 적음.
- 기존 LICENSE, README 본문, 중국어·영어 문서, 소스 안의 저작권·출처 표기를 유지함.
- NOTICE 를 추가함.
- 구성과 신뢰 경계를 `docs/architecture.svg` 로 그리고, Noto Sans CJK KR 로 렌더한 `docs/architecture.png` 를 README 에 넣음.
- 실대상·API 키 없이 `go test ./closedloop/ ./defenseeval/ ./investigation/` 를 실행한 터미널 화면을 `docs/images/offline-package-tests.png` 로 남김. Docker 엔진이 이 환경에 없어 웹 서버 기동 화면은 만들지 않음.

상위 저장소가 더한 기능 이력은 [CHANGELOG.md](CHANGELOG.md)와 [RELEASE_NOTES.md](RELEASE_NOTES.md)에 그대로 있음.
