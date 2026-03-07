# 🚀 Featured Projects

## 🛡️ AI Security

<details open>
<summary>
  <sub>(Indirect Prompt Injection Detection)</sub>
</summary>

### 📑 [Analysis on the Robustness of Indirect Prompt Injection Detection in Quantized Large Language Models](https://github.com/shshinbox/master-research-ipi-pipeline)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Type: Academic](https://img.shields.io/badge/Type-Academic-blue?style=flat-square) ![Domain: AI_Security](https://img.shields.io/badge/Domain-AI_Security-red?style=flat-square)
> **양자화된 LLM 환경에서의 간접 프롬프트 인젝션 탐지 강건성 분석 (석사 학위 논문, 2025)**
- **연구 요약**: INT8 양자화가 적용된 LLM 환경에서 활성화(Activation) 기반 보안 탐지 기법의 유효성을 실증하고, 노이즈로 인한 내부 레이어의 보안 특성 변화를 분석
- **주요 성과**:
    - 양자화 노이즈 누적으로 인해 최적 탐지 지점이 후반부에서 중간 레이어로 이동하는 구조적 변화 확인
    - FP32 대비 메모리가 절감된 환경에서 ROC-AUC 0.9698의 높은 탐지 성능 유지
- **기술 키워드**: `Python`, `PyTorch`, `HuggingFace Transformers`, `BitsAndBytes`, `Scikit-learn`
- [논문 요약 바로가기 (PDF)](https://shshinbox.github.io/master-research-ipi-pipeline/%EC%84%9D%EC%82%AC%ED%95%99%EC%9C%84%EB%85%BC%EB%AC%B8_%EC%9A%94%EC%95%BD.pdf)

</details>

---

## 🤖 AI Agents

<details open> 
<summary>
  <sub>(Graph-based Agentic Workflow)</sub>
</summary>
  
### 🏠 [RealtyAgent](https://github.com/shshinbox/RealtyAgent)
![Building](https://img.shields.io/badge/Status-Building-orange?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Focus: Agentic Workflow](https://img.shields.io/badge/Focus-Agentic_Workflow-brightgreen?style=flat-square)
> **부동산 상담 멀티 에이전트**
- LangGraph 기반 상태 중심 구조로 AI Agent 설계
- API 결과 실패 또는 응답값이 없을 경우 재시도 루프 로직 구현
- 요청 분석/계획/실행 단계를 개별 노드로 구조화하여 단계별 책임 분리
- 실행 통제를 위한 HITL(Human-in-the-Loop) 개입 구조 설계
- **기술 키워드**: `Python`, `LangGraph`, `FastAPI`
- [아키텍처 요약 바로가기 (PDF)](https://shshinbox.github.io/RealtyAgent/RealtyAgent_%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4.pdf)

</details>

<details open>
<summary>
  <sub>(Linear Stateless Tool-Calling Agent)</sub>
</summary>
  
### 🏠 [Real Estate Agent](https://github.com/shshinbox/real-estate-agent)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Team](https://img.shields.io/badge/Project-Team-blueviolet?style=flat-square)
> **LLM API 활용 RAG 기반 챗봇**
- **기술 키워드**: `Python`,`FAISS`, `RAG`, `OpenAI API`
- **상세 자료**: [📄 시스템 기획 및 아키텍처 바로가기 (PDF)](https://github.com/shshinbox/real-estate-agent/blob/main/%EB%B6%80%EB%8F%99%EC%82%B0%EC%B4%88%EB%B3%B4%EB%A5%BC_%EC%9C%84%ED%95%9C_%EB%B6%80%EB%8F%99%EC%82%B0_%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8_%EA%B5%AC%EC%B6%95_20251208_v1.0.pdf)

</details>

---

## ☕ Backend Engineering

<details open> 
<summary>
  <sub>(Distributed Concurrency Control)</sub>
</summary>

### ☕ [Java Spring Backend: Ticketing System](https://github.com/shshinbox/concert-reservation-service)
![Maintenance](https://img.shields.io/badge/Status-Maintenance-blue?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Experience-Based](https://img.shields.io/badge/Project-Experience--Based-007396?style=flat-square) ![Expertise-Backend-007396?style=flat-square](https://img.shields.io/badge/Expertise-Backend-007396?style=flat-square) 
> **Kafka, Redis 활용 동시성 제어 및 대기열 관리**
- **기술 키워드**: `Java`, `Spring Boot`, `JPA`, `Kafka`, `Redis`, `Security`, `MariaDB`

</details>

---

## 🏗️ Data Engineering

<details open> 
<summary>
  <sub>(Concurrent Data Pipelines)</sub>
</summary>

### 📄 [Python Data Pipeline: arXiv Text Extractor](https://github.com/shshinbox/arxiv-text-extractor2)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Methodology](https://img.shields.io/badge/Methodology-Vibe--Coding-black?style=flat-square&logo=openai&logoColor=white) ![Focus-Data_Engineering](https://img.shields.io/badge/Focus-Data_Engineering-brightgreen?style=flat-square)
> **비동기 병렬 연산 arXiv 데이터 수집 파이프라인**
- **기술 키워드**: `Python`, `AsyncIO`, `Multiprocessing`, `Aiohttp`, `PostgreSQL`, `MongoDB`, `SQLAlchemy`

</details>
