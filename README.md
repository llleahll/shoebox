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




