<div align="center">

# Giwon Im · 임기원

**Backend Platform Engineer**<br>
Kotlin · Java · Spring Boot · AI Integration · Geospatial Systems

인프라 운영부터 백엔드 플랫폼, AI 모델 연동과 공간 데이터까지 약 8년 동안 다뤄왔습니다.<br>
복잡한 요구를 API와 데이터 흐름으로 정리하고 운영 가능한 제품으로 연결합니다.

[![Email](https://img.shields.io/badge/Email-gwim1130@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gwim1130@naver.com)
[![Notion](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=notion&logoColor=white)](https://dev-giwon.notion.site/ce2318d46f3a4b66894ad04d1b20d986)
[![Blog](https://img.shields.io/badge/Blog-FF5722?style=flat-square&logo=blogger&logoColor=white)](https://dduckddack-2.tistory.com)

</div>

---

## Profile

- 인프라 운영 약 2년을 포함한 약 8년의 기술 경력
- Kotlin·Java·Spring Boot 기반 백엔드 설계와 운영
- 위성영상 AI, GIS·공간 데이터, 디지털트윈과 IoT 도메인 경험
- 장시간 비동기 작업, 외부 시스템 연동, 데이터 정합성과 장애 격리
- AWS·Docker·Kubernetes·Jenkins·ArgoCD 기반 배포와 운영
- 문제 정의부터 모바일·백엔드·배포까지 혼자 수행해 App Store 제품 3종 출시
- 직접 구현을 중심으로 소규모 팀의 요구사항·일정·품질도 조율할 수 있는 실무형 시니어·PL

## Selected Experience

### Prompt-based IOD for satellite imagery

- 기존 객체 또는 새 이미지를 비주얼 프롬프트로 사용하고 텍스트 프롬프트와 정책에 맞게 조합
- Triton 벡터화 서버와 인퍼런스 서버를 연결하고 결과 저장·지도 표시 API까지 구현
- 장시간 추론 요청의 재시도와 중복 방지, 프롬프트 적용 시점 정책 설계
- 기존 모델과 IOD 결과의 클래스 ID를 매핑하고 NMS로 결과를 결합
- 범용 `car` 탐지 결과를 `red car`, `blue car`처럼 사용자 의도에 맞게 보정

### Backend platform and data workflows

- 월간 약 30만 건 규모로 추정되는 변화탐지 객체·폴리곤 처리와 PDF·DOCX 리포트 자동 생성
- Kafka 기반 비동기 결과 처리, Polling·SSE 상태 전달과 재처리 흐름
- Python·FastAPI 라벨링 서버를 Kotlin·Spring Boot로 전환하고 실제 작업 시나리오로 검증
- 국내외 위성영상 공급사 3곳의 상이한 API를 공통 검색·주문·다운로드 흐름으로 통합
- Jira·GitHub·CI·ArgoCD를 연결한 Agentic 개발 흐름과 Human-in-the-loop 승인 규칙 구성

### Geospatial and infrastructure

- 실내 3D 디지털트윈의 Node.js GIS 서버를 Java·Spring Boot로 전환
- 실내 측위 현장 검증, 포인터 기반 최단 경로와 MongoDB 비정형 데이터 방어 처리
- LH 3기 신도시 가상체험과 B2C 디지털트윈 플랫폼의 3D·공간 데이터 백엔드 구현
- AWS Auto Scaling, Blue Green 무중단 배포와 Jenkins CI/CD 최초 도입
- 광선로·CCTV GIS 솔루션을 5인 팀 PL로 수행해 2차 납품까지 완료

## Shipped Products

세 제품 모두 기획, 디자인, React Native 앱, Kotlin·Spring Boot 백엔드, 인프라와 App Store 배포까지 혼자 수행했습니다.

| Product | Stack | What I built |
|---|---|---|
| **[Signal Desk](https://apps.apple.com/kr/app/signal-desk-%ED%88%AC%EC%9E%90-%EB%8C%80%EC%8B%9C%EB%B3%B4%EB%93%9C/id6770443767)** | Kotlin · Spring Boot · PostgreSQL · React Native · Gemini | KRX·네이버·CBOE VIX·FRED·뉴스를 통합하고 캐시·폴백·구조화 응답 검증을 적용한 AI 투자 대시보드 |
| **[Codie · 코디](https://apps.apple.com/kr/app/codie-ai-%EC%BD%94%EB%94%94/id6791064962)** | Kotlin · Spring Boot · React Native · Gemini Vision | 날씨·TPO·색 조화·피드백 기반 랭킹과 멀티모달 AI를 결합한 개인화 코디 추천 |
| **[Card Together · 카드투게더](https://apps.apple.com/kr/app/%EC%B9%B4%EB%93%9C%ED%88%AC%EA%B2%8C%EB%8D%94/id6792750711)** | Kotlin · Spring Boot · React Native · App Intents · Vision OCR | 카드 문자 자동화, SHA-256 중복 방지, 온디바이스 OCR과 가족 공동 예산 |

### In TestFlight

**곳곳** — 가본 곳과 가고 싶은 곳을 지도에 기록하는 로컬 우선 여행 도감입니다. 취향·방문 이력·계절·새 도시·다양성을 반영하는 설명 가능한 추천을 구현했고, 현재 실사용하며 UI·UX를 개선하고 있습니다.

출시 제품 외에도 복수의 iOS 제품을 TestFlight까지 구현·검증하며 아이디어를 빠르게 제품화하고 중단 여부를 판단했습니다.

## Tech Stack

**Backend**<br>
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

**Data & Messaging**<br>
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/-PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Infrastructure**<br>
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/-Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**Product & Geospatial**<br>
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/-React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/-Expo-000020?style=flat-square&logo=expo&logoColor=white)
![OpenLayers](https://img.shields.io/badge/-OpenLayers-1F6B75?style=flat-square&logo=openlayers&logoColor=white)

## GitHub Activity

<div align="center">

![Giwon's GitHub stats](https://github-readme-stats.vercel.app/api?username=giwon1130&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&hide_rank=true&include_all_commits=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=giwon1130&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

<div align="center">
  <sub><a href="https://dev-giwon.notion.site/ce2318d46f3a4b66894ad04d1b20d986">Portfolio</a> · <a href="https://dduckddack-2.tistory.com">Blog</a> · <a href="mailto:gwim1130@naver.com">Email</a></sub>
</div>
