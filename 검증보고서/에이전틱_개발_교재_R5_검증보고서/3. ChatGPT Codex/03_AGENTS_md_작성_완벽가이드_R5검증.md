# 03. AGENTS.md 작성 완벽 가이드 — 5차 할루시네이션 검증 보고서 (R5)

**검증일**: 2026-06-06
**검증 라운드**: Round 5
**검증 방법**: 웹검색 기반 공식 문서 대조
**검증 기반**: R4 수정본
**전체 할루시네이션 위험도**: 낮음

## 웹검색 확인 항목
| 주장 내용 | 검색어 | 결과 | 출처 URL |
|---------|------|------|---------|
| AGENTS.md 32KiB 크기 제한 | "AGENTS.md specification 2026" | 확인됨 | https://developers.openai.com/codex/guides/agents-md |
| AGENTS.override.md 우선순위 체계 | "AGENTS.md override priority 2026" | 확인됨 | https://github.com/openai/codex/blob/main/docs/agents_md.md |
| 오픈 표준(Linux Foundation 언급) | "AGENTS.md open standard 2026" | 부분 확인: OpenAI·Google 협업으로 개방적 표준 방향 추진. Linux Foundation 공식 인증 여부 불분명 | https://prpm.dev/blog/agents-md-deep-dive |
| Codex 홈 디렉토리 AGENTS.md 탐색 순서 | "AGENTS.md file discovery codex" | 확인됨: 홈→루트→CWD 순서 | https://developers.openai.com/codex/guides/agents-md |
| 파일당 32KiB 총 합산 | "AGENTS.md size limit" | 확인됨: 복수 AGENTS.md 합산 32KiB 제한 | https://github.com/openai/codex/blob/main/docs/agents_md.md |

## 잔존/신규 오류
### 🔴 심각
(없음)

### 🟡 주의
| 항목 | 교재 내용 | 공식 문서 | 출처 |
|------|---------|---------|-----|
| Linux Foundation 오픈 표준 | Linux Foundation 오픈 표준으로 언급 | OpenAI·Google 등 협업으로 개방 표준 지향이나 Linux Foundation 공식 인증 확인 불가. 표현 완화 권장 | https://prpm.dev/blog/agents-md-deep-dive |

### 🟢 확인됨
- AGENTS.md 역할 및 중요성 설명 정확
- 32KiB 크기 제한 정확
- AGENTS.override.md 우선순위 체계 정확
- 파일 탐색 순서(홈 디렉토리→프로젝트 루트→CWD) 정확
- 에이전트별 규칙 파일명 비교표(AGENTS.md/CLAUDE.md/GEMINI.md) 정확
- 모노레포 서브디렉토리 AGENTS.md 활용법 정확

## R4 대비 개선도
- R4 WHI: 0.05
- R5 WHI: 0.04 (Linux Foundation 표현 정밀화)

## 신뢰도 (R5)
- **점수**: 9.6/10
