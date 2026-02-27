

<div align="center">
  <img src="https://github.com/user-attachments/assets/807a5735-e104-4bbe-adf5-b7a47830b0cf" width="400"/>
</div>


## 한 줄 소개

실시간 배송 추적·재고 공유·권한 기반 중앙 관리를 통합한 B2B 직영점 운영 플랫폼

---

## 📋 프로젝트 개요

| 항목 | 내용 |
|------|------|
| **진행 기간** | 2025.09 ~ 2025.10 |
| **팀 인원** | 4명 |
| **내 역할** | DB 설계(ERD/요구사항), POS·공지·이벤트 UI 설계 · UI 품질 개선, Git Actions 관리, 코딩 컨벤션 확립 |
| **핵심 기술** | Vue 3, MariaDB, GitHub Actions, Gemini CLI, Claude CLI |

---

## 🕵️ 팀원 소개

<table align="center">
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/kbw07"><img src="https://github.com/user-attachments/assets/706e1875-8a3d-4d3e-9a19-d344d6866f23" width="100px;" alt=""/><br /><sub><b>강병욱</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/flionme"><img src="https://github.com/user-attachments/assets/08e896f8-c18f-454a-a44a-2337f585e77f" width="100px;" alt=""/><br /><sub><b>김성인</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/David9733"><img src="https://github.com/user-attachments/assets/4d6ad9a1-ac42-4f36-9259-2b988493cf85" width="100px;" alt=""/><br /><sub><b>이시욱</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/raccoon-coding"><img src="https://github.com/user-attachments/assets/90a33761-0bd8-4b73-a12a-1e24f0c5a6a9" width="100px;" alt=""/><br /><sub><b>최민성</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

---

## 🎯 프로젝트 목적

"데이터로 연결하고, 실시간으로 관리한다."

본사와 매장을 하나의 네트워크로 연결하여, 주문·재고·물류·매출·고객 데이터를 실시간으로 통합 관리하는<br>B2B 직영점 운영 솔루션입니다.

| 구분 | 내용 |
|------|------|
| **기존 방식** | 점포별로 재고·POS·고객 데이터가 분산되어 본사가 통합 현황을 파악하기 어려움<br>본사와 가맹점 간 소통 채널 부재로 의사결정 지연 |
| **본 서비스** | GPS 물류 실시간 추적, 고객 데이터 분석, 실시간 소통을 하나의 플랫폼으로 통합 |
| **기대 효과** | 재고 손실 최소화, 장애 대응 속도 향상, 본사와 매장 간 정보 비대칭 해소 |

---

## 🙋 내 기여

### 1단계 · Database

- 요구사항 명세서 작성 및 기능 우선순위 정의
- 팀원별 역량 수준과 선호를 파악하여 파트 배분
- IntelliJ ERD 자동 생성 기능으로 Java 엔티티 기반 ERD 추출

### 2단계 · Frontend

- 템플릿 선정 및 팀 UI 기준 수립(벤치마킹 : 무신사)
- 역할 기반 접근 제어 설계
- Figma 디자인 작업
- POS 앱 설계(벤치마킹 : Toss Pos)
- 공지·프로모션 UI 구현
- 역할별 시나리오 점검을 통한 UI 오류 이슈화 및 품질 개선

### 3단계 · 협업

- CRUD 가이드라인 보완
- WBS 일정 구조화
- GitHub Actions 일정관리
- 팀 코딩 컨벤션 문서화 및 공유
- 개인 브랜치 전략 수립
- GitHub Pull request 2인 이상 승인 후 병합 규칙 적용

---

## ✨ 주요 기능

- GPS 실시간 추적 및 매장 도착 예상 시간 제공
- 매장별 POS 상태 조회 및 고장 접수·처리 상태 추적
- 연령·성별·카테고리별 고객 매출 분석 및 인기상품 랭킹
- 본사와 가맹점 재고 실시간 동기화 및 발주
- 본사와 가맹점 실시간 메신저 및 공지 전달
- 쿠폰 생성·관리 및 프로모션 등록·조회

---

## 👥 역할별 권한

