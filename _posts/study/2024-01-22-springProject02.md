---
layout: post
title: 스프링 팀프로젝트 2. 데이터 생성 
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
sidebar: []

---


오늘의 주제 : 스프링부트로 팀 프로젝트를 해보자. <br>
 * * *



## 데이터
: 프로그램을 만드는동안 작성한 코드를 바로 테스트할 수 있게 데이터가 있으면 더 편할 것 같아서 미리 작성했다.
  설계해놓은 테이블 열에 맞춰서 작성해서, 데이터를 다운받은 그대로 추가할 수 있게 했다.

- 커뮤니티 데이터
  ![image](https://github.com/CheeseYoung/Cheeseyoung.github.io/assets/132384527/067ee3ab-798d-46a4-b17f-48cc15265bc7)
  - 카테고리별/ 날짜별/ 작성자별로 다양하게 작성
  - 신고 기능을 위해 신고당할만한 게시글도 작성
  - 사진이 있는 게시글도 작성
<br><br>
- 상품 데이터
  ![image](https://github.com/CheeseYoung/Cheeseyoung.github.io/assets/132384527/c7afc8e8-c0cb-428f-a6f0-4bf69572cde0)
  - 일반 거래와 경매 거래로 나누고, 카테고리별로 다양하게 작성
  - 물품 사진은 링크로 등록
  - 신고당할만한 판매물품도 작성
<br><br>

- 댓글 데이터
  ![image](https://github.com/CheeseYoung/Cheeseyoung.github.io/assets/132384527/237ea50e-139a-49d6-9c81-394acf7ca831)
  - 일반 댓글과 대댓글 작성
<br><br>

- 신고 데이터
  ![image](https://github.com/CheeseYoung/Cheeseyoung.github.io/assets/132384527/c3b3eea4-fb08-40aa-b03c-e8f6529012f2)
  - 신고당한 것이 커뮤니티인지 상품인지 구분하고, 해당 게시글/상품 번호 작성
  - 대댓글의 경우엔 참조댓글번호를 추가
<br>











