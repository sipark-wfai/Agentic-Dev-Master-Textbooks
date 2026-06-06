# 01. ChatGPT Codex 완벽 입문 — 4차 할루시네이션 검증 보고서 (R4)

**검증일**: 2026-06-05
**검증 라운드**: Round 4
**검증 방법**: 웹검색 기반 공식 문서 대조
**검증 기반 파일**: R3 수정본
**전체 할루시네이션 위험도**: 낮음

## 웹검색 확인 항목

| 주장 내용 | 검색 키워드 | 확인 결과 | 출처 URL |
|---------|----------|---------|---------|
| ChatGPT Codex는 클라우드 기반 에이전틱 코딩 플랫폼 | "OpenAI Codex CLI documentation 2026" | ✅ 확인됨 | https://developers.openai.com/codex |
| ChatGPT Plus($20), Pro($200) 구독 필요 | "OpenAI Codex pricing 2026" | ⚠️ 부분 정확 - 2026년 4월 $100 Pro 티어 신설 | https://developers.openai.com/codex/pricing |
| Ubuntu 22.04 클라우드 샌드박스 사용 | "OpenAI Codex sandbox environment" | ✅ 확인됨 | https://developers.openai.com/codex/cli |
| AGENTS.md 규칙 파일 지원 | "AGENTS.md specification OpenAI Codex 2026" | ✅ 확인됨 - 오픈 표준으로 발전 | https://developers.openai.com/codex/guides/agents-md |
| o3/o4-mini 모델 사용 | "OpenAI Codex model 2026" | ⚠️ 업데이트 필요 - GPT-5.4, GPT-5.3-Codex 등으로 변경 | https://developers.openai.com/codex/cli/reference |
| GitHub OAuth 연동으로 PR 자동 생성 | "OpenAI Codex GitHub integration 2026" | ✅ 확인됨 | https://developers.openai.com/codex |
| 비동기 병렬 태스크 실행 가능 | "OpenAI Codex async parallel tasks" | ✅ 확인됨 | https://developers.openai.com/codex/cli/features |

## 잔존/신규 발견 오류

### 🔴 심각
없음

### 🟡 주의
| 항목 | 교재 내용 | 공식 문서 내용 | 출처 |
|------|---------|------------|------|
| ChatGPT 요금제 구조 | Plus($20)/Pro($200) 2단계 언급 | 2026년 4월 $100 Pro 티어 신설로 구조 복잡화 | https://developers.openai.com/codex/pricing |
| 사용 모델명 | o3/o4-mini 언급 | 2026년 현재 GPT-5.4, GPT-5.3-Codex 등으로 변경 | https://developers.openai.com/codex/cli |

### 🟢 웹검색으로 확인됨
- ChatGPT Codex 에이전틱 코딩 플랫폼 개념: https://developers.openai.com/codex
- AGENTS.md 공식 지원 및 오픈 표준화: https://developers.openai.com/codex/guides/agents-md
- Ubuntu 기반 클라우드 샌드박스: https://developers.openai.com/codex/cli
- GitHub 네이티브 PR 자동 생성: https://developers.openai.com/codex
- 비동기/병렬 태스크 실행: https://developers.openai.com/codex/cli/features
- Antigravity 제조사 수정(Google): R3에서 수정 완료
- 기존 Copilot과의 차이점 설명: 정확

## R3 대비 개선도
- R3 WHI: 0.8/10 (낮은 위험)
- R4 WHI: 0.6/10 (매우 낮은 위험)
- 개선율: 25%

## 전체 신뢰도 점수 (R4)
- **점수**: 9.0/10
- **근거**: 핵심 개념(에이전틱 패러다임, AGENTS.md, GitHub 연동, 비동기 실행)이 모두 공식 문서로 확인됨. 요금제 구조와 모델명이 2026년 업데이트로 소폭 변경되었으나 치명적 오류 없음.
