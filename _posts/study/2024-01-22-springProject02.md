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
: 프로그램을 만드는동안 기능을 테스트할 데이터가 있으면 더 편할 것 같아서 작성했다. <br>
![image](https://github.com/CheeseYoung/cheeseyoung.github.io/assets/132384527/d8fc7390-1f65-4e81-80fd-7766d381ed81) <br>
- 데이터는 실제 숙박업소 목록을 사용했고, 3만건 중에 일반호텔,관광호텔으로 분류된 3500건만 사용했다.
- 가격대의 다양성을 위해 주중가격은 랜덤으로 생성했고, 주말가격 또한 주중가격 * 1.2~1.5 로 랜덤으로 생성했다.
- 쿠폰 적용 여부는 나중에 사용할 때를 대비해서 쿠폰사용불가를 0으로, 쿠폰사용가능을 1로 설정했다.









