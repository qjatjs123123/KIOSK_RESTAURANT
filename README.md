# 웹을 활용한 키오스크
## 개요
많은 음식점이 키오스크를 사용하고 있다. 키오스크 PC에 직접 설치를 해야하는 번거로움이 있다. 이러한 문제를 해결하기 위해 웹앱을 통해 배포 및 유지 보수를 할 수 있도록 구현하였다.

## 사용 기술
1. 자바스크립트 - 웹 브라우저 프로그래밍을 하기 위하여 사용
2. CSS - 웹 브라우저의 스타일을 위하여 사용
3. JSP - DB연동 및 동적 프로그래밍을 위해 사용
4. Web Socket - [메뉴판 페이지] [주방 페이지]간 메시지 송수신을 위해 웹 소캣 사용
5. Imgur API - DB에 이미지를 저장하기 위해서 사용
6. Maria DB - 회원가입 정보, 메뉴 정보, 매출 정보를 저장하기 위해 사용

## 키오스크 프로그램 동작 과정
1. 회원가입을 한다.
2. 로그인 후 관리자 모드에 접속한다.
3. 관리자 모드에서 메뉴 이미지 선택, 이름, 가격을 입력한다.
4. 메뉴판 모드에 접속한다.
5. 메뉴판 페이지에서 주문한 음식 정보가 웹 소캣을 통해 주방 페이지에 전달된다.
6. 주방 페이지에서 완료된 음식은 클릭하여 삭제한다.
7. 관리자는 관리자 모드에서 매출 정보를 년/월/일 별로 확인 한다.

## 페이지 이미지
### 로그인 페이지
![image](https://user-images.githubusercontent.com/74814641/134827217-69e5f5e2-4ee0-46bc-85d1-95f76ae9ef4c.png)

### 모드 선택 페이지
![image](https://user-images.githubusercontent.com/74814641/134827304-8b3f709e-dc18-4db2-9b4e-d740fd73b40f.png)

### 주방 페이지
![image](https://user-images.githubusercontent.com/74814641/134827287-5c676ad5-c6c1-40f7-b0de-f8d14460ff6d.png)

### 메뉴판 페이지
![image](https://user-images.githubusercontent.com/74814641/134827321-f9c1d0fc-34fc-4431-9468-e25dce66859e.png)

### 장바구니 페이지
![image](https://user-images.githubusercontent.com/74814641/134827352-6ec0e236-ba89-4b22-a4a1-99cca7a11957.png)

### 관리자 페이지
![image](https://user-images.githubusercontent.com/74814641/134827414-a71b8b75-526c-4534-9cb7-371f27c8c994.png)

## 기능 설명(영상)
### 회원가입 
https://user-images.githubusercontent.com/74814641/134828356-b673c53a-8ea1-4cf1-8735-ff275a76b8cd.mp4

### ID찾기





