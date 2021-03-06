



# Overview


개요 - MVC패턴 숙련을 위한 오라클 SQL 데이터 연동 페이지 설계

4인 협업 프로젝트 - 가상의 전자책 대여 페이지를 만들기로 회의 후 결정

미리 전자책 데이터를 저장해두고, 홈페이지를 이용해 열람할 수 있다

부가기능으로는 자유게시판 등이 있다



사용 편집기 : 이클립스

서버 : 아파치 톰켓

브라우저 : 크롬

프레임워크 : 스프링, Run on Server로 시작

​

​

# Demo / 스크린샷


![b_01](https://user-images.githubusercontent.com/79967078/121019768-b21d6180-c7da-11eb-8b1a-bc99ac038afd.jpg)
![b_02](https://user-images.githubusercontent.com/79967078/121019778-b3e72500-c7da-11eb-878b-10529dc7cb49.jpg)
![b_03](https://user-images.githubusercontent.com/79967078/121019783-b5185200-c7da-11eb-89a2-a9fef326acea.jpg)
![b_04](https://user-images.githubusercontent.com/79967078/121019789-b6497f00-c7da-11eb-820a-9eaa7d426755.jpg)


​

​

# Technologies used (libraries & versions)


사용언어 / Java, JSP, Javascript 
프레임워크 / Spring Framwork / Mybatis, MVC MODEL2, html5, css3, Bootstrap
데이터베이스 / Oracle SQL


​

​

# Project setup



마이바티스, SQL 오라클 DB설정, 이클립스, SPRING 프레임워크 maven 설정, 톰켓 아파치 주소 설정

​

​

# Unique elements



책 대출관련 DB연동 및 접근성이 좋은 UI를 만들기위해 페이징처리와 DB에따른 목록을 나열하였다

환경에 따라 쉽게 URL주소를 변경할 수 있도록 변화가 쉬운 부분은 CONTEXT BEAN 으로 변경하였다



​

​

# Problems I faced


페이징처리부분을 구현하는데 많은 시행착오를 겪으면서 구현할 수 있었다

DB에 데이터(이미지, 텍스트)를 넣고 유동적으로 구현하는데서 많은 시행착오를 겪었다

외부서버에서 로그인하고 게시글을 올리는데 이미지파일을 설정해 서버컴퓨터에 받게끔 설계하는데서 시행착오를 여러번 겪었다

MVC 패턴 서비스 부분에서 가져와야할 여러 값들을 연동하거나 이어붙이는데 에로사항이 많았고 함수나 명령어를 많이 알아보았다

​

​

# What I learned

MVC패턴 서비스, 홈컨트롤러, 각종 메소드의 연계방법을 익혔고 JSP에서 어떻게해야 동적인 페이지를 구현할수 있는지 숙련하게 되었다

서버가 어떤식으로 데이터를 받고 전송하는지, ORACLE 데이터를 어떻게 이용해야하는지 익힐 수 있었다
​

​

# Known issues


텍스트를 단순히 텍스트상자에 나열하는 점이 부족하고, 텍스트가 아닌 연속된 이미지파일로 가상책을 열람하는 방법을 구현하지 못했다

CSS 설정이 전반적으로 부족하다 





