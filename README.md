# 🚀 Featured Projects

## 🛡️ AI Security

<details open>
<summary>
  <sub>(Indirect Prompt Injection Detection)</sub>
</summary>

### 📑 [Analysis on the Robustness of Indirect Prompt Injection Detection in Quantized Large Language Models](https://github.com/shshinbox/master-research-ipi-pipeline)
> **양자화된 LLM 환경에서의 간접 프롬프트 인젝션 탐지 강건성 분석 (석사 학위 논문, 2025)**

![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Type: Academic](https://img.shields.io/badge/Type-Academic-blue?style=flat-square) ![Domain: AI_Security](https://img.shields.io/badge/Domain-AI_Security-red?style=flat-square)
- **연구 요약**: INT8 양자화가 적용된 LLM 환경에서 활성화(Activation) 기반 보안 탐지 기법의 유효성을 실증하고, 노이즈로 인한 내부 레이어의 보안 특성 변화를 분석
- **주요 성과**:
  - **Layer Shift 규명:** 양자화 노이즈 누적으로 인해 최적 탐지 지점이 후반부에서 중간 레이어로 이동하는 구조적 변화 확인
  - **리소스 최적화:** FP32 대비 메모리가 절감된 환경에서 **ROC-AUC 0.9698**의 높은 탐지 성능 유지
- **기술 키워드**: `Python`, `PyTorch`, `HuggingFace Transformers`, `BitsAndBytes`, `Scikit-learn`
- **상세 자료**: [📄 논문 요약 바로가기 (PDF)](https://github.com/shshinbox/master-research-ipi-pipeline/blob/master/%EC%84%9D%EC%82%AC%ED%95%99%EC%9C%84%EB%85%BC%EB%AC%B8_%EC%9A%94%EC%95%BD_v1.0.pdf)

</details>

---

## 🤖 AI Agents

<details open> 
<summary>
  <sub>(Graph-based Agentic Workflow)</sub>
</summary>
  
### 🏠 [Stateful Agentic System: Real Estate Consultation v2.0](https://github.com/shshinbox/RealtyAgent)
![Building](https://img.shields.io/badge/Status-Building-orange?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Focus: Agentic Workflow](https://img.shields.io/badge/Focus-Agentic_Workflow-brightgreen?style=flat-square)
> **LangGraph 기반의 상태 보존형 자가 수정 워크플로우**
- **개요**: 단방향 응답의 한계를 극복하기 위해 단계별 검증 노드와 자가 수정(Self-Correction) 루프를 설계하고, 중요한 판단 지점에 HITL(Human-in-the-loop)을 결합
- **구현 특징**: 상담 문맥을 유지하기 위한 전역 상태(State) 설계와 각 에이전트 노드 간의 데이터 전달 흐름(Graph Edge) 최적화를 중점적으로 설계
- **기술 키워드**: `Python`, `LangGraph`, `FastAPI`, `AsyncSQLiteSaver`
- **상세 자료**: 
  - [📦 LangGraph Module](https://github.com/shshinbox/RealtyAgent/tree/main/engine) : 워크플로우 그래프 설계
  - [⚡ FastAPI Server](https://github.com/shshinbox/RealtyAgent/tree/main/server) : 서빙을 위한 비동기 백엔드 구축

</details>

<details open>
<summary>
  <sub>(Linear Stateless Tool-Calling Agent)</sub>
</summary>
  
### 🏠 [Linear Architecture Leveraging OpenAI API and MCP: Real Estate Consultation v1.0](https://github.com/shshinbox/real-estate-agent)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Team](https://img.shields.io/badge/Project-Team-blueviolet?style=flat-square)
> **MCP와 OpenAI API를 활용한 자율 계획 기반 에이전트**
- **개요**: 별도 프레임워크 없이 MCP를 통해 모델 스스로 실행 계획을 수립하고 도구를 순차 호출하는 Stateless 시스템
- **구현 특징:** FAISS 기반 RAG 엔진 구축 및 부동산 도메인 데이터 검색 최적화
- **기술 키워드**: `Python`, `OpenAI API`, `MCP`, `FAISS`, `RAG`
- **상세 자료**: [📄 시스템 기획 및 상세 아키텍처 바로가기 (PDF)](https://github.com/shshinbox/real-estate-agent/blob/main/%EB%B6%80%EB%8F%99%EC%82%B0%EC%B4%88%EB%B3%B4%EB%A5%BC_%EC%9C%84%ED%95%9C_%EB%B6%80%EB%8F%99%EC%82%B0_%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8_%EA%B5%AC%EC%B6%95_20251208_v1.0.pdf)

</details>

---

## 🏗️ Data Engineering

<details open> 
<summary>
  <sub>(Concurrent Data Pipelines)</sub>
</summary>

### 📄 [Python Data Pipeline: arXiv Text Extractor](https://github.com/shshinbox/arxiv-text-extractor2)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Methodology](https://img.shields.io/badge/Methodology-Vibe--Coding-black?style=flat-square&logo=openai&logoColor=white) ![Focus-Data_Engineering](https://img.shields.io/badge/Focus-Data_Engineering-brightgreen?style=flat-square)
> **비동기 통신과 병렬 연산을 결합한 대용량 학술 데이터 수집 시스템**
- **개요**: 비동기 네트워크 통신과 CPU 병렬 처리를 동시에 활용해, 대량의 논문 PDF를 끊김 없이 수집하고 텍스트를 추출하는 파이프라인
- **AI 협업 설계**: 파이썬의 성능 제약(GIL)을 우회하여 네트워크 다운로드와 텍스트 추출 연산을 동시에 수행할 수 있는 하이브리드 병렬 구조 설계를 중점적으로 요청함
- **기술 키워드**: `Python`, `AsyncIO`, `Multiprocessing`, `Aiohttp`, `PostgreSQL`, `MongoDB`, `SQLAlchemy`

</details>

---

## ☕ Backend Engineering

<details open> 
<summary>
  <sub>(Distributed Concurrency Control)</sub>
</summary>

### ☕ [Java Spring Backend: Ticketing System](https://github.com/shshinbox/concert-reservation-service)
![Maintenance](https://img.shields.io/badge/Status-Maintenance-blue?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Experience-Based](https://img.shields.io/badge/Project-Experience--Based-007396?style=flat-square) ![Expertise-Backend-007396?style=flat-square](https://img.shields.io/badge/Expertise-Backend-007396?style=flat-square) 
> **Kafka와 Redis를 활용한 고가용성 동시성 제어 및 대기열 관리 시스템**
- **개요**: 분산 환경에서 발생하는 데이터 정합성 문제와 트래픽 폭주 상황에서의 안정적인 서비스 제공에 집중함
  - **Traffic Control:** Kafka 파티션 오프셋 추정 알고리즘을 통한 실시간 대기 순번 산출 및 진입 제어
  - **Concurrency Control:** Redis 분산 락(Distributed Lock)을 적용하여 다중 노드 간 데이터 정합성 보장
  - **Token Validation:** Redis 기반 입장권 라이프사이클 관리 및 검증 로직 구현
- **기술 키워드**: `Java`, `Spring Boot`, `JPA`, `Kafka`, `Redis`, `Security`, `MariaDB`

</details>

