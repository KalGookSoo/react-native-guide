# React Native 프로젝트 가이드

## 프로젝트 개요

이 프로젝트는 React Native에 관한 내용을 기반한 프로젝트 구성 가이드 및 애플리케이션 개발에 대한 전략과 구현 방법을 다루는 문서입니다.

독자는 타입스크립트로 구현한 리액트 개발자를 대상으로 하며, 구현 코드는 간략하게 제공하고 대부분 다이어그램(Mermaid)으로 설명합니다.

## 목차

### 1부: React Native 시작하기

#### 1장. React Native 소개
- [1-1. React Native란 무엇인가](chapters/01-1_what_is_react_native.md)
- [1-2. React Native의 장단점](chapters/01-2_pros_and_cons.md)
- [1-3. 개발 환경 구축](chapters/01-3_setup_development_environment.md)

#### 2장. 프로젝트 구조와 아키텍처
- [2-1. React Native 프로젝트 구조 이해하기](chapters/02-1_project_structure.md)
- [2-2. 폴더 구조 설계 전략](chapters/02-2_folder_structure_strategy.md)
- [2-3. Redux Toolkit 기반 프로젝트 구성](chapters/02-3_redux_toolkit_project_setup.md)

### 2부: 네비게이션과 라우팅

#### 3장. React Navigation
- [3-1. React Navigation 설정](chapters/03-1_react_navigation_setup.md)
- [3-2. Stack, Tab, Drawer 네비게이터 구현](chapters/03-2_navigator_implementation.md)
- [3-3. 네비게이션과 Redux 통합](chapters/03-3_navigation_redux_integration.md)

### 3부: Redux Toolkit 전역 상태 관리

#### 4장. Redux Toolkit 핵심
- [4-1. Store 설정과 Slice 패턴](chapters/04-1_store_and_slice.md)
- [4-2. RTK Query로 API 통신](chapters/04-2_rtk_query.md)
- [4-3. Redux Middleware와 비동기 처리](chapters/04-3_middleware_async.md)

#### 5장. Java API 서버 연동
- [5-1. REST API 통신 구조 설계](chapters/05-1_rest_api_architecture.md)
- [5-2. RTK Query와 Java Spring Boot 연동](chapters/05-2_rtk_query_spring_integration.md)
- [5-3. 인증 토큰 관리와 인터셉터](chapters/05-3_auth_token_interceptor.md)

### 4부: 네이티브 기능 활용

#### 6장. 디바이스 API
- [6-1. 카메라와 이미지 처리](chapters/06-1_camera_image.md)
- [6-2. 위치 정보와 지도 연동](chapters/06-2_location_maps.md)
- [6-3. 푸시 알림 구현](chapters/06-3_push_notifications.md)

#### 7장. 네이티브 모듈
- [7-1. 네이티브 모듈 이해와 활용](chapters/07-1_native_modules_usage.md)
- [7-2. iOS 네이티브 기능 브릿지](chapters/07-2_ios_native_bridge.md)
- [7-3. Android 네이티브 기능 브릿지](chapters/07-3_android_native_bridge.md)

### 5부: 성능 최적화

#### 8장. 렌더링 최적화
- [8-1. 대용량 리스트 최적화](chapters/08-1_large_list_optimization.md)
- [8-2. 이미지 로딩과 캐싱 전략](chapters/08-2_image_loading_caching.md)
- [8-3. Redux 성능 최적화 패턴](chapters/08-3_redux_performance.md)

#### 9장. 앱 성능 모니터링
- [9-1. 성능 프로파일링과 메트릭](chapters/09-1_performance_profiling.md)
- [9-2. 메모리 누수 감지와 해결](chapters/09-2_memory_leak_detection.md)
- [9-3. 번들 최적화와 코드 스플리팅](chapters/09-3_bundle_optimization.md)

### 6부: 테스트와 품질 관리

#### 10장. 테스트 전략
- [10-1. Redux 로직 테스트](chapters/10-1_redux_testing.md)
- [10-2. API 통신 모킹과 테스트](chapters/10-2_api_mocking_testing.md)
- [10-3. E2E 테스트 자동화](chapters/10-3_e2e_automation.md)

### 7부: 배포와 운영

#### 11장. 빌드와 배포
- [11-1. iOS 앱 스토어 배포](chapters/11-1_ios_appstore_deployment.md)
- [11-2. Android Play 스토어 배포](chapters/11-2_android_playstore_deployment.md)
- [11-3. CodePush를 통한 핫픽스](chapters/11-3_codepush_hotfix.md)

#### 12장. CI/CD와 자동화
- [12-1. GitHub Actions CI/CD 구축](chapters/12-1_github_actions_cicd.md)
- [12-2. 자동화된 테스트와 배포 파이프라인](chapters/12-2_automated_pipeline.md)
- [12-3. 버전 관리와 릴리즈 전략](chapters/12-3_version_release_strategy.md)

### 8부: 실전 프로젝트

#### 13장. 아키텍처 설계
- [13-1. Java API 서버 연동 아키텍처](chapters/13-1_java_api_architecture.md)
- [13-2. Redux 기반 데이터 플로우 설계](chapters/13-2_redux_data_flow.md)
- [13-3. 확장 가능한 프로젝트 구조](chapters/13-3_scalable_structure.md)

#### 14장. 핵심 기능 구현
- [14-1. JWT 인증 시스템](chapters/14-1_jwt_authentication.md)
- [14-2. 실시간 데이터 동기화](chapters/14-2_realtime_sync.md)
- [14-3. 오프라인 모드와 데이터 캐싱](chapters/14-3_offline_caching.md)

#### 15장. 고급 기능
- [15-1. 파일 업로드와 다운로드](chapters/15-1_file_upload_download.md)
- [15-2. 백그라운드 작업 처리](chapters/15-2_background_tasks.md)
- [15-3. 딥링킹과 유니버설 링크](chapters/15-3_deep_linking.md)

