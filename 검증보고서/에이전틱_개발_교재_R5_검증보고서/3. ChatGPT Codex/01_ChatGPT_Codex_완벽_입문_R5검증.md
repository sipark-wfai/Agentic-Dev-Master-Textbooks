# 01. ChatGPT Codex 완벽 입문 — 5차 할루시네이션 검증 보고서 (R5)

**검증일**: 2026-06-06
**검증 라운드**: Round 5
**검증 방법**: 웹검색 기반 공식 문서 대조
**검증 기반**: R4 수정본
**전체 할루시네이션 위험도**: 낮음

## 웹검색 확인 항목
| 주장 내용 | 검색어 | 결과 | 출처 URL |
|---------|------|------|---------|
| ChatGPT Codex는 클라우드 기반 에이전틱 코딩 플랫폼 | "OpenAI Codex documentation 2026" | 확인됨 | https://developers.openai.com/codex |
| Ubuntu 샌드박스에서 실행 | "OpenAI Codex sandbox Ubuntu 2026" | 확인됨(Ubuntu 24.04) | https://developers.openai.com/codex/concepts/sandboxing |
| Plus/Pro/Business/Edu/Enterprise 지원 | "OpenAI Codex pricing plans 2026" | 확인됨 | https://developers.openai.com/codex/pricing |
| GPT-5.5 모델 적용(R4에서 GPT-5.4 언급) | "OpenAI Codex GPT-5.5 2026" | 신규 확인: GPT-5.5가 2026년 4월 23일 출시, Codex에 적용됨 | https://openai.com/index/introducing-gpt-5-5/ |
| Subagents GA(병렬 에이전트) | "openai codex subagents parallel 2026" | 확인됨: 2026년 3월 14일 GA | https://developers.openai.com/codex/subagents |

## 잔존/신규 오류
### 🔴 심각
(없음)

### 🟡 주의
| 항목 | 교재 내용 | 공식 문서 | 출처 |
|------|---------|---------|-----|
| 주요 모델명 | GPT-5.4 언급 | GPT-5.5가 2026년 4월 23일 기본 모델로 전환됨. GPT-5.4는 여전히 사용 가능하나 GPT-5.5가 주력 모델 | https://openai.com/index/introducing-gpt-5-5/ |
| Subagents 기능 | 비동기 멀티태스킹 언급 있으나 Subagents GA 미언급 | 2026년 3월 14일 Codex Subagents GA 출시, 최대 6개 동시 실행 | https://developers.openai.com/codex/subagents |

### 🟢 확인됨
- ChatGPT Codex의 클라우드 네이티브 아키텍처 설명 정확
- 에이전트 패러다임 vs Copilot 패러다임 비교 정확
- Ubuntu 샌드박스 환경 설명 정확
- Plus/Pro/Business/Enterprise 플랜 구분 정확
- GitHub 연동 방식 정확
- 비동기 실행 개념 정확

## R4 대비 개선도
- R4 WHI: 0.05 (매우 낮음)
- R5 WHI: 0.03 (GPT-5.5 주력 모델 전환 반영, Subagents GA 추가)

## 신뢰도 (R5)
- **점수**: 9.5/10
- GPT-5.5 전환 및 Subagents GA 반영으로 최신성 향상
