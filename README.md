# 📦 슈박스 Spring Boot 웹 프로젝트 (Shoebox)

> 온라인 신발 쇼핑몰을 위한 **Full-stack 웹 애플리케이션**  
> 사용자 친화적인 UI와 안정적인 백엔드 아키텍처를 통해  
> 상품 검색부터 결제까지 원활한 경험을 제공하며,
상품·회원·주문을 관리할 수 있는 관리자 페이지도 포함된 프로젝트입니다.

---

## ✨ 프로젝트 개요
- **프로젝트 기간**: 2025.05.12 ~ 2025.05.23 (2주)
- **개발 형태**: 팀 프로젝트 (8인)
- **담당 업무**: 프론트엔드 메인 페이지, 관리자 페이지 프론트& 백엔드 회원관리 기능 개발, UI/UX 기획 참여

---

## 🔧 기술 스택 & 개발 환경
- **Frontend**: Thymeleaf, HTML5, CSS3, JavaScript  
- **Backend**: Java (JDK 17), Spring Boot 3.4.5, Spring Security, MyBatis, JPA  
- **Database**: Oracle XE 18c, 공공 API  
- **Version Control**: GitHub, Git Flow  
- **Tools & IDE**: IntelliJ IDEA, STS4, Eclipse, VS Code, Gradle, SQL Developer, Figma, Photoshop
- **OS**: Windows 11

---

## 🚀 서비스 기능 요약

### 1. 계정 & 프로필
- 이메일, 소셜 로그인 지원
- 비밀번호 재설정 / 아이디 찾기
- 개인 프로필: 주문 내역, 적립금·쿠폰, 리뷰/Q&A 기록 확인 가능

### 2. 쇼핑 여정
1. **탐색하기**  
   - 카테고리 / 브랜드 / 성별 / 연령대 별 상품 필터  
   - 정렬 옵션(신상품, 할인율, 인기순) 제공  
2. **상품 살펴보기**  
   - 이미지 슬라이드, 옵션(색상·사이즈) 선택, 재고 확인  
   - 실구매자 후기, 평점, Q&A 열람 가능  
3. **장바구니 & 위시리스트**  
   - 선택 상품 담기 / 삭제 / 수량 변경  
   - 장바구니에서 즉시 주문 가능  

### 3. 결제 & 배송
- 다양한 결제수단 (카드, 간편결제, 무통장입금)  
- 쿠폰/포인트 동시 사용 가능  
- 배송지 관리 및 배송 상태 실시간 확인  
- 주문 취소 / 환불 절차 제공  

### 4. 커뮤니티 & 참여
- 상품 후기 작성 + 별점 등록  
- 문의(Q&A) 등록 및 답변 확인  
- 이벤트 / 프로모션 참여 가능  

### 5. 관리자 페이지
- 상품 등록·수정·할인율/재고 관리  
- 회원 등급 조정 및 포인트·쿠폰 지급  
- 이벤트, 공지, 배너, 팝업 등 프로모션 관리  
- 리뷰 블라인드 처리 & 신고 대응  
- Q&A 및 1:1 문의 답변 관리  
- 매출/회원 통계 대시보드 제공  

---

## 💻 실행 화면


### 🛍️ 메인 서비스
- 메인 → 상품 상세 → 장바구니 → 결제 → 주문 완료  
<img src="https://github.com/user-attachments/assets/a547ed64-264c-427d-a347-66fa102a9999" width="800" alt="전체 서비스 흐름">

---

### 🛠️ 담당 화면 (메인 Frontend + 관리자 Frontend + Backend)

#### 1️⃣ 카테고리 페이지
<img src="https://github.com/user-attachments/assets/061d1578-44de-4111-8efa-79f9ad1dea5e" width="800" alt="카테고리 페이지">

- 상품 필터, 정렬, 리스트 구현
- CSS 및 레이아웃 조정으로 화면 깨짐 방지

#### 2️⃣ 상품 상세 페이지
<img src="https://github.com/user-attachments/assets/d59eccd1-3795-4796-808d-dc4b8444e30a" width="800" alt="상품 상세 페이지">

- 사이즈/수량 선택 시 DOM 동적 생성  
- 총 결제 금액 자동 계산 기능 구현  
- CSS 조정으로 옵션 영역 추가 시 레이아웃 유지

#### 3️⃣ 장바구니 페이지
<img src="https://github.com/user-attachments/assets/e2e32c83-9955-4785-989a-ee0785091e62" width="800" alt="장바구니 페이지">

- 선택 상품 담기/삭제/수량 변경 기능 구현  
- 총 결제 금액 실시간 계산

#### 4️⃣ 주문 페이지
<img src="https://github.com/user-attachments/assets/0cfbefb6-4fc0-4a97-a463-118e9a113fbc" width="800" alt="주문 페이지">

- 주문 정보 전송 및 결제 로직 연동  
- 사용자 입력 검증 및 오류 처리

#### 5️⃣ 주문 완료 페이지
<img src="https://github.com/user-attachments/assets/1f4fce9a-91ce-44e2-8e8d-88081d8010ba" width="800" alt="주문 완료 페이지">

