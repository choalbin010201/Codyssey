# AI Prompt Engineering Mission

## 프로젝트 개요

본 프로젝트는 LLM을 활용한 업무 자동화 프롬프트 패키지 제작 과제입니다.  
주제는 **소상공인 홍보 포스터 문구 및 구성안 제작 AI**입니다.

사용자는 가게 종류, 홍보 목적, 타겟 고객, 포스터 사용처, 원하는 분위기, 필수 포함 정보 등을 입력하고, AI는 1장짜리 홍보 포스터에 들어갈 제목, 부제목, 본문 문구, CTA, 레이아웃 구성안을 생성합니다.

## 사용 모델

- Gemini 3 Flash
- Claude Sonnet
- GPT-5.4

모델 비교 결과, 최종 시스템에는 **Claude Sonnet**을 선정했습니다.

## 폴더 구조

```text
ai-prompt-engineering-mission/
├─ README.md
├─ reports/
│  ├─ 01_모델비교_선정보고서.md
│  ├─ 02_시스템설계문서.md
│  └─ 03_실행로그.md
├─ prompts/
│  ├─ model_comparison_prompt.md
│  ├─ system_prompt_v1.md
│  └─ system_prompt_v2.md
└─ logs/
   └─ conversation_log_raw.md
