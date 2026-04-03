# 제품 개발자 임기원

문제를 서비스와 제품 단위로 구조화하고, 실제로 동작하는 형태까지 연결하는 제품 개발자입니다.

Kotlin, Spring Boot, PostgreSQL/PostGIS, Redis, Kafka 기반 환경에서
조회 성능 개선, 비동기 처리 구조 설계, 운영 안정화 작업을 수행해왔습니다.
백엔드 구현에 강점이 있지만, 최근에는 `giwon-home` 같은 허브와
`emergency-room`, `giwon-assistant-api`, `HomeHarmony`, `TripMemo` 같은 독립 서비스들을 직접 만들며
제품 관점에서 공개 저장소를 정리하고 있습니다.
최근에는 `MetroPulse`처럼 실시간 지하철 도착정보 OpenAPI와 혼잡도 데이터를 함께 다루고, 출퇴근 빠른 보기까지 제공하는 교통 서비스도 새로 확장하고 있습니다.
실무 대표 프로젝트는 보안상 공개 저장소로 제공할 수 없어
문제, 역할, 해결 방식, 성과 중심으로 노션 포트폴리오에 정리했습니다.

최근 공개 저장소는 `giwon-home` 허브, `emergency-room`, `giwon-assistant-api`, `HomeHarmony`, `TripMemo`, `MetroPulse` 같은 독립 서비스들을 중심으로 정리하고 있습니다.

<div align="center">

[![Email](https://img.shields.io/badge/Email-gwim1130@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gwim1130@naver.com)
[![Blog](https://img.shields.io/badge/Blog-dduckddack--2-FF5722?style=flat-square&logo=blogger&logoColor=white)](https://dduckddack-2.tistory.com)
[![Notion](https://img.shields.io/badge/Notion-Portfolio-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/dev-giwon/ce2318d46f3a4b66894ad04d1b20d986)

</div>

## 핵심 강점
- 문제를 제품 단위로 정리하고 실제 서비스 형태로 연결
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
- [emergency-room-frontend](https://github.com/giwon1130/emergency-room-frontend)
  현재 위치 기반으로 주변 응급실 병상 현황을 지도와 리스트로 보여주는 프론트엔드
- [emergency-room-backend](https://github.com/giwon1130/emergency-room-backend)
  공공 응급의료 API, PostGIS, Redis 기반으로 위치 조회와 상태 요약을 제공하는 백엔드
- [HomeHarmony](https://github.com/giwon1130/HomeHarmony)
  직주근접·예산·가족형 추천 모드와 생활권 추천 점수를 함께 제공하는 주거 선택 지원 프론트엔드 MVP
- [TripMemo](https://github.com/giwon1130/TripMemo)
  여행(trip), 장소, 메모를 함께 묶고 검색·필터·대시보드·타임라인 조회를 제공하는 여행 기록 서비스 백엔드
- [metro-pulse-backend](https://github.com/giwon1130/metro-pulse-backend)
  실시간 지하철 도착정보 OpenAPI와 30분 단위 평균 혼잡도를 함께 제공하고, 즐겨찾기·출퇴근 빠른 보기를 갖춘 교통 서비스 백엔드

## 공개 저장소 방향
공개 저장소는 실무 프로젝트 원본을 올리는 공간이 아니라,
개인 허브, 독립 서비스, 템플릿, 실험용 프로젝트를 정리하는 용도로 사용하고 있습니다.

- [giwon-home](https://github.com/giwon1130/giwon-home)
- [giwon-home-api](https://github.com/giwon1130/giwon-home-api)
- [giwon-assistant-api](https://github.com/giwon1130/giwon-assistant-api)
- [emergency-room-frontend](https://github.com/giwon1130/emergency-room-frontend)
- [emergency-room-backend](https://github.com/giwon1130/emergency-room-backend)
- [HomeHarmony](https://github.com/giwon1130/HomeHarmony)
- [base-spring-template](https://github.com/giwon1130/base-spring-template)
- [TripMemo](https://github.com/giwon1130/TripMemo)

## 기술 키워드
- Backend: Kotlin, Java, Spring Boot
- Data: PostgreSQL, PostGIS, Redis, MongoDB
- Messaging: Kafka, RabbitMQ
- Infra: Docker, Kubernetes, Jenkins, GitHub Actions
- GIS: PostGIS, GeoServer, QGIS, GDAL

## 링크
- [Notion Portfolio](https://www.notion.so/dev-giwon/ce2318d46f3a4b66894ad04d1b20d986)
- [Blog](https://dduckddack-2.tistory.com)
