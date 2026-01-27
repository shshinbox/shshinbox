## 🚀 Featured Projects

### 🛡️ [Master's Thesis: LLM Security & Quantization](https://github.com/shshinbox/master-research-ipi-pipeline)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Type: Academic](https://img.shields.io/badge/Type-Academic-blue?style=flat-square) ![Domain: AI_Security](https://img.shields.io/badge/Domain-AI_Security-red?style=flat-square)
> **"양자화된 LLM 환경에서의 간접 프롬프트 인젝션 탐지 강건성 분석"**
- **Core Concept**: INT8 양자화 LLM 환경에서 활성화 기반 간접 프롬프트 인젝션 탐지의 강건성을 실증하고, 노이즈 누적으로 인한 최적 탐지 레이어의 이동(Layer Shift) 현상 실증
- **Key Findings**:
  - 양자화 노이즈 영향으로 최적 탐지 지점이 후반부에서 중간 레이어로 이동하는 구조적 특성 확인
  - FP32 대비 메모리 사용량을 약 70% 절감하면서도 최대 0.9698(ROC-AUC)의 높은 탐지 성능 유지
- **Tech Keywords**: `Python`, `PyTorch`, `HuggingFace Transformers`, `LLM.int8()`, `Scikit-learn`
- **Material**: [📄 논문 요약 바로가기 (PDF)](https://github.com/shshinbox/master-research-ipi-pipeline/blob/master/%EC%84%9D%EC%82%AC%ED%95%99%EC%9C%84%EB%85%BC%EB%AC%B8_%EC%9A%94%EC%95%BD_v1.0.pdf)

---

### 🏠 [Stateful Agentic System: Real Estate Consultation v2.0](https://github.com/shshinbox/RealtyAgent)
![Building](https://img.shields.io/badge/Status-Building-orange?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Focus: Agentic Workflow](https://img.shields.io/badge/Focus-Agentic_Workflow-brightgreen?style=flat-square)
> **"LangGraph 기반의 노드 간 상태 공유와 자가 수정 루프를 통해 상담의 정합성을 갖춘 시스템"**
- **Core Concept**: 단방향 응답의 한계를 극복하기 위해 단계별 검증과 자가 수정(Self-Correction) 루프를 설계하고, HITL(Human-in-the-loop)를 결합
- **Tech Keywords**: `Python`, `LangGraph`, `FastAPI`, `State Management`, `Asynchronous Design`, `Pydantic`
- **Quick Links**: 
  - [📦 LangGraph Module](https://github.com/shshinbox/RealtyAgent/tree/main/engine) : 워크플로우 그래프 설계
  - [⚡ FastAPI Server](https://github.com/shshinbox/RealtyAgent/tree/main/server) : 서빙을 위한 비동기 백엔드 구축

---

### 🏠 [Linear Architecture Leveraging OpenAI API and MCP: Real Estate Consultation v1.0](https://github.com/shshinbox/real-estate-agent)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Team](https://img.shields.io/badge/Project-Team-blueviolet?style=flat-square)
> **"OpenAI API와 MCP를 활용하여 모델의 자율적 계획과 도구 순차 호출을 구현한 계획 기반 시스템"**
- **Core Concept**: 별도의 프레임워크 없이 OpenAI API 수준에서 MCP(Model Context Protocol) 도구 설명을 제공하여 모델이 스스로 실행 계획을 수립하고 순차 호출하도록 설계
- **Tech Keywords**: `Python`, `OpenAI API`, `MCP`, `FAISS`, `RAG`
- **Material**: [📄 시스템 기획 및 상세 아키텍처 바로가기 (PDF)](https://github.com/shshinbox/real-estate-agent/blob/main/%EB%B6%80%EB%8F%99%EC%82%B0%EC%B4%88%EB%B3%B4%EB%A5%BC_%EC%9C%84%ED%95%9C_%EB%B6%80%EB%8F%99%EC%82%B0_%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8_%EA%B5%AC%EC%B6%95_20251208_v1.0.pdf)

---

### 📄 [Python Data Pipeline: arXiv Text Extractor](https://github.com/shshinbox/arxiv-text-extractor2)
![Completed](https://img.shields.io/badge/Status-Completed-green?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Methodology](https://img.shields.io/badge/Methodology-Vibe--Coding-black?style=flat-square&logo=openai&logoColor=white) ![Focus-Data_Engineering](https://img.shields.io/badge/Focus-Data_Engineering-brightgreen?style=flat-square)
> **"비동기 I/O와 멀티 프로세싱을 결합하여 데이터 수집 효율을 극대화한 Arxiv 추출 파이프라인"**
- **Core Concept**: AsyncIO 기반의 비동기 다운로드와 Multiprocessing 기반의 텍스트 추출을 병렬로 구성하여 처리 속도를 높이고, Exponential Backoff 및 Jitter 로직을 적용해 수집 환경의 안정성 확보
- **Vibe-Coding Point**: AI를 아키텍처 설계 파트너로 활용하여 5일 만에 시스템 전체를 구축했으며, 파이썬의 GIL 제약을 극복한 병렬 구조와 하이브리드 스토리지(PostgreSQL+MongoDB) 연동 로직 완성
- **Tech Keywords**: `Python`, `AsyncIO`, `Multiprocessing`, `Aiohttp`, `PostgreSQL`, `MongoDB`, `SQLAlchemy`, `Pydantic`

---

### ☕ [Java Spring Backend: Ticketing System](https://github.com/shshinbox/concert-reservation-service)
![Maintenance](https://img.shields.io/badge/Status-Maintenance-blue?style=flat-square) ![Personal](https://img.shields.io/badge/Project-Personal-lightgrey?style=flat-square) ![Experience-Based](https://img.shields.io/badge/Project-Experience--Based-007396?style=flat-square) ![Expertise-Backend-007396?style=flat-square](https://img.shields.io/badge/Expertise-Backend-007396?style=flat-square) 
> **"Kafka 오프셋 추정 알고리즘과 Redis 분산 락을 결합하여 동시성 문제를 해결한 예약 시스템"**
- **Core Concept**: Kafka 파티션 오프셋 기반의 대기 순번 산출 로직을 직접 설계하여 트래픽 유입을 제어하고, Redis 기반의 입장권(Active Token) 검증 및 분산 락으로 데이터 정합성 확보
- **Tech Keywords**: `Java`, `Spring Boot`, `JPA`, `Kafka`, `Redis`, `Security`, `MariaDB`
