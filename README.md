## Claude 관련 정보 모음

> 클로드 코드 마스터 카톡방 + 개인 수집 자료 통합 정리

---

### 빠른 팁

- **LSP**: `~/.zshrc`에 `export ENABLE_LSP_TOOL=1` 필요
- **Auto Mode**: `claude --enable-auto-mode` (위험 작업 시 한번 더 확인)
- **Voice Mode**: `/voice`로 활성화 (단계적 롤아웃)
- **Auto Dream**: 세션 메모리 자동 정리. `/memory`로 on/off 확인. 24시간 경과 + 5회 이상 세션 시 동작
- **show me**: 학습 시 유용한 Claude Code 명령어
- **npx skills add tw93/claude-health**: `/health`로 Claude Code 설정 리포트 출력
- **npx -y cc-alchemy-statusline**: 스테이터스라인 설정

---

### [Anthropic / Claude Code 공식](./official.md)

**핵심 링크**
- [Claude Code 공식 문서](https://code.claude.com/docs/en/overview)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)
- [Anthropic 엔지니어링 블로그](https://www.anthropic.com/engineering)

**문서 · 기능별**

| 링크 | 설명 |
|------|------|
| [Agent Teams (한국어)](https://code.claude.com/docs/ko/agent-teams) | 에이전트 팀 기능 |
| [Scheduled Tasks](https://code.claude.com/docs/en/scheduled-tasks) | 스케줄링 기능 |
| [Code Review 블로그](https://claude.com/blog/code-review) | 코드 리뷰 기능 |
| [/btw 퀵 질문](https://code.claude.com/docs/en/interactive-mode#side-questions-with-btw) | 사이드 퀵 질문 |
| [데스크탑 앱 퀵스타트](https://code.claude.com/docs/en/desktop-quickstart) | 데스크탑 앱 설치 |
| [채널 기능](https://code.claude.com/docs/en/channels) | 텔레그램/디스코드 연결 |
| [공식 플러그인](https://github.com/anthropics/claude-plugins-official) | Anthropic 공식 플러그인 |
| [하네스 설계 원칙](https://www.anthropic.com/engineering/harness-design-long-running-apps) | 장기 실행 앱 설계 |

**파트너 · 투자**

| 링크 | 설명 |
|------|------|
| [Claude 파트너 프로그램](https://claude.com/partners) | 파트너 신청 |
| [Anthropic 1억 달러 투자](https://www.linkedin.com/posts/claude_anthropic-invests-100-million-into-the-claude-activity-7437981037143486464-naBR/) | 파트너 무료 제공 |

---

### [플러그인 · 스킬 · MCP 서버](./plugins-and-skills.md)

**내가 쓰는 플러그인**
- **feature-dev** — 기능 개발 가이드
- **serena** ([GitHub](https://github.com/oraios/serena)) — 코드 심볼 기반 토큰 절약 LSP
- **context7** — 라이브러리 문서 자동 참조
- **lsp** — LSP 연동 (`~/.zshrc`에 `export ENABLE_LSP_TOOL=1` 필요)

**스킬 · 플러그인 모음**

| 링크 | 설명 |
|------|------|
| [Claude Natives 팀 어셈블](https://github.com/team-attention/plugins-for-claude-natives/tree/main/plugins%2Fteam-assemble) | 팀 어셈블 플러그인 |
| [cclsp](https://github.com/ktnyt/cclsp) | Claude Code LSP 연동 |
| [Oh My Claude Code](https://github.com/Yeachan-Heo/oh-my-claudecode) | Claude Code 확장 도구 |
| [Everything Claude Code](https://github.com/affaan-m/everything-claude-code) | 종합 가이드 |
| [Excalidraw 다이어그램 스킬](https://github.com/coleam00/excalidraw-diagram-skill) | 다이어그램 생성 |
| [Baoyu Skills](https://github.com/JimLiu/baoyu-skills) | 스킬 모음 |
| [Taste Skill](https://github.com/Leonxlnx/taste-skill) | AI 티 덜 내는 프론트 디자인 |
| [zclean](https://github.com/whynowlab/zclean) | 에이전트 세션 정리 |
| [UI/UX Pro Max Skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | UX 점검 |
| [cmux 옵저버 스킬](https://github.com/meengi07/cmux-agent-observer-skill) | 멀티 에이전트 옵저버 |
| [ClipWise](https://github.com/kwakseongjae/clipwise) | 동영상 제작 |
| [Context Hub](https://github.com/andrewyng/context-hub) | 최신 데이터 가져오기 |
| [Auto Research Skill](https://github.com/olelehmann100kMRR/autoresearch-skill) | 자동 리서치 |
| [Plannotator](https://github.com/backnotprop/plannotator) | plan 모드 완성 후 HTML 피드백 |
| [Everything Claude Code (한국어)](https://github.com/affaan-m/everything-claude-code/blob/main/docs/ko-KR/README.md) | 한국어 문서 |
| [Claude Code Best Practice](https://github.com/shanraisshan/claude-code-best-practice) | 베스트 프랙티스 |
| [Awesome Codex Subagents](https://github.com/VoltAgent/awesome-codex-subagents) | 서브에이전트 적용 가이드 |
| [CC-SDD](https://github.com/gotalab/cc-sdd) | SDD 도구 |
| [NotebookLM MCP](https://github.com/PleasePrompto/notebooklm-mcp) | 리서치/문서생성 토큰 절약 |
| [SuperMemory](https://github.com/supermemoryai/supermemory) | AI 메모리 플러그인/MCP |

**DLC (확장 도구)**

| 링크 | 설명 |
|------|------|
| [oh-my-opencode](https://github.com/code-yeongyu/oh-my-opencode) | OpenCode 확장 |
| [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | Claude Code 확장 |

**MCP 서버**

| 링크 | 설명 |
|------|------|
| [Financial Datasets MCP](https://docs.financialdatasets.ai/mcp-server) | 미장 금융 데이터 |
| [한국 주식 MCP](https://github.com/jjlabsio/korea-stock-mcp) | 한국 주식 데이터 |

---

### [AI 코딩 에이전트 · CLI · 터미널 도구](./tools-and-cli.md)

**AI 코딩 에이전트**

| 링크 | 설명 |
|------|------|
| [OmO (Sisyphus)](https://x.com/koylanai/status/2025286163641118915) | 작업 분할 에이전트. Claude/Codex/Gemini 등 모델 교체 가능 |
| [RCLI](https://github.com/RunanywhereAI/RCLI) | 로컬 AI CLI 도구 |
| [Superset](https://superset.sh/) | 워크트리 분리 병렬 실행 |
| [OpenJarvis](https://github.com/open-jarvis/OpenJarvis) | 로컬 AI 에이전트 |
| [cmux](https://www.cmux.dev/ko) | AI 코딩용 터미널 (한국어) |
| [OpenCode AI](https://opencode.ai/docs/ko/go/) | OpenCode AI 문서 |
| [Mistral AI CLI](https://mistral.ai/) | Mistral CLI 도구 |

**OpenAI / Codex**

| 링크 | 설명 |
|------|------|
| [Symphony](https://github.com/openai/symphony) | OpenAI Symphony |
| [Codex 서브에이전트](https://developers.openai.com/codex/subagents/) | 서브에이전트 도입 |
| [하네스 엔지니어링 사례](https://openai.com/ko-KR/index/harness-engineering/) | OpenAI 하네스 사례 |

**터미널 도구**

| 링크 | 설명 |
|------|------|
| [iTerm Notification](https://github.com/wonjun3991/iterm-notification) | 터미널 알림 |
| [Octo Terminal](https://github.com/johunsang/octo-terminal-releases) | 올인원 에디터/터미널 |
| [Kaku](https://github.com/tw93/Kaku) | AI용 터미널 (lazygit/yazi 내장) |
| [LazyGit](https://github.com/jesseduffield/lazygit) | 터미널 Git UI |
| [Yazi](https://github.com/sxyazi/yazi) | 터미널 파일 매니저 |
| [Mole](https://github.com/tw93/Mole) | 맥 클린징 도구 |
| [tmux 가이드](https://www.wevesolutions.co.kr/blog/tmux-guide) | `.tmux.conf` 설정 필수 |

**유용한 CLI**

| 링크 | 설명 |
|------|------|
| [토스증권 CLI](https://github.com/JungHoonGhae/tossinvest-cli) | 토스증권 |
| [오픈카카오 CLI](https://github.com/JungHoonGhae/openkakao) | 오픈카카오톡 |

---

### [개발 방법론 · SDD · 하네스 패턴](./dev-methodology.md)

**SDD (Spec Driven Development)**

spec-kit으로 스펙 정의 → 에이전트가 clarify/analyze 반복 → 개발. TDD와 함께 사용하면 가장 높은 퀄리티.

| 링크 | 설명 |
|------|------|
| [GitHub Spec Kit](https://github.com/github/spec-kit) | GitHub 공식 SDD 도구 |
| [CC-SDD](https://github.com/gotalab/cc-sdd) | Claude Code용 SDD 도구 |
| [스펙으로 프로그래밍하는 언어](https://news.hada.io/topic?id=27476) | 관련 기사 |

**하네스 패턴**

에이전트 md 파일을 목차로 활용하는 개발 방식. 주류 방법론이 될 전망.

| 링크 | 설명 |
|------|------|
| [하네스 설계의 원칙](https://www.anthropic.com/engineering/harness-design-long-running-apps) | Anthropic 공식 (장기 실행 앱) |
| [토스 하네스](https://toss.tech/article/harness-for-team-productivity) | 토스 팀 생산성 사례 |
| [OpenAI 하네스](https://openai.com/ko-KR/index/harness-engineering/) | OpenAI 사례 |

---

### [기업 도입 사례 · 아티클](./articles-and-cases.md)

**기업 AI 코딩 도입 사례**

| 링크 | 설명 |
|------|------|
| [토스 - AI 하네스 팀 생산성](https://toss.tech/article/harness-for-team-productivity) | 한국어 |
| [토스 - 영문 버전](https://toss.tech/article/harness-for-team-productivity-eng) | 영문 |
| [카카오페이 - Agentic Coding](https://tech.kakaopay.com/post/ifkakao-agentic-coding/) | if(kakao) 발표 |
| [마이리얼트립 - 1년간의 AI 코딩 여정](https://medium.com/myrealtrip-product/1%EB%85%84%EA%B0%84%EC%9D%98-ai-%EC%BD%94%EB%94%A9-%EC%97%AC%EC%A0%95-30a9d2a1d3f3) | Medium |

**아티클 · 블로그**

| 링크 | 설명 |
|------|------|
| [Claude Code 고수들은 이렇게 쓴다](https://blog.huns.site/blog/posts/ai/claude/claude-code-power-user-tips) | 파워 유저 팁 |
| [Claude Skills 구축 완벽 가이드](https://claude.com/blog/complete-guide-to-building-skills-for-claude) | 공식 블로그 |
| [Claude Code Skills/Subagents 멘탈 모델](https://levelup.gitconnected.com/a-mental-model-for-claude-code-skills-subagents-and-plugins-3dea9924bf05) | 구조 이해 |
| [Cursor Composer 2](https://cursor.com/ko/blog/composer-2) | 강화학습 적용 |
| [AI 시대 개발자 고민](https://brunch.co.kr/@hiclemi/146) | 에세이 |

**팔로우할 사람**

| 플랫폼 | 링크 | 설명 |
|--------|------|------|
| LinkedIn | [정구봉님](https://www.linkedin.com/in/gb-jeong/) | AI/Claude 관련 인사이트 |

---

### [로컬 LLM · 모델 비교 · 경량화](./local-llm.md)

**맥미니 64GB 추천 모델**
- **Qwen 3.5 35B** — 소형 모델 중 강세
- **DeepSeek 32B Q4**
- **GPT-OSS 20B**

**도구 · 플랫폼**

| 링크 | 설명 |
|------|------|
| [ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw) | 로컬 AI 에이전트 |
| [MetalRT](https://www.runanywhere.ai/blog/metalrt-fastest-llm-decode-engine-apple-silicon) | 애플 실리콘 최적 LLM 디코드 엔진 |
| [LLMfit](https://github.com/AlexsJones/llmfit) | 로컬 머신에 적합한 모델 추천 |
| [Unsloth Studio](https://unsloth.ai/docs/new/studio) | PyTorch/GPU UI 스튜디오 |
| [NVIDIA NIM 프리뷰](https://build.nvidia.com/models?filters=nimType%3Anim_type_preview) | 모델 빌드 |

**모델 비교 · 기법**

| 링크 | 설명 |
|------|------|
| [오픈소스 소형 모델 비교](https://artificialanalysis.ai/models/open-source/small) | Qwen 3.5 강세 |
| [Qwen 3.5 35B 맥미니 테스트](http://youtube.com/post/UgkxJ1eoKOsw3tY8rBXVSNrUkGmeug42vODY?si=AHrrTl-vaW091H0O) | 64GB 영상 |
| [TurboQuant](https://research.google/blog/turboquant-redefining-ai-efficiency-with-extreme-compression/) | Google AI 극한 압축 |
| [SLM 방향 유도 기법](https://www.youtube.com/watch?v=w_mBRmx7vf0) | 작은 모델 유도 |

---

### [AI 디자인 · UI 도구](./design-and-ui.md)

| 링크 | 설명 |
|------|------|
| [Pencil](https://www.pencil.dev/) | MCP 연동 UI 수정 도구 (무료) |
| [AIverse Design Canvas](https://www.aiverse.design/insights/design-canvas) | 오픈소스 디자인 도구 |
| [Codespeak](https://codespeak.dev/) | Spec → 프로그래밍 언어 변환 |
| [Component Gallery](https://component.gallery/) | UI 컴포넌트 갤러리 |
| [Google Stitch](https://stitch.withgoogle.com/) | Google 디자인 도구 |
| [Stitch 활용기](https://news.hada.io/topic?id=27635) | 앱 디자인에 실제 사용 중 |

---

### [학습 자료 · 유튜브 · 강의](./learning.md)

**유튜브**

| 링크 | 설명 |
|------|------|
| [코드팩토리](https://www.youtube.com/@codefactory_official) | 개발 강의 채널 |
| [AI 관련 영상](https://youtu.be/qEF-eUaTq0Y?si=4gCNERgMAznmoLfQ) | 정윤성 공유 |
| [AI 관련 영상](https://youtu.be/f9mjOnznkNA?si=0DjiKox6r077HHVC) | 정윤성 공유 |
| [비주얼라이제이션](https://youtu.be/RtX3dYj3JoM?si=jheCGWjkcJjFHhfn) | 시각화 관련 |

**개발 일반 · 학습**

| 링크 | 설명 |
|------|------|
| [망나니개발자 블로그](https://mangkyu.tistory.com/463) | 개발 블로그 |
| [Diagrams](https://diagrams.mingrammer.com/) | Python 인프라 다이어그램 라이브러리 |
| [RealWorld Docs](https://realworld-docs.netlify.app/introduction/) | 에이전트 팀 실습용 |
| ["AI도 객체지향처럼 써야한다"](https://velog.io/@teo/we-programmer) | 개발 관점 |
| [요즘IT 매거진](https://yozm.wishket.com/magazine/detail/3650/) | 개발 효율 |
| [Claude Architect 노션](https://subdued-web-725.notion.site/Claude-Architect-3237248738e88070b3d1ec5352b45f64) | 자격증/가이드 |
| [Missing Semester (한국어)](https://missing-semester-kr.github.io/) | CLI 환경 학습 |
| [디자인 패턴 의사결정 트리](https://medium.com/womenintechnology/stop-memorizing-design-patterns-use-this-decision-tree-instead-e84f22fca9fa) | 패턴 선택 가이드 |

**AI 튜터**

| 링크 | 설명 |
|------|------|
| [Tutor Skills](https://github.com/RoundTable02/tutor-skills) | AI 학습/퀴즈 생성 |

---

### [기타 도구 · 서비스](./misc.md)

**브라우저 자동화 · 크롤링**

| 링크 | 설명 |
|------|------|
| [Vercel Agent Browser](https://github.com/vercel-labs/agent-browser) | Playwright 대비 토큰 90% 절감 |
| [Agent Browser 스킬 문서](https://github.com/vercel-labs/agent-browser/blob/main/skills/agent-browser/SKILL.md) | 스킬 상세 |
| [Claude Code 스킬로 크롤링하기](https://www.threads.com/@unclejobs.ai/post/DVxN2A8iTE3) | 활용법 |

**RAG · 데이터 · PDF**

| 링크 | 설명 |
|------|------|
| [OpenRAG](https://github.com/langflow-ai/openrag) | RAG 묶음 도구 |
| [OpenDataLoader PDF](https://github.com/opendataloader-project/opendataloader-pdf) | PDF 파서 |

**AI 예측 · 분석**

| 링크 | 설명 |
|------|------|
| [MiroFish](https://github.com/666ghj/MiroFish/blob/main/README-EN.md) | 다중 AI 예측 엔진 (60억 펀딩) |
| [MiroFish 한글화 테스트](https://www.threads.com/@uppinote20/post/DV94pphgcte/) | 코인 선물봇 활용 |

**AI 서비스 · 플랫폼**

| 링크 | 설명 |
|------|------|
| [Pi AI](https://pi.ai/redirect) | 개인화 AI |
| [Infratice](https://infratice.co.kr/) | AI 프롬프트 복사/사용 서비스 |
| [Okara AI CMO](https://okara.ai/agent/cmo) | 마케팅 AI 에이전트 |
| [Tiptap](https://tiptap.dev/pricing) | 웹 에디터 (Git 35K, 클라우드) |
| [Simplite](https://simplite.net) | 홈서버 구축 솔루션 |

**AI 인프라 · 개인 AI**

| 링크 | 설명 |
|------|------|
| [Personal AI Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure) | 스타 1만 코앞 |
| [ReMe (AgentScope)](https://github.com/agentscope-ai/ReMe) | AgentScope AI |

**앱 개발 · 배포**

| 링크 | 설명 |
|------|------|
| [App Store Screenshots](https://github.com/ParthJadhav/app-store-screenshots) | 스크린샷 자동 생성 |
| [Blitz Mac](https://github.com/blitzdotdev/blitz-mac) | 앱 스토어 출시 자동화 |
| [Remotion](https://github.com/remotion-dev/remotion) | React 기반 영상 제작 |
| [VibeShell](https://www.wevesolutions.co.kr/products/vibeshell) | 안드로이드 SSH 바이브코딩 |

**보안**

| 링크 | 설명 |
|------|------|
| [Terraform 보안 도구 털림](https://m.boannews.com/html/detail.html?tab_type=1&idx=142760) | 보안뉴스 |

**기타**

| 링크 | 설명 |
|------|------|
| [React Grab](https://github.com/aidenybai/react-grab/blob/main/README.md) | React 도구 |
| [오라클 클라우드 인스턴스](https://m.clien.net/service/board/cm_nas/17168505) | 클리앙 |
| [Claude Cowork 논코딩 활용](https://www.reddit.com/r/ClaudeAI/comments/1rubfbx/what_i_actually_use_cowork_for_heavy_noncoding/) | Reddit |
