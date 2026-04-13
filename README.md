# 제품 개발자 임기원

문제를 기능 단위가 아니라 서비스와 제품 단위로 구조화하고, 실제로 동작하는 형태까지 빠르게 연결하는 제품 개발자입니다.

Kotlin, Spring Boot, PostgreSQL/PostGIS, Redis, Kafka 기반 환경에서 조회 성능 개선, 비동기 처리 구조 설계, 운영 안정화 작업을 해왔습니다.  
백엔드 구현이 강점이지만, 최근에는 `giwon-home` 같은 허브와 `SignalDesk`, `RouteOps`, `MetroPulse`, `ShelterNow`, `HomeHarmony`, `TripMemo`, `emergency-room`, `giwon-assistant-api` 같은 독립 서비스를 직접 만들며 제품 관점의 공개 저장소를 정리하고 있습니다.

요즘은 코드를 많이 작성하는 것보다 문제를 정확히 정의하고, 빠르게 실험하고, 실제로 검증해 개선하는 능력이 더 중요하다고 보고 있습니다.  
그래서 AI 도구를 활용해 요구사항 정리 -> 실험 -> 검증 -> 개선 사이클을 짧게 가져가며 제품을 다듬고 있습니다.

실무 대표 프로젝트는 보안상 공개 저장소로 제공할 수 없어, 문제, 역할, 해결 방식, 성과 중심으로 노션 포트폴리오에 정리했습니다.

<div align="center">

