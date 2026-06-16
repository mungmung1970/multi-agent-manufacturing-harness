Agent끼리 직접 호출 금지
모든 호출은 Orchestrator/EventBus 경유
Orchestrator는 AI 추론 금지
LLM은 수치 판단 금지
OOD 발생 시 Predictor 호출 금지
모든 판단은 Audit Log 저장
테스트 없는 핵심 로직 변경 금지