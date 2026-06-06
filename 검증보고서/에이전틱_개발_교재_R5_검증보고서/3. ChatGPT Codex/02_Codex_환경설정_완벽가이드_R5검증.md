# 02. Codex 환경 설정 완벽 가이드 — 5차 할루시네이션 검증 보고서 (R5)

**검증일**: 2026-06-06
**검증 라운드**: Round 5
**검증 방법**: 웹검색 기반 공식 문서 대조
**검증 기반**: R4 수정본
**전체 할루시네이션 위험도**: 낮음

## 웹검색 확인 항목
| 주장 내용 | 검색어 | 결과 | 출처 URL |
|---------|------|------|---------|
| Pro 중간 티어 $100/월 신설 | "OpenAI Codex pricing plans June 2026" | 확인됨: Pro 5x $100/월, Pro 20x $200/월 | https://developers.openai.com/codex/pricing |
| 토큰 기반 과금 전환(2026년 4월) | "OpenAI Codex token billing April 2026" | 확인됨: 2026년 4월 2일 전환 | https://help.openai.com/en/articles/20001106-codex-rate-card |
| GPT-5.4/GPT-5.3-Codex 모델명 | "OpenAI Codex models 2026" | 주의: GPT-5.5가 2026년 4월 23일 주력 모델로 전환됨 | https://openai.com/index/introducing-gpt-5-5/ |
| Node.js 22 이상 요구사항 | "openai codex CLI 2026 requirements" | 확인됨 | https://developers.openai.com/codex/cli |
| npm install -g @openai/codex | "openai codex CLI install 2026" | 확인됨 | https://github.com/openai/codex |
| Pro 2x 프로모 종료(2026년 5월 31일) | "OpenAI Codex Pro pricing promo 2026" | 신규 확인: 2026년 5월 31일 프로모 종료, 6월 1일부터 용량 반감 | https://aitoolsrecap.com/Blog/openai-codex-pro-pricing-promo-ends-june-2026 |

## 잔존/신규 오류
### 🔴 심각
(없음)

### 🟡 주의
| 항목 | 교재 내용 | 공식 문서 | 출처 |
|------|---------|---------|-----|
| 주요 모델명 | GPT-5.4, GPT-5.3-Codex | GPT-5.5가 2026년 4월 23일 출시되어 주력 모델로 전환됨. GPT-5.4는 보조 모델로 잔존 | https://openai.com/index/introducing-gpt-5-5/ |
| Pro 2x 프로모 | 언급 없음 | 2026년 5월 31일 Pro 2x 프로모 종료, 6월 1일부터 $100 플랜 실용량 반감 | https://aitoolsrecap.com/Blog/openai-codex-pro-pricing-promo-ends-june-2026 |
| Go 플랜 | 언급 없음 | $8/월 Go 플랜 추가됨(경량 사용자용) | https://developers.openai.com/codex/pricing |

### 🟢 확인됨
- Plus $20/월, Pro $100/월(5x), Pro $200/월(20x) 구조 정확
- 토큰 기반 과금 전환(2026년 4월 2일) 정확
- GPT-5.3-Codex 크레딧 단가(43.75/1M input, 350/1M output) 정확
- Node.js 22 이상 요구사항 정확
- @openai/codex 패키지명 정확
- curl 설치 방식 정확

## R4 대비 개선도
- R4 WHI: 0.08
- R5 WHI: 0.05 (GPT-5.5 전환 및 Go 플랜, 프로모 종료 반영)

## 신뢰도 (R5)
- **점수**: 9.3/10
