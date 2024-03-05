# 프로젝트 소개


> 오픈소스 코드와 jQuery를 이용하여 구상한 쇼핑몰 홈페이지 입니다.  \
> 사용자는 홈페이지를 통해 가입, 쿠폰, 이벤트, 공지 등을 확인할 수 있으며 메인, 카테고리, 장바구니 등 화면을 확인할 수 있습니다. 
> 
> HTML, CSS를 사용해 기본적인 웹 화면을 구현하고, \
> Javascript와 jQury를 이용해 동적인 이벤트 처리와 모달 창 등을 적용했습니다.

> ### 개발 기간 및 인원
> 23.11.24 ~ 23.12.04 (1.5주) \
> 풀스택 1명

<br/>

# 기술 스택
![html](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![css](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![jquery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

<br/>

# 주요 기능

### 모달 창
- 주문이 어떻게 진행되고 있는지 확인할 수 있도록 주문의 상태를 변경할 수 있다.
- 주문이 들어오면 예상 조리 시간을 선택해야 한다.
- 주문이 들어오면 주문을 수락하거나 거절할 수 있다.

![309559121-d0533ef0-93f4-4206-9408-bbb786b1dfb2](https://github.com/jeong9745/jQuery-mall/assets/156148169/c0427fb6-1935-43f9-a536-f85482e78ffc)

https://github.com/jeong9745/jQuery-mall/assets/156148169/2c0a0537-e6ed-4858-b745-2f02c25b9656

### 특정 조건 만족 시 숨겨진 입력 창 띄우기
- ID 와 PW를 비교하고, 저장된 정보가 아니라면 신규 회원으로 간주한다.
- 회원가입 페이지로 전환되면서 e-mail 을 추가로 작성하는 입력란이 뜬다. 

![309559135-ed86a5c1-60c0-47b5-b65a-03e3914d8978](https://github.com/jeong9745/jQuery-mall/assets/156148169/763abb5b-2caa-43b7-8451-b78332eea162)

<br/>

# 추가 구현하고 싶은 기능

### 데이터베이스 연동
- 카테고리의 제품을 카트에 담으면 데이터가 저장되고, 담은 제품 정보를 데이터에서 불러와 카트에서 확인할 수 있어야 한다.
- 회원가입을 하면 User정보가 데이터베이스에 저장되고, 로그인 및 로그아웃 시 데이터베이스에서 유저 정보를 찾아 로그인 할 수 있어야 한다. 
- 이벤트 정보 및 게시판 내용 등이 데이터에 저장되고, 이벤트 정보 및 게시판 내용 조회 시 불러와 게시판에서 내용을 확인 할 수 있어야 한다.
- 결제를 하고 구매가 완료되면 데이터베이스에 저장되고, 구매 내역을 홈페이지에서 확인 할 수 있어야 한다. 

### 카트 바구니 기능 추가
- 전체 주문하기를 누르면 체크박스가 모두 체크가 된다.