| 역할 | 접근 범위 |
|------|---------|
| **본사** | 서브관리자 기능 전체 포함 + 계정·권한 관리 |
| **서브관리자** | 전체 매장 현황 조회, 발주 승인, 배송 기사 배정, GPS 배송 추적, POS 상태 점검, 고객·매출 분석,<br> 재고 및 상품 관리, 프로모션·쿠폰 생성·관리, 공지 발송, 메신저, AS 처리 |
| **가맹점** | 내 매장 재고 조회 및 매출 조회, 발주 요청, AS 신청, 메신저, 프로모션·공지 조회 |
| **POS기** | 상품 선택·결제(일반/카드/회원), 결제 내역 조회, 공지 조회 |

---

## 📐 코딩 컨벤션

### Git 전략

- 브랜치 구조: main / release / develop / {이름}/기능브랜치
- 커밋 태그: [FEAT] 기능 완료 / [DEV] 개발 중 / [REFA] 리팩토링 / [DOC] 문서 / [HOT] 핫픽스
- 개발 완료 시 develop 으로 PR → 아침 코드 리뷰 후 병합
- develop → release merge / release → main merge

### Frontend

- CSS 파일은 assets에 작성
- components는 버튼·헤더·푸터 등 공통 UI (Bootstrap 기반)
- mainRouter → 도메인별 개별 라우터 파일 분리
- Axios plugin 사용, API 변수명은 도메인 + Api 형식
- 페이지네이션 적용 (무한 스크롤 사용 안 함)
- script / template / styles 순서 유지

### Backend

- Domain별 Controller / Service / Repository / Model 구조
- utils: 메서드 단위로 호출해서 사용하는 도구 모음
- common: 상수·클래스 자체를 사용하는 공통 자원(Config는 common에 위치)
- 상수는 추상 클래스로 관리, 대문자 표기
- @NoArgsConstructor(access = AccessLevel.PROTECTED) 접근 레벨 설정
- Setter 사용 금지, 메서드로 값 변경
- Builder 패턴 사용
- id는 Integer 고정 (null 허용)
- Model 내부에 Entity / Dto 분리
- Dto 명칭은 Res / Req 로 통일 (Dto 접미사 제거)
- Dto 변환 메서드 toEntity / toDto 고정
- BaseResponse / BaseException / GlobalExceptionHandler 공통 처리
- else → 예외 처리로 끝냄 (분기 마지막은 반드시 예외를 던짐)
- Exception Message는 도메인별 Enum으로 관리
- Service 클래스에 @Transactional(readOnly = true) 기본 적용, DB 변경 메서드에만 @Transactional 추가
- 메서드 간 빈 줄로 문단 개행
- CamelCase 적용

---

## 🛠️ 기술 스택

**DB** : MariaDB

**Frontend** : Vue.js 3.4.21(UI 프레임워크) · Vue Router 4.3.2(SPA 라우팅) · Pinia 2.1.7(전역 상태 관리) · Axios 1.12.2(HTTP 통신) · @stomp/stompjs 7.2.0(WebSocket 메신저) · Leaflet 1.9.4(GPS 지도 시각화) · ApexCharts 1.5.3(데이터 차트) · Bootstrap 5.3.3(UI 컴포넌트) · Vite 5.2.0(빌드 도구)

**Collaboration** :  Git, GitHub, Figma, Discord

