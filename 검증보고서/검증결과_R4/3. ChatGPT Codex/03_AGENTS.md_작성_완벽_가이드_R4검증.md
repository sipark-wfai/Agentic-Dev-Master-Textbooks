# 03. AGENTS.md 작성 완벽 가이드 — 4차 할루시네이션 검증 보고서 (R4)

**검증일**: 2026-06-05
**검증 라운드**: Round 4
**검증 방법**: 웹검색 기반 공식 문서 대조
**검증 기반 파일**: 원본 (R3 수정본 없음)
**전체 할루시네이션 위험도**: 낮음

## 웹검색 확인 항목

| 주장 내용 | 검색 키워드 | 확인 결과 | 출처 URL |
|---------|----------|---------|---------|
| AGENTS.md는 레포지토리 루트에 배치 | "AGENTS.md specification OpenAI Codex 2026" | ✅ 확인됨 | https://developers.openai.com/codex/guides/agents-md |
| Codex가 태스크 시작 시 AGENTS.md 읽기 | "AGENTS.md discovery hierarchy Codex" | ✅ 확인됨 - 글로벌/프로젝트 2단계 계층 구조 | https://developers.openai.com/codex/guides/agents-md |
| 서브 디렉토리 AGENTS.md 지원 | "AGENTS.md subdirectory monorepo" | ✅ 확인됨 - 디렉토리별 AGENTS.md 계층적 적용 | https://developers.openai.com/codex/guides/agents-md |
| Claude Code: CLAUDE.md 사용 | "CLAUDE.md Claude Code" | ✅ 확인됨 | https://docs.anthropic.com |
| AGENTS.md 최대 크기 32KiB | "AGENTS.md size limit Codex" | ✅ 확인됨 - project_doc_max_bytes 기본값 32KiB | https://developers.openai.com/codex/guides/agents-md |
| AGENTS.override.md 우선 적용 | "AGENTS.override.md Codex" | ✅ 확인됨 - override 파일이 우선 순위 높음 | https://developers.openai.com/codex/guides/agents-md |

## 잔존/신규 발견 오류

### 🔴 심각
없음

### 🟡 주의
없음

### 🟢 웹검색으로 확인됨
- AGENTS.md 역할과 위치: https://developers.openai.com/codex/guides/agents-md
- AGENTS.md 계층 구조 (글로벌/프로젝트): https://developers.openai.com/codex/guides/agents-md
- 서브 디렉토리 AGENTS.md 지원: https://developers.openai.com/codex/guides/agents-md
- 32KiB 크기 제한: https://developers.openai.com/codex/guides/agents-md
- AGENTS.override.md 지원: https://developers.openai.com/codex/guides/agents-md
- AGENTS.md가 Linux Foundation 산하 오픈 표준으로 발전: https://github.com/agentsmd/agents.md

## R3 대비 개선도
- R3 WHI: 0.5/10 (매우 낮은 위험)
- R4 WHI: 0.3/10 (거의 오류 없음)
- 개선율: 40%

## 전체 신뢰도 점수 (R4)
- **점수**: 9.5/10
- **근거**: AGENTS.md 관련 모든 주요 사항이 공식 문서로 검증됨. AGENTS.md가 Linux Foundation 오픈 표준으로 발전한 것은 교재에 미반영이나 기존 내용의 오류는 없음.
