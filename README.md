# <div align="center">**JuShoppingmall**</div>

## Shoppingmall

### 기간 : 2022.8.22 ~ 2022.8.29

### 개발자 : 주병현,안주영, 장지원

### 본인 역할

## 백엔드 및 프론트엔드

- ### 백엔드

- **로그인**

  - Mysql을 이용한 로그인 구현
  
  - JWT를 이용한 로그인 유지

- **회원가입**

  - Mysql을 이용한 회원가입 구현

- ** Mysql설계 **

  - 로그인 : 로그인에 필요한 쇼핑몰 유저 저장

  - 회원가입 : 유입된 회원들을 저장할 수 있는 저장소 구현
  
  - 장바구니 : 유저들이 마음에 드는 상품을 골라 담을 수 있는 저장공간 구현

- **프론트**

  - 메인 페이지 구현

  - 장바구니 페이지 구현

---

## 목차


- [**개요**](https://github.com/acca3434/JuShoppingmall#%EA%B0%9C%EC%9A%94)
- [**사용기술**](https://github.com/acca3434/JuShoppingmall#%EC%82%AC%EC%9A%A9-%EA%B8%B0%EC%88%A0)
  - [전체 데이터베이스](https://github.com/acca3434/JuShoppingmall#%EC%A0%84%EC%B2%B4-%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4
)
  - [메인 페이지](https://github.com/acca3434/JuShoppingmall#%EB%A9%94%EC%9D%B8-%ED%8E%98%EC%9D%B4%EC%A7%80)
  - [회원가입 페이지](https://github.com/acca3434/JuShoppingmall#%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85-%ED%8E%98%EC%9D%B4%EC%A7%80)
  - [로그인 페이지](https://github.com/acca3434/JuShoppingmall#%EB%A1%9C%EA%B7%B8%EC%9D%B8-%ED%8E%98%EC%9D%B4%EC%A7%80)
  - [로그인 후 페이지](https://github.com/acca3434/JuShoppingmall#%EB%A1%9C%EA%B7%B8%EC%9D%B8-%ED%9B%84-%ED%8E%98%EC%9D%B4%EC%A7%80)
  - [자유게시판 페이지](https://github.com/acca3434/JuShoppingmall#%EC%9E%90%EC%9C%A0%EA%B2%8C%EC%8B%9C%ED%8C%90-%ED%8E%98%EC%9D%B4%EC%A7%80)
  - [자유게시판 검색 기능(JQeury)](https://github.com/acca3434/JuShoppingmall#%EC%9E%90%EC%9C%A0%EA%B2%8C%EC%8B%9C%ED%8C%90-%EA%B2%80%EC%83%89-%EA%B8%B0%EB%8A%A5jqeury)
  - [자유게시판 댓글 기능](https://github.com/acca3434/JuShoppingmall#%EC%9E%90%EC%9C%A0%EA%B2%8C%EC%8B%9C%ED%8C%90-%EB%8C%93%EA%B8%80-%EA%B8%B0%EB%8A%A5
)
  - [장바구니 기능](https://github.com/acca3434/JuShoppingmall#%EC%9E%A5%EB%B0%94%EA%B5%AC%EB%8B%88-%EA%B8%B0%EB%8A%A5)
  
---

## **개요**

### **Scripts**

`npm start`

---

## 사용 **기술**

<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"> 
<img src="https://img.shields.io/badge/Mysql-2496ED?style=for-the-badge&logo=Mysql&logoColor=black"> 
<img src="https://img.shields.io/badge/Express.js-363636?style=for-the-badge&logo=Express.js&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-F16822?style=for-the-badge&logo=Node.js&logoColor=white"> 
<img src="https://img.shields.io/badge/JWT-FF9900?style=for-the-badge&logo=JWT&logoColor=black">

---

### 전체 데이터베이스

<br/>

<img src="./img/database.png" />

<br/>

### 메인 페이지

<br/>

<img src="./img/mainPage.png" />

<br/>

## 페이지를 누르면 각 디자이너의 쇼핑몰이 나옴

### 안주영 페이지 클릭

<br/>

<img src="./img/topPage.png" />

<br/>

###  주병현 페이지 클릭

<br/>

<img src="./img/secondPagePage.png" />

<br/>

###  장지원 페이지 클릭

<br/>

<img src="./img/thirdPage.png" />

<br/>

### 회원가입 페이지

<br/>

<img src="./img/signUpPage.png" />

<br/>

### 로그인 페이지

<br/>

<img src="./img/loginPage.png" />

<br/>

### 로그인 후 페이지(JWT 로그인 유지)

<br/>

<img src="./img/loginAfterPage.png" />

<br/>

### 유저 베스트 검색 실시간 페이지

<br/>

<img src="./img/TapLiveSearchBest.png" />

<br/>

### 출석체크 페이지

<br/>

<img src="./img/culseockPage.png" />

<br/>

### 챗봇 페이지

- 챗봇은 실시간으로 사용자의 말을 기억하는것으로 구현하는것이 아닌 
- 상담원으로 바로 연결하기 위해 정해진 답변을 내놓고 상담원과
- 바로 연결한다

<br/>

<img src="./img/chatBot.png" />

<br/>

- 유저가 마음에 드는 쇼핑몰의 물건을 누르면 장바구니에 담기는 기능이다.

### 장바구니 리모콘 페이지

<br/>

<img src="./img/cartCount.png" />

<br/>

### 장바구니 기능

<br/>

<img src="./img/cartPage.png" />

<br/>
=======
09.03.10-# AJJShoppingMall

## 안주장 쇼핑몰의 정의

https://cuddly-petroleum-f3d.notion.site/AJJ-dfb013b2cafa46678509f7e1bf327b4b

## 구현한 기능

https://cuddly-petroleum-f3d.notion.site/ad3b8b0e0db1451d9fe62660d1a5378c

## 회의록들

https://cuddly-petroleum-f3d.notion.site/2f508307056d4af8afbf3bf35a4b776e?v=f4d177d3c9054c1f9457342a02246a57