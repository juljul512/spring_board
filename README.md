# spring_board

> **JDK 21**과 **Spring Boot**, **MyBatis**를 활용하여 제작한 SSR 기반의 커뮤니티 게시판 프로젝트입니다. 회원가입부터 로그인, 게시글 CRUD 및 페이징/검색 등 커뮤니티 서비스의 핵심 기능을 구현했습니다.

---

## 🛠 Tech Stack

### Backend
- **JDK:** 21
- **Framework:** Spring Boot 3.x (Spring 4.0.8)
- **Persistence:** MyBatis Framework
- **Database:** MariaDB

### Frontend
- **Rendering:** SSR (Server-Side Rendering)
- **Template Engine:** Thymeleaf
- **Script/Style:** jQuery, Bootstrap 5

---

## ✨ Key Features (주요 기능)

### 1. 👤 회원 관리 (Auth)
- **회원가입:** 아이디 중복 체크 (AJAX/jQuery) 및 비밀번호 암호화
- **로그인 / 로그아웃:** 세션 기반 인증 처리 및 접근 권한 제어

### 2. 📋 커뮤니티 게시판 (Board CRUD)
- **게시글 목록:** 페이징(Paging) 처리 및 키워드 기반 검색 (제목, 작성자, 내용)
- **게시글 조회:** 상세 페이지 조회 및 조회수 증가 처리
- **게시글 작성:** Thymeleaf 폼 바인딩을 통한 글 등록
- **게시글 수정/삭제:** 작성자 본인 확인 후 수정 및 삭제 가능

---

## 🏛 Architecture & ERD

### Database Schema (ERD)
*(ERD 이미지 URL 또는 설계를 넣어주세요)*