![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

---

## 🗄️ DB 아키텍처

### ERD

<details>
<summary>📊 ERD 보기</summary>

![HypeLink ERD](./doc/hypelinkERD.png)

</details>



---

---

## 🤔 기술 선택 이유

<details>
<summary>Database — MariaDB</summary>

- MySQL과 완전 호환되는 오픈소스 RDBMS로 팀 내 학습 비용이 낮음
- 매장·재고·발주·고객 데이터가 명확한 관계(FK)로 연결되는 구조에 관계형 DB가 적합하다고 판단
- QueryDSL과 결합하여 복합 조건 통계 쿼리(연령별 매출, 재고 회전율 등)를 타입 안전하게 작성

</details>

<details>
<summary>Frontend — Vue 3 + Pinia</summary>

- **Vue 3 Composition API**: 기능 단위로 로직을 분리하여 역할별 대시보드(AdminDashboard / StoreOwnerDashboard)처럼 재사용 컴포넌트 구성이 용이
- **Pinia**: Vuex 대비 간결한 API와 DevTools 지원으로 인증(auth), 권한(permissions), 모달(modal), 토스트(toast) 등 복수 스토어를 명확히 분리해 관리
- **@stomp/stompjs**: SockJS 없이도 WebSocket 위에서 구독·발행 패턴을 구현할 수 있어 본사–가맹점 실시간 메신저에 채택
- **Leaflet**: 순수 JS 지도 라이브러리로 번들 크기가 작고, GPS 좌표 기반 마커/경로 렌더링이 간단

</details>

<details>
<summary>Collaboration — GitHub Flow + 문서화 체계</summary>

- `main` / `develop` / `{이름}/BRANCH` 3단계 브랜치 전략으로 기능 개발과 통합을 분리
- PR 기반 코드 리뷰로 병합 전 오류 사전 차단
- `/doc` 폴더에 기획서·ERD·WBS·피그마·아키텍처를 통합 관리하여 팀원 간 정보 공유 일원화

</details>

---

## 🔑 핵심 구현 포인트

| 항목 | 위치 | 설명 |
|------|------|------|
| 역할 기반 접근 제어 | `src/stores/permissions.js` | ADMIN / MANAGER / BRANCH_MANAGER 3개 역할별 허용 라우트 목록을 Pinia 스토어로 중앙 관리; 라우터 가드에서 `canAccess()` 호출로 페이지 접근 차단 |
| 도메인 분리 라우팅 | `src/router/routes/` (18개 파일) | 기능별 라우트 파일을 분리(`inventoryRoutes`, `asRoutes` 등)하여 단일 파일 비대화 방지 |
| WebSocket 메신저 | `src/views/MessengerView.vue` | STOMP 프로토콜로 채널 구독, 본사·가맹점 간 실시간 요청/응답; 연결 해제 시 자동 재연결 처리 |
| GPS 배송 추적 지도 | `src/views/ShipmentTrackingView.vue` | 기사별 스마트 디바이스에서 GPS 좌표를 수신하여 Leaflet 지도에 실시간 마커 표시; Geocoding API로 매장 주소→좌표 변환 후 현재 위치 기준 도착 예상 시간(ETA) 계산 |
| 통합 분석 대시보드 | `src/views/analytics/` | 매출·주문·재고·상품·매장 5개 분석 탭, ApexCharts 차트 컴포넌트 재사용 구조 |
| POS 결제 처리 | `hypelinkPos/src/views/POSView.vue` | PortOne Browser SDK(`@portone/browser-sdk 0.0.9`)로 일반/회원 결제 처리; uuid로 주문 고유 ID 생성 |
| ERD 기반 스키마 설계 | `doc/hypelinkERD.png` | 요구사항 정의서 기반 엔티티 도출 → 정규화 → FK/인덱스 설계 → ERD 문서화 |

### 주요 화면

<details>
<summary>📺 관리자 대시보드 화면 보기</summary>

#### 본사 로그인
![본사 관리자](https://github.com/user-attachments/assets/3d5406f6-9176-4b58-b819-286af2814787)

#### 고객 분석
![고객분석](https://github.com/user-attachments/assets/5c9d7b18-90b7-4ba4-a467-02744d73388d)

#### 전체 배송 추적
![전체배송추척](https://github.com/user-attachments/assets/dbcec5e0-5382-4e53-9e7b-87846d9f0b49)

#### AS 접수 처리
![AS](https://github.com/user-attachments/assets/1c9672ca-952e-4b9a-8f49-81fa4743d3b6)

</details>

<details>
<summary>💳 POS 단말기 화면 보기</summary>

#### POS 결제
![pos_gif](https://github.com/user-attachments/assets/086e6512-c76e-430a-8061-11aacb365e50)

#### 회원 결제
![포스기 회원 결제](https://github.com/user-attachments/assets/637100dd-1409-4bb3-90f7-d89f04595ca8)

#### 결제 내역
![포스기 결제내역](https://github.com/user-attachments/assets/7ee47852-b185-4ad7-8424-19bc6b10fbf1)

</details>

---

## 🔧 트러블슈팅 / 개선 경험

### DB 설계 — (구체적 사례 입력 필요)

| 구분 | 내용 |
|------|------|
| **문제** | (예: 재고 테이블 설계 시 매장별/창고별 재고를 단일 테이블로 구성했을 때 쿼리 복잡도 증가) |
| **원인** | (예: 엔티티 구분 없이 타입 컬럼으로 분기 → JOIN 시 Full Scan 발생) |
| **해결** | (예: 매장재고(StoreInventory)와 창고재고(WarehouseInventory)를 별도 테이블로 분리, 인덱스 추가) |
| **결과** | (예: 쿼리 단순화 및 가독성 향상 / 측정 수치 있으면 기재, 없으면 생략) |

### Frontend — 역할별 권한 관리 누락 문제

| 구분 | 내용 |
|------|------|
| **문제** | 가맹점 계정으로 본사 전용 URL에 직접 접근 시 권한 오류 없이 화면이 노출됨 |
| **원인** | 사이드바에서 메뉴를 숨기는 것만으로 접근 제어를 구현했고, 라우터 가드에 역할 검증이 없었음 |
| **해결** | `permissions.js`에 역할별 허용 라우트 목록을 정의하고, `router.beforeEach`에서 `canAccess()` 호출로 미인가 접근 시 대시보드로 리다이렉트 |
| **결과** | URL 직접 입력으로 인한 권한 우회 차단; 역할 추가 시 `permissions.js` 수정만으로 확장 가능한 구조 확보 |

### 협업 — 이슈 트래킹 도구 선택

| 구분 | 내용 |
|------|------|
| **문제** | 팀 이슈 및 일정 관리를 위해 Jira 도입을 검토했으나, 초기 설정 복잡도와 팀 학습 비용이 높아 실제 개발에 집중하기 어려운 상황 |
| **원인** | Jira는 대규모 팀·장기 프로젝트에 최적화된 도구로, 단기 프로젝트에서는 오버엔지니어링이 될 수 있다고 판단 |
| **해결** | GitHub Actions와 PR 기반 워크플로우로 대체 — 브랜치 전략, 커밋 컨벤션, 코드 리뷰 프로세스를 GitHub 내에서 통합 관리 |
| **결과** | 별도 도구 없이 GitHub 단일 환경에서 이슈 트래킹·CI·코드 리뷰를 일원화하여 팀 협업 효율 향상 |

---

## 🚀 실행 및 테스트

### 대시보드 앱 (`hypelinkMain`)

```bash
cd hypelinkMain
npm install
npm run dev       # 개발 서버 (http://localhost:5173)
npm run build     # 프로덕션 빌드
```

### POS 앱 (`hypelinkPos`)

```bash
cd hypelinkPos
npm install
npm run dev       # 개발 서버
npm run build     # 프로덕션 빌드
```

### 테스트 계정

| 역할 | ID | PW |
|------|----|----|
| 본사 (ADMIN) | `hq@company.com` | `1234` |
| 서브관리자 (MANAGER) | `manager@hypelink.com` | `1234` |
| 가맹점 (BRANCH_MANAGER) | `gangnam@hypelink.com` | `1234` |
| POS 단말기 | `pos.gangnam.01@hypelink.com` | `1234` |

### Docker (Nginx)

```bash
docker build -t hypelink-front .
docker run -p 80:80 hypelink-front
```

---

## 📎 참고자료

| 자료 | 링크 |
|------|------|
| 피그마 디자인 | [Figma 바로가기](https://www.figma.com/design/apT7cRFWE4TS6WcdayD1Tn/HypeLink?node-id=0-1&p=f&t=s8E79kwSqskjhKOT-0) |
| 피그마 캡처 | [doc/Fiqma.png](./doc/Fiqma.png) |
| ERD | [doc/hypelinkERD.png](./doc/hypelinkERD.png) |
| 요구사항 정의서 | [doc/HypeLink 요구사항 정의서.pdf](./doc/HypeLink%20요구사항%20정의서.pdf) |
| 기획서 | [doc/HypeLink 기획서.pdf](./doc/HypeLink%20기획서.pdf) |
| WBS | [doc/WBS.pdf](./doc/WBS.pdf) |
| V1 시스템 아키텍처 | [doc/시스템 아키텍처.png](./doc/시스템%20아키텍처.png) |
| V2 MSA 아키텍처 | [doc/MSA 시스템 아키텍처.png](./doc/MSA%20시스템%20아키텍처%20.png) |
| CI/CD 파이프라인 문서 | [GitHub Wiki](https://github.com/beyond-sw-camp/be17-fin-MeshX-HypeLink-FE/wiki/HypeLink-CI-CD-%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8-%EB%AC%B8%EC%84%9C) |
| 대시보드 서비스 | [meshx.store](https://www.meshx.store) |
| POS 서비스 | [meshx.shop](https://www.meshx.shop) |
