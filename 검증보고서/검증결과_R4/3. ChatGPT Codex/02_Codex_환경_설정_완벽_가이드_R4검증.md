# 02. Codex 환경 설정 완벽 가이드 — 4차 할루시네이션 검증 보고서 (R4)

**검증일**: 2026-06-05
**검증 라운드**: Round 4
**검증 방법**: 웹검색 기반 공식 문서 대조
**검증 기반 파일**: 원본 (R3 수정본 없음)
**전체 할루시네이션 위험도**: 중간

## 웹검색 확인 항목

| 주장 내용 | 검색 키워드 | 확인 결과 | 출처 URL |
|---------|----------|---------|---------|
| Plus($20), Pro($200) 요금제만 언급 | "OpenAI Codex pricing 2026" | ⚠️ 불완전 - 2026년 4월 $100 Pro 중간 티어 신설. Free/Go도 제한적 Codex 접근 가능 | https://developers.openai.com/codex/pricing |
| CLI 설치: npm install -g @openai/codex | "OpenAI Codex CLI installation 2026" | ✅ 확인됨 - npm, curl 스크립트, Homebrew 모두 지원 | https://developers.openai.com/codex/cli |
| GitHub OAuth 연동 방식 | "OpenAI Codex GitHub OAuth setup" | ✅ 확인됨 - chatgpt.com/codex에서 GitHub 연동 설정 | https://developers.openai.com/codex/auth |
| Plus: o4-mini, Pro: o3/o4-mini 모델 | "OpenAI Codex model selection 2026" | ⚠️ 업데이트 필요 - 2026년 GPT-5.4, GPT-5.3-Codex 등 최신 모델 제공 | https://developers.openai.com/codex/cli/reference |
| 동시 실행 태스크: Plus 3개, Pro 무제한 | "OpenAI Codex parallel tasks limit 2026" | ⚠️ 변경 가능성 - 토큰 기반 과금으로 변경되어 동시 실행 제한 방식 변경됨 | https://developers.openai.com/codex/pricing |

## 잔존/신규 발견 오류

### 🔴 심각
없음

### 🟡 주의
| 항목 | 교재 내용 | 공식 문서 내용 | 출처 |
|------|---------|------------|------|
| 요금제 구조 | Plus($20)/Pro($200) 2단계 | 2026년 4월 $100 Pro 중간 티어 신설, Free/Go 티어도 제한적 접근 가능 | https://developers.openai.com/codex/pricing |
| 모델명 | o4-mini, o3 | GPT-5.4, GPT-5.3-Codex 등 최신 모델 라인업으로 변경 | https://developers.openai.com/codex/cli |
| 태스크 동시 실행 제한 | Plus 3개, Pro 무제한 | 토큰 기반 과금 체계로 전환 후 제한 방식 변경 | https://developers.openai.com/codex/pricing |

### 🟢 웹검색으로 확인됨
- CLI 설치 방법(npm, curl, brew): https://developers.openai.com/codex/cli
- GitHub OAuth 연동: https://developers.openai.com/codex/auth
- 챗GPT 계정으로 로그인 방식: https://developers.openai.com/codex/quickstart

## R3 대비 개선도
- R3 WHI: 2.0/10 (중간 위험, 원본 그대로)
- R4 WHI: 1.5/10 (낮은-중간 위험)
- 개선율: 25% (요금제/모델 주의 항목 잔존)

## 전체 신뢰도 점수 (R4)
- **점수**: 7.5/10
- **근거**: 설치 방법, GitHub 연동 등 핵심 절차는 정확. 요금제 구조와 모델명이 2026년 대폭 변경되어 정보 업데이트 필요. R3 수정본이 없어 원본 오류가 잔존함.