[![Email](https://img.shields.io/badge/Email-gwim1130@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gwim1130@naver.com)
[![Blog](https://img.shields.io/badge/Blog-dduckddack--2-FF5722?style=flat-square&logo=blogger&logoColor=white)](https://dduckddack-2.tistory.com)
[![Notion](https://img.shields.io/badge/Notion-Portfolio-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/dev-giwon/ce2318d46f3a4b66894ad04d1b20d986)

</div>

## 핵심 강점
- 문제를 제품 단위로 정리하고 실제 서비스 형태로 연결
- 모호한 요구사항을 문제 정의, 우선순위, 실행 단위로 구조화
- AI 도구를 활용해 실험-검증 사이클을 단축하고 의사결정 속도 향상
- 대량 데이터 처리와 조회 성능 개선
- Kafka, Redis 기반 비동기 처리 구조 설계
- PostGIS 기반 공간 데이터 처리와 GIS 서비스 개발
- 개인 생산성과 공공 데이터 영역에서 독립 서비스 MVP를 빠르게 구현

## 대표 실무 경험
- FastAPI 기반 라벨링 툴 백엔드를 Kotlin Spring Boot로 전환하며 팀 주력 스택으로 통합
- Kafka 기반 비동기 처리 구조로 변화탐지·객체탐지 데이터 처리와 리포트 자동화 파이프라인 구축
- 위성·항공 이미지 분석 플랫폼에서 공간 데이터 조회 구조 개선과 운영 안정화 작업 수행
- GIS 기반 서비스와 디지털트윈 플랫폼에서 백엔드 개발, 배포, 운영 경험 축적

## 대표 공개 프로젝트
- [giwon-home](https://github.com/giwon1130/giwon-home)
  공개 프로젝트 허브, 자기소개 페이지, 독립 서비스 진입점을 제공하는 프론트엔드 허브
- [giwon-home-api](https://github.com/giwon1130/giwon-home-api)
  허브에서 사용하는 공개 프로필/프로젝트 카탈로그 API 서버
- [giwon-assistant-api](https://github.com/giwon1130/giwon-assistant-api)
  아침 브리핑 자동 생성, 뉴스/날씨 요약, 아이디어 저장과 브리핑 이력 관리를 제공하는 개인용 AI 비서 API
- [signal-desk](https://github.com/giwon1130/signal-desk)
  한국/미국 시장을 분리해 차트, 수급, 뉴스 군집화, 포트폴리오, AI 추천, 모의투자를 제공하는 시장 인텔리전스 서비스
- [signal-desk-api](https://github.com/giwon1130/signal-desk-api) / [signal-desk-web](https://github.com/giwon1130/signal-desk-web) / [signal-desk-app](https://github.com/giwon1130/signal-desk-app)
  시장 데이터 API, 웹 대시보드, 모바일 컴패니언 앱으로 분리한 금융 제품군
- [route-ops-api](https://github.com/giwon1130/route-ops-api) / [route-ops-web](https://github.com/giwon1130/route-ops-web)
  호출형 이동 서비스 운영자를 위해 권역 수요, 차량 상태, 재배치 추천, 운영 브리핑을 제공하는 DRT 운영 콘솔
- [metro-pulse-backend](https://github.com/giwon1130/metro-pulse-backend) / [metro-pulse-frontend](https://github.com/giwon1130/metro-pulse-frontend)
  실시간 지하철 도착정보와 시간대 혼잡도를 함께 제공하는 교통 서비스
- [shelter-now-backend](https://github.com/giwon1130/shelter-now-backend) / [shelter-now-frontend](https://github.com/giwon1130/shelter-now-frontend)
  현재 위치 기준으로 가까운 대피소와 쉼터를 탐색하는 공공 안전 서비스
- [emergency-room-backend](https://github.com/giwon1130/emergency-room-backend) / [emergency-room-frontend](https://github.com/giwon1130/emergency-room-frontend)
  공공 응급의료 API, PostGIS, Redis 기반으로 주변 응급실 병상 현황을 제공하는 응급 의료 탐색 서비스
- [HomeHarmony](https://github.com/giwon1130/HomeHarmony)
  직주근접·예산·가족형 추천 모드와 생활권 추천 점수를 함께 제공하는 주거 선택 지원 프론트엔드 MVP
- [TripMemo](https://github.com/giwon1130/TripMemo)
  여행(trip), 장소, 메모를 함께 묶고 검색·필터·대시보드·타임라인 조회를 제공하는 여행 기록 서비스 백엔드

## 공개 저장소 방향
공개 저장소는 실무 프로젝트 원본을 올리는 공간이 아니라, 개인 허브, 독립 서비스, 템플릿, 실험용 프로젝트를 통해 문제 정의 -> 검증 -> 개선 과정을 제품 단위로 정리하는 용도로 사용하고 있습니다.

- [giwon-home](https://github.com/giwon1130/giwon-home)
- [giwon-home-api](https://github.com/giwon1130/giwon-home-api)
- [giwon-assistant-api](https://github.com/giwon1130/giwon-assistant-api)
- [signal-desk](https://github.com/giwon1130/signal-desk)
- [signal-desk-api](https://github.com/giwon1130/signal-desk-api)
- [signal-desk-web](https://github.com/giwon1130/signal-desk-web)
- [signal-desk-app](https://github.com/giwon1130/signal-desk-app)
- [route-ops-api](https://github.com/giwon1130/route-ops-api)
- [route-ops-web](https://github.com/giwon1130/route-ops-web)
- [metro-pulse-backend](https://github.com/giwon1130/metro-pulse-backend)
- [metro-pulse-frontend](https://github.com/giwon1130/metro-pulse-frontend)
- [shelter-now-backend](https://github.com/giwon1130/shelter-now-backend)
- [shelter-now-frontend](https://github.com/giwon1130/shelter-now-frontend)
- [emergency-room-backend](https://github.com/giwon1130/emergency-room-backend)
- [emergency-room-frontend](https://github.com/giwon1130/emergency-room-frontend)
- [HomeHarmony](https://github.com/giwon1130/HomeHarmony)
- [TripMemo](https://github.com/giwon1130/TripMemo)
- [base-spring-template](https://github.com/giwon1130/base-spring-template)

## 기술 키워드
- Backend: Kotlin, Java, Spring Boot
- Data: PostgreSQL, PostGIS, Redis, MongoDB
- Messaging: Kafka, RabbitMQ
- Infra: Docker, Kubernetes, Jenkins, GitHub Actions
- GIS: PostGIS, GeoServer, QGIS, GDAL

## 링크
- [Notion Portfolio](https://www.notion.so/dev-giwon/ce2318d46f3a4b66894ad04d1b20d986)
- [Blog](https://dduckddack-2.tistory.com)
