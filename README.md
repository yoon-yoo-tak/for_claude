## CLAUDE 관련 찾기 귀찮아서 만드는 문서

---

### Official
근본은 클로드 공식문서를 보는것

- 클로드 공식문서 (https://code.claude.com/docs/en/overview)
- Anthropic 블로그 (https://www.anthropic.com/engineering)

### Plugins
일단 설치해야하는 plugin

- feature-dev ([official link](https://github.com/anthropics/claude-code/tree/main/plugins/feature-dev)) 
- serena  ([official link](https://github.com/oraios/serena))
- context7 ([official link](https://github.com/upstash/context7))
- lsp
  - lsp는 ~/.zshrc에 export ENABLE_LSP_TOOL=1 해줘야 lsp mcp server의 모든 기능 사용 가능
- Superpowers
  <details>
  <summary>Superpowers</summary>
  Superpowers: AI 에이전트가 코드부터 짜지 않게 만드는 개발 방법론
  github repo : https://github.com/obra/superpowers
  
  GitHub 스타 4.1만 개, Skill 생태계 사실상 1위예요. 단순한 코드 생성 보조가 아니라, 에이전트의 소프트웨어 개발 프로세스 자체를 바꿔놓는 프레임워크예요.
  
  • 설치하면 에이전트가 먼저 "뭘 만들려는 건지" 질문하고, 설계 문서를 작성한 뒤에야 코딩을 시작 
  • 브레인스토밍 → 계획 수립 → 테스트 주도 개발(TDD) → 코드 리뷰 → Git 워크트리 관리까지 7단계 워크플로우 내장 
  • 작업을 2~5분 단위로 쪼개서 독립된 하위 에이전트에 배분하고, 2단계 자동 리뷰까지 수행
  
  제가 직접 써보고 가장 놀랐던 건 Claude Code 가 정말 오랜 시간 자율적으로 작업하면서도 계획에서 벗어나지 않는다는 점이었어요.

  출처 : [이정민님 🛠 Claude Code Skill 10만 개 중 진짜 살아남은 4개, 주말 동안 살펴봤습니다](https://www.linkedin.com/posts/jyoung105_claude-code-skill-10%EB%A7%8C-%EA%B0%9C-%EC%A4%91-%EC%A7%84%EC%A7%9C-%EC%82%B4%EC%95%84%EB%82%A8%EC%9D%80-4%EA%B0%9C-share-7425792969234067456-GSoI?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFy3IrABSfxfQAnJS2Ic4psSSBTf3QXWZ4k)
  </details>


### DLC

- oh-my-opencode (https://github.com/code-yeongyu/oh-my-opencode)
- oh-my-claudecode (https://github.com/Yeachan-Heo/oh-my-claudecode)

### Prompt

- everything-claude-code (https://github.com/affaan-m/everything-claude-code)

### Youtube

- 코드팩토리(https://www.youtube.com/@codefactory_official)

### Linkedin

- 정구봉님 (https://www.linkedin.com/in/gb-jeong/)

### Article

- [Claude Code 고수들은 이렇게 쓴다](https://blog.huns.site/blog/posts/ai/claude/claude-code-power-user-tips)
- [Claude Skills 구축을 위한 완벽 가이드](https://claude.com/blog/complete-guide-to-building-skills-for-claude)
