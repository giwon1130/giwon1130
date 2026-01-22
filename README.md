# 안녕하세요, 백엔드 개발자 임기원입니다 👋

**Kotlin/Java 기반 백엔드 엔지니어**로, 대규모 시스템 설계와 GIS 기술을 활용한 플랫폼 개발에 강점을 가지고 있습니다.

<div align="center">

[![Email](https://img.shields.io/badge/Email-gwim1130@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gwim1130@naver.com)
[![Blog](https://img.shields.io/badge/Blog-dduckddack--2-FF5722?style=flat-square&logo=blogger&logoColor=white)](https://dduckddack-2.tistory.com)
[![Notion](https://img.shields.io/badge/Notion-Portfolio-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/dev-giwon/ce2318d46f3a4b66894ad04d1b20d986)

</div>

---

## 🛠️ 기술 스택

### Backend Development
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

- **주요 기술**: Kotlin, Java, Spring Boot, Spring Data JPA, QueryDSL
- **아키텍처**: REST API, gRPC, Microservices
- **특기**: 레거시 시스템 마이그레이션 및 성능 최적화

### Database & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

- PostgreSQL, MySQL, MongoDB를 활용한 데이터 모델링
- Redis 기반 캐싱 및 세션 관리
- PostGIS를 활용한 지리공간 데이터 처리

### GIS & Geospatial
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white)

- **GIS Stack**: PostGIS, GeoServer, OpenLayers, QGIS, GDAL
- **경험**: 디지털트윈, 위성/항공 이미지 분석 플랫폼 개발
- **특기**: 대용량 지리공간 데이터 처리 및 최적화

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

- **Cloud**: AWS, NCLOUD, IDC 환경 구축 및 운영
- **Container**: Docker, Kubernetes, Helm Chart
- **CI/CD**: GitHub Actions, ArgoCD, Jenkins, Harbor
- **OS**: Linux, Windows Server

### Messaging & Monitoring
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

- **Messaging**: Kafka, RabbitMQ 기반 비동기 메시징
- **Logging**: ELK Stack (Elasticsearch, Logstash, Kibana)
- **Monitoring**: 대규모 로그 수집 및 분석 시스템 구축

---

## 💼 주요 프로젝트

### 🏢 기업 프로젝트

#### 🛰️ 위성 이미지 라벨링 플랫폼 (LE3)
**에스아이에이(SIA)** | 2025.04 ~ 2026.01

- **역할**: Backend Developer
- **기술 스택**: Kotlin, Spring Boot, PostgreSQL, PostGIS, Redis
- **프로젝트 설명**: ML 모델 학습을 위한 지리공간 데이터 생성 및 관리 플랫폼
- **주요 업무**:
  - **Python FastAPI → Kotlin Spring Boot 마이그레이션**
    - API 응답 시간 **30% 개선**
    - Docker 이미지 크기 **85% 감소** (2GB → 300MB)
    - 메모리 사용량 **32% 감소**
  - 지리공간 데이터 처리 (PostGIS, JTS, Hibernate Spatial)
  - **13단계 라벨링 워크플로우** 구현 (Annotator → Reviewer → Evaluator → Manager)
  - JWT 기반 역할별 접근 제어 (RBAC)
  - AOI 관심지역 기능 개발

---

#### 🛰️ AI 기반 초소형 위성체계 SAR 징후탐지 및 초해상도 영상복원 기술
**에스아이에아(SIA)** | 2025.01 ~ 2025.08

- **역할**: Backend Developer
- **기술 스택**: Kotlin, Spring Boot, TCP/IP, Docker, Kubernetes
- **주요 업무**:
  - AI 모델과 시스템 간 연동을 고려한 아키텍처 설계
  - **TCP 통신 기반 분산 위성영상 AI 분석 서버** 개발
  - AI 분석 결과 파일을 처리하여 **API 형태로 제공**
  - 실시간 영상 처리 파이프라인 구성 및 안정화
- **성과**:
  - SAR 징후탐지 및 초해상도 영상복원에 특화된 분산 서버 구현
  - 외부 시스템 연동 용이성 확보
  - 한화시스템 협업을 통한 실제 위성체계 적용 가능성 검증

---

#### 📊 초거대 AI 감시 및 탐지 시스템 (리포트 자동화)
**에스아이에아(SIA)** | 2025.04 ~ 2025.09

- **역할**: Backend Developer
- **기술 스택**: Kotlin, Spring Boot 3.x, PostgreSQL, Redis, Kafka, PostGIS, Docker, Kubernetes
- **주요 업무**:
  - 대규모 변화탐지·객체탐지 데이터 처리 및 **리포트 자동화 시스템** 설계·구축
  - **SSE 기반 실시간 알림** 기능 구현 및 안정화
  - **Spring Cache** 기반 캐싱 처리로 대규모 데이터 응답 속도 개선
  - **Kafka**를 활용한 대규모 데이터 연계 및 비동기 처리
  - **GIS 기반 공간분석** 로직 구현 및 데이터 가공
- **성과**:
  - 대규모 위성/항공 영상 데이터 리포트 자동화 파이프라인 구축
  - 실시간 알림 및 캐싱 도입으로 서비스 응답성 개선
  - Kafka 기반 데이터 연계로 안정적인 분산 환경 운영 확보
  - GIS 기반 분석 기능 고도화를 통해 결과 데이터 활용성 확대

---

#### 📦 물류 통합 관리 플랫폼 및 GIS 기반 서비스 고도화
**와따에이아이** | 2023.08 ~ 2024.04

- **역할**: Backend Developer
- **기술 스택**: Java, Spring Boot, PostgreSQL, MongoDB, Kafka, ELK, Redis, GeoServer, GIS
- **주요 업무**:
  - 물류 통합 관리 플랫폼 백엔드 개발 및 실시간 데이터 처리
  - **GIS 기반 기능 개발**
    - IoT 실내 측위 SDK를 활용한 위치 추적 기능
    - 최단거리 계산 로직 적용으로 **실시간 네비게이션** 구현
    - **GeoServer 최적화**로 지도 렌더링 성능 개선 및 서버 자원 절감
    - 위치별 방문 통계 기능 개발
  - **Node.js → Spring Boot** 레거시 전환으로 유지보수성과 성능 개선
  - **Kafka + ELK** 로그 모니터링 환경 구축으로 장애 탐지·대응 체계 강화
  - 국립현대미술관 앱 개발 참여: 실내 위치 기반 안내 기능 구현
- **성과**:
  - 레거시 전환을 통한 시스템 안정성 **20% 이상 개선**
  - GeoServer 최적화로 렌더링 성능 및 서버 자원 효율성 향상
  - GIS 기반 기능 확장으로 물류 및 전시 공간 데이터 활용성 강화

---

#### 🎥 국방/보안 시설용 CCTV·광선로 지도 뷰어 솔루션
**CityEyeLab (프리랜서 PL)** | 2022.12 ~ 2023.08

- **역할**: Project Leader
- **기술 스택**: Java, Spring, React, OpenLayers, Docker, GIS
- **주요 업무**:
  - CCTV·광선로 지도 뷰어 솔루션 설계 및 개발 총괄
  - **RTSP 스트리밍 서버** 연동으로 실시간 영상 전송 구현
  - **폐쇄망 환경** 최적화 Docker 기반 맵 서버 구축 및 배포
  - **OpenLayers** 활용 지도 연계 및 GIS 시각화 기능 구현
  - 프로젝트 리딩: 요구사항 정의, 일정 관리, **개발팀(5명)** 업무 분담 및 품질 관리
- **성과**:
  - 국방/보안 시설 환경에 특화된 안정적 CCTV·광선로 뷰어 솔루션 구축
  - 폐쇄망 환경에서의 스트리밍 및 지도 시각화 기술 검증 완료

---

#### 🌐 디지털트윈 메타버스 융합 서비스 (듀플래닛)
**바이브컴퍼니** | 2021.10 ~ 2022.12

- **역할**: Backend Developer
- **기술 스택**: Java, Spring Boot, PostgreSQL, PostGIS, Redis, Docker, AWS, Angular
- **주요 업무**:
  - 디지털트윈 기반 **메타버스 B2C 서비스** 백엔드 개발·운영
  - 3D 건물 모델링, 검색, 결제, 외부 API 연계 기능 개발
  - **AWS 환경 무중단 배포** 및 로드밸런싱 구성
  - **Redis 캐싱**을 통한 성능 최적화
- **성과**:
  - 초기 수익 창출 및 대규모 사용자 트래픽 안정적 대응
  - 사용자 경험 중심 기능 제공으로 플랫폼 경쟁력 강화

---

#### 🏘️ 디지털트윈 기반 신도시 가상체험 플랫폼 (LH 3기 신도시)
**바이브컴퍼니** | 2021.03 ~ 2022.12

- **역할**: Backend Developer & DevOps
- **기술 스택**: Java, Spring Boot, PostgreSQL, PostGIS, Docker, Jenkins, Ncloud, IDC
- **주요 업무**:
  - 신도시 가상 모델하우스 플랫폼 백엔드 개발·운영
  - 디지털트윈 CMS, 경관·일조 시뮬레이션, 거리뷰 기능 개발
  - **Jenkins 기반 CI/CD** 환경 구축 및 자동화 배포 구성
  - Ncloud·IDC 환경 기반 서비스 운영
- **성과**:
  - 분양·홍보용 가상체험 서비스 운영으로 사용자 몰입도 증가
  - 안정적 CI/CD 도입으로 배포 리스크 감소 및 운영 효율성 향상

---

#### 🏙️ 스마트시티 사물데이터 융합 서비스 (IOTDA)
**미소정보기술** | 2020.06 ~ 2021.03

- **역할**: Backend Developer
- **기술 스택**: Java, Spring, MySQL, MongoDB, Kubernetes
- **주요 업무**:
  - IoT 기반 스마트시티 플랫폼 백엔드 개발
  - 차트·지도 기반 **IoT 데이터 시각화** 기능 구현
  - AI 분석 모듈 연계 및 REST API 개발
  - **MySQL·MongoDB ETL** 자동화 도구 개발
  - 내부망 지도 서버 및 보안 구조 설계
- **성과**:
  - IoT 데이터 분석 및 시각화 자동화로 데이터 활용성 향상
  - ETL 및 내부망 설계로 데이터 관리 프로세스 표준화

---

### 👨‍💻 개인 프로젝트

#### 🏢 공공기관 IoT 가시화 플랫폼
- **기술**: Spring Boot, WebSocket, Chart.js
- **설명**: 실시간 IoT 센서 데이터 모니터링 대시보드

#### 📹 국가기관 CCTV Viewer
- **기술**: Spring Boot, WebRTC, OpenLayers
- **설명**: 지도 기반 CCTV 통합 관제 시스템

#### ✈️ Trip_Memo (여행 공유 서비스)
- **기술**: Spring Boot, PostgreSQL, AWS S3
- **설명**: 여행 일정 공유 및 추천 플랫폼

#### 🏠 Home_Harmony (아파트 선택 도움 서비스)
- **기술**: Spring Boot, PostGIS, 공공 데이터 API
- **설명**: 지역별 아파트 정보 분석 및 추천

#### 🍔 AMR (AI 메뉴 추천 서비스)
- **기술**: Spring Boot, Python FastAPI, OpenAI API
- **설명**: 사용자 선호도 기반 메뉴 추천

---

## 🎯 핵심 역량

- ✅ **시스템 마이그레이션**: Python → Kotlin 전환으로 성능 30% 개선, Docker 이미지 85% 감소
- ✅ **GIS 전문성**: PostGIS, GeoServer를 활용한 대규모 지리공간 데이터 처리
- ✅ **엔터프라이즈 아키텍처**: DDD, CQRS 기반 확장 가능한 시스템 설계
- ✅ **DevOps 경험**: Kubernetes, ArgoCD를 활용한 자동화된 배포 파이프라인 구축
- ✅ **성능 최적화**: 쿼리 튜닝, 캐싱 전략으로 API 응답 시간 단축
- ✅ **대규모 데이터 처리**: Kafka 기반 비동기 메시징 및 실시간 데이터 파이프라인 구축
- ✅ **클라우드 운영**: AWS, NCLOUD, IDC 환경에서의 서비스 구축 및 운영 경험

---

## 💼 경력 요약

| 기간 | 회사 | 직급 | 주요 업무 |
|------|------|------|-----------|
| 2024.04 ~ 현재 | 에스아이에이(SIA) | 백엔드 개발자 | AI 위성 영상 분석, 리포트 자동화 플랫폼 |
| 2023.08 ~ 2024.04 | 와따에이아이 | GIS 엔지니어 | 물류 플랫폼, GIS 기반 서비스 |
| 2022.12 ~ 2023.08 | CityEyeLab | PL | CCTV·광선로 뷰어 솔루션 |
| 2021.03 ~ 2022.12 | 바이브컴퍼니 | 백엔드 개발자 | 디지털트윈, 메타버스 서비스 |
| 2020.06 ~ 2021.02 | 미소정보기술 | 웹 개발자 | 스마트시티 IoT 플랫폼 |
| 2017.10 ~ 2019.06 | IMT | 인프라 엔지니어 | 인프라 서버·보안 운영 |
| 2017.05 ~ 2017.10 | 국토연구원 | 인프라 엔지니어(인턴) | 인프라 서버·보안 운영 |

---

## 📚 기술 블로그

- 📝 [티스토리 블로그](https://dduckddack-2.tistory.com) - 개발 경험 및 기술 정리
- 📝 [노션 블로그](https://dev-giwon.notion.site/ce2318d46f3a4b66894ad04d1b20d986?pvs=4) - 프로젝트 회고 및 트러블슈팅

---

## 📈 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=giwon1130&show_icons=true&theme=radical&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=giwon1130&layout=compact&theme=radical&hide_border=true)

</div>

---

## 📫 연락처

- 📧 Email: gwim1130@naver.com
- 💼 GitHub: [@giwon1130](https://github.com/giwon1130)
- 📝 Blog: [티스토리](https://dduckddack-2.tistory.com) | [노션](https://dev-giwon.notion.site/ce2318d46f3a4b66894ad04d1b20d986?pvs=4)

---

<div align="center">

### "좋은 코드는 읽기 쉬운 코드이며, 좋은 시스템은 유지보수하기 쉬운 시스템입니다." 💡

</div>
