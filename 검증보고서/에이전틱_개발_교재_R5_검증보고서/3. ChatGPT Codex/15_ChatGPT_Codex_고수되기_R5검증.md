# 15. ChatGPT Codex 고수되기 — 5차 할루시네이션 검증 보고서 (R5)

**검증일**: 2026-06-06
**검증 라운드**: Round 5
**검증 방법**: 웹검색 기반 공식 문서 대조
**검증 기반**: R4 수정본
**전체 할루시네이션 위험도**: 낮음

## 웹검색 확인 항목
| 주장 내용 | 검색어 | 결과 | 출처 URL |
|---------|------|------|---------|
| 토큰 기반 과금 전환(2026년 4월) | "openai codex token billing April 2026" | 확인됨: 2026년 4월 2일 전환 | https://help.openai.com/en/articles/20001106-codex-rate-card |
| Pro $100 중간 티어 신설 | "openai codex pro $100 plan 2026" | 확인됨: Pro 5x $100/월(2026년 4월 9일 신설) | https://developers.openai.com/codex/pricing |
| GPT-5.5 업그레이드 | "openai codex GPT-5.5 2026" | 확인됨: GPT-5.5 2026년 4월 23일 출시, Codex 기본 모델 전환 | https://openai.com/index/introducing-gpt-5-5/ |
| codex profiles 명령 | "codex profiles command 2026" | 확인됨 | https://developers.openai.com/codex/changelog |
| codex history search 명령 | "codex history search 2026" | 확인됨 | https://developers.openai.com/codex/changelog |
| Subagents GA(2026년 3월 14일) | "openai codex subagents 2026" | 확인됨: GA 출시, 고급 활용법 포함 | https://developers.openai.com/codex/subagents |
| Pro 2x 프로모 종료(2026년 5월 31일) | "openai codex pro promo june 2026" | 신규 확인: 2026년 5월 31일 종료, 6월 1일부터 $100/월 플랜 용량 반감 | https://aitoolsrecap.com/Blog/openai-codex-pro-pricing-promo-ends-june-2026 |
| Computer Use on Windows(2026년 5월 29일) | "openai codex windows computer use 2026" | 신규 확인: 2026년 5월 29일 v26.527에서 Windows Computer Use 출시 | https://kingy.ai/news/openai-just-brought-codex-computer-use-to-windows-what-pc-users-get-now/ |
| Codex-only 시트(팀용 과금) | "codex only seat pricing team 2026" | 확인됨: 팀별 유연 과금 출시 | https://openai.com/index/codex-flexible-pricing-for-teams/ |

## 잔존/신규 오류
### 🔴 심각
(없음)

### 🟡 주의
| 항목 | 교재 내용 | 공식 문서 | 출처 |
|------|---------|---------|-----|
| Pro 2x 프로모 종료 | 언급 없음 | 2026년 5월 31일 Pro 2x 프로모 종료. 6월 1일부터 $100/월 플랜 실용량 반감. 비용 계획에 영향 | https://aitoolsrecap.com/Blog/openai-codex-pro-pricing-promo-ends-june-2026 |
| Windows Computer Use | 언급 없음 | 2026년 5월 29일 Windows에서 Computer Use 기능 출시. 포어그라운드 전용, EEA/UK/스위스 미지원 | https://openai.com/index/introducing-the-codex-app/ |

### 🟢 확인됨
- 토큰 기반 과금 전환(2026년 4월 2일) 정확
- Pro 5x $100/월(2026년 4월 9일) 신설 정확
- GPT-5.5 업그레이드 반영 정확
- codex profiles/history search 명령 정확
- Subagents GA 활용법 정확
- 고수의 일일 루틴 패턴 정확
- Assistants API 버전 주의 명시 정확
- LangGraph 버전 주의 명시 정확

## R4 대비 개선도
- R4 WHI: 0.06
- R5 WHI: 0.04 (Pro 2x 프로모 종료, Windows Computer Use 추가)

## 신뢰도 (R5)
- **점수**: 9.4/10
