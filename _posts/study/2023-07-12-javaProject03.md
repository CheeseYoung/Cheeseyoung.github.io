---
layout: post
title: STUDY_자바 팀프로젝트3. 프로그램 제작
subtitle: Preparing Team Project 
author: Jo
categories: STUDY
banner:
  video: "./assets/images/banners/typing.gif"
  loop: true
  volume: 0.8
  start_at: 8.5
  image: "assets/images/banners/typing.gif"
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: gold"
tags: Java API Oracle Study

---


오늘의 주제 : 첫번째 팀프로젝트를 해보자3 <br>
 * * *


## JAVA를 이용한 프로그램 만들기
![image](https://github.com/CheeseYoung/cheeseyoung.github.io/assets/132384527/0de63c0f-1168-4715-bb81-7f81263b9638) <br>
- 테이블 3개에 맞춰서 VO 3개
- 프로그램을 실행하는 main
- 회원가입과 로그인을 하는 util
- 관리자용 메뉴 admin
- 고객용 메뉴 customer
- 필요한 모든 메소드는 DAO 1개에 정리했다.
<br>
- 여기서 관리자용 메뉴와 고객용 메뉴를 구분했기에 userid가 계속 필요했는데,<br>
  userid는 util에서 입력 받은 값이라 어떻게 저 값을 각 클래스에서 어떻게 사용할 지 고민이 많았다.<br>
  그래서 login 메소드에서 입력받은 userid를, menu 메소드를 부를 때 <b>매개변수</b>로 받게했고,<br>
  그 결과, 입력받은 userid를 각 클래스에서 사용할 수 있게 됐다.
<br>