- 주문 내역 요약, 결제 상태 표시

#### 6️⃣ 아이디 찾기 페이지
<img src="https://github.com/user-attachments/assets/491aa194-0be6-463b-9d73-4c09f4bc2ded" width="800" alt="아이디 찾기 페이지">

- 입력 검증 및 결과 표시 기능 구현

#### 7️⃣ 관리자 회원 관리

<img src="https://github.com/user-attachments/assets/3a86c42f-4bb1-4f04-8609-17cd93ec142c" width="800" alt="관리자 검색">
<img src="https://github.com/user-attachments/assets/495f8589-c0f7-4e68-918e-0087e28af089" width="800" alt="회원 정보 수정">
<img src="https://github.com/user-attachments/assets/e468ac09-5240-448c-a759-85a57ba39440" width="800" alt="회원 상세 페이지">

- 회원 검색 기능 구현 (이름/아이디/연락처)  
- 회원 정보 수정 및 상세 페이지 구성

---

## 📂 프로젝트 구조
```
shoebox/
├── src/main/java/com.test.shoebox/
│   ├── config/      # Spring Security & MVC 설정
│   ├── controller/  # 역할별 컨트롤러(Admin, Member 등)
│   ├── dto/         # 데이터 전송 객체(DTO)
│   ├── entity/      # JPA 엔티티
│   ├── repository/  # JpaRepository 정의
│   ├── service/     # 비즈니스 로직
│   └── ShoeboxApplication.java
├── resources/
│   ├── static/      # CSS, JS, 이미지
│   ├── templates/   # Thymeleaf 템플릿
│   └── application.yml
├── shoebox_DDL.sql  # DB 테이블 생성 스크립트
└── build.gradle
```
---
## 🚀 실행 방법

### 1. DB 세팅
- Oracle 설치 후 `shoebox_DDL.sql` 실행

### 2. 프로젝트 열기
- STS4 또는 IntelliJ에서 **Gradle 프로젝트**로 Import

### 3. 환경 설정
- `application.yml`에서 DB 접속 정보, 포트, 보안 옵션 수정

### 4. 서버 구동
- `ShoeboxApplication.java` 실행  
  또는  
  ```bash
  ./gradlew bootRun
  ```
### 5. 접속 주소
- 사용자: http://localhost:8090/main/
- 관리자: http://localhost:8090/admin/


## 🔧 Troubleshooting (관리자)

### 1️⃣ 500 Internal Server Error
- **문제**: 일부 회원 페이지 접근 시 서버 오류  
- **원인**: Controller에서 `Optional.get()` 호출 시 데이터 미존재  
- **해결**: `Optional.orElseThrow()`로 null 안전 처리 및 @ControllerAdvice로 예외 공통 처리  


### 2️⃣ DB 연결 문제
- **문제**: 주문/회원 조회 시 데이터가 화면에 표시되지 않음  
- **원인**: `application.yml`의 Oracle 접속 정보 오타, 테이블 데이터 누락  
- **해결**: DB 접속 정보 수정, 테이블 생성 스크립트(shoebox_DDL.sql) 적용, HikariCP 로그 확인  


### 3️⃣ Thymeleaf 렌더링 오류
- **문제**: 상세페이지, 마이페이지 일부 뷰가 로드되지 않음  
- **원인**: 모델 객체 미전달 또는 뷰 파일 경로 불일치  
- **해결**: Controller에서 Model에 DTO 전달, 템플릿 파일(user/detail.html 등)과 경로/변수명 일치 확인  


### 4️⃣ 정적 리소스 캐싱 문제
- **문제**: CSS/JS 수정 후 브라우저에서 갱신되지 않음  
- **원인**: 브라우저 캐시, Spring Boot 기본 리소스 캐시  
- **해결**: `spring.web.resources.cache.period=0` 설정, 개발환경에서만 적용



## 🛠️ Troubleshooting (메인 Frontend)

### 1️⃣ 상품 옵션 선택 시 레이아웃 깨짐
- **문제**: 사이즈 선택 후 옵션 영역이 추가될 때 레이아웃이 무너짐  
- **원인**: CSS `display` 속성과 JS `innerHTML` 사용으로 flex 스타일 초기화  
- **해결**:  
  - `selected-size-info`에 고정 flex 스타일 적용  
  - `innerHTML` 대신 `appendChild` 사용으로 DOM 구조 유지  


### 2️⃣ 총 결제 금액 표시 오류
- **문제**: 수량 변경 시 총 금액이 반영되지 않음  
- **원인**: 숫자 포맷(쉼표 포함) 파싱 실패, `updateTotal()` 미호출  
- **해결**:  
  - 이벤트마다 `updateTotal()` 강제 호출  
  - `parseInt(price.replace(/[^0-9]/g, ''))`로 숫자만 추출  


### 3️⃣ 버튼 클릭 UX 개선
- **문제**: 장바구니/구매 버튼 클릭 시 선택 상품이 없으면 반응 없음  
- **해결**:  
  - 조건문으로 예외 처리 → `alert` 메시지 출력  
  - 잘못된 요청 차단, 사용자 경험 개선  





