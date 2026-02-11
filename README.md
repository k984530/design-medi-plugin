# design-medi-plugin

디자인메디 사내 디자이너를 위한 Claude Code 플러그인입니다. 디자인 워크플로우를 자동화하고 효율화합니다.

## 설치

```bash
# 1. 마켓플레이스 등록
claude plugin marketplace add k984530/design-medi-plugin

# 2. 플러그인 설치
claude plugin install design-medi-plugin@design-medi-marketplace
```

## 프로젝트 구조

```
design-medi-plugin/
├── .claude-plugin/
│   ├── plugin.json          # 플러그인 매니페스트
│   └── marketplace.json     # 마켓플레이스 배포 설정
├── commands/                # 슬래시 커맨드
├── agents/                  # 커스텀 에이전트
├── skills/                  # 스킬
├── hooks/                   # 이벤트 훅
├── .gitignore
├── LICENSE
└── README.md
```

## 기능 (예정)

- 디자인 시스템 관리
- 디자인 리뷰 자동화
- 컴포넌트 생성 지원

## 라이선스

MIT
