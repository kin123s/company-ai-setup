# 🏢 Company AI Setup Prompt (Agent Mission)

> **사용 방법:** 회사 업무용 레포지토리와 본 `company-ai-setup` 디렉토리를 나란히(같은 상위 폴더 내에) 배치한 후, 새로운 AI 에이전트(Cursor, Copilot, Antigravity 등)에게 아래 프롬프트를 복사하여 전달하세요.

---

### 📋 프롬프트 (아래 내용을 복사해서 에이전트에게 전달하세요)

```text
[임무: 업무용 프로젝트를 위한 전역 .ai 환경 구축]

현재 내 작업 환경의 부모 디렉토리에 내가 직접 설계하고 구축한 `company-ai-setup` 템플릿 프로젝트가 존재합니다.
당신의 첫 번째 임무는 이 템플릿을 참고하여 현재 작업할 레포지토리에 `.ai` 디렉토리 아키텍처를 구축하는 것입니다.

1. `../company-ai-setup/.ai` 디렉토리와 그 하위 파일들(`rules.md`, `context/project.md`, `guidelines/`, `workflows/`, `state/sessions/` 등)을 그대로 복사하여 현재 작업 중인 프로젝트의 최상단 루트에 `.ai` 디렉토리로 구성해 주십시오.
2. 복사가 완료되면, `.ai/context/project.md` 안의 [여기에 프로젝트명 입력] 같은 Placeholder(빈칸) 부분들을 현재 프로젝트의 성격에 맞게 분석하여 임시로 채워 넣어 주십시오.
3. `.ai/rules.md`를 신규 환경에 맞게 숙독하고 인지해 주십시오.
4. 모든 작업이 완료되면, 다음 담당자(또는 나)가 문맥을 이어갈 수 있도록 `.ai/state/sessions/session_intro.md`에 첫 번째 세션 기록을 남기고, '인수인계서' 양식으로 현재까지 완료된 셋업 작업을 보고해 주십시오.
```

---
