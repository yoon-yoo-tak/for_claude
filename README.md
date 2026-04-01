## Claude 관련 정보 모음

> 클로드 코드 마스터 카톡방 + 개인 수집 자료 통합 정리

---

| 파일 | 내용 |
|------|------|
| [official.md](./official.md) | Anthropic 공식 문서, 블로그, 릴리즈 노트 |
| [plugins-and-skills.md](./plugins-and-skills.md) | 플러그인, 스킬, MCP 서버 |
| [tools-and-cli.md](./tools-and-cli.md) | AI 코딩 에이전트, CLI, 터미널 도구 |
| [dev-methodology.md](./dev-methodology.md) | SDD, 하네스 패턴, 개발 방법론 |
| [articles-and-cases.md](./articles-and-cases.md) | 기업 도입 사례, 아티클, 블로그 |
| [local-llm.md](./local-llm.md) | 로컬 LLM, 모델 비교, 경량화 |
| [design-and-ui.md](./design-and-ui.md) | AI 디자인/UI 도구 |
| [learning.md](./learning.md) | 학습 자료, 유튜브, 강의, SNS |
| [misc.md](./misc.md) | 브라우저 자동화, RAG, AI 서비스, 기타 |

---

### 빠른 팁

- **LSP**: `~/.zshrc`에 `export ENABLE_LSP_TOOL=1` 필요
- **Auto Mode**: `claude --enable-auto-mode` (위험 작업 시 한번 더 확인)
- **Voice Mode**: `/voice`로 활성화 (단계적 롤아웃)
- **Auto Dream**: 세션 메모리 자동 정리. `/memory`로 on/off 확인. 24시간 경과 + 5회 이상 세션 시 동작
- **show me**: 학습 시 유용한 Claude Code 명령어
- **npx skills add tw93/claude-health**: `/health`로 Claude Code 설정 리포트 출력
- **npx -y cc-alchemy-statusline**: 스테이터스라인 설정
