---
layout: post
title: 스프링 팀프로젝트 1. 주제 선정 및 프로젝트 설계
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

## 주제 선정
![image](https://github.com/CheeseYoung/Cheeseyoung.github.io/assets/132384527/d92ed52a-7e72-4d81-97b2-22a283dc477d) <br>
- 주제 선정은 노션에 기록하며 진행했다.
- 브레인스토밍으로 넣고 싶은 기능들을 주르륵 적고, 그 중에서 현실적으로 판단하여 필요한 기능만 남겼다.
- 결론은 중고거래플랫폼에 경매 추가, 커뮤니티 기능 추가
![image](https://github.com/CheeseYoung/Cheeseyoung.github.io/assets/132384527/b20ebb47-3f8a-4038-89eb-ac5db2af3117)
- 프로젝트명을 정하며 아이디어를 짜내던 와중에 중고나라/번개장터/당근마켓을 다 합쳐버리자는 의견.
- 그렇게 프로젝트명은 피자나라치킨공주를 벤치마킹(?)한 <b>당근나라번개공주</b>가 되었다.


## 요구사항 명세서
![image](https://i.ibb.co/yPTrzw0/image.png) <br>
- 주제를 선정한 이후에, 스프레드 시트에 요구사항 명세서를 작성했다.
- 팀원들이 각자 생각나는대로 추가하고, 추가된 항목에 문제점이 보이면 수정했다.
- 일주일동안 추가와 수정을 거쳤고, 마지막 날은 부족하거나 필요없는 내용을 추가/삭제했다.


## 전체 개요
![image](https://i.ibb.co/WcLjS8b/20240122-141007.png) <br>
- 작성한 요구사항 명세서를 기반으로 대략적인 테이블을 구성했다.


## DB 구성
![image](https://github.com/CheeseYoung/Cheeseyoung.github.io/assets/132384527/3cd465da-3852-45ff-8757-33355744056d) <br>
- 각 테이블의 칼럼명, 타입, 제약조건 등을 설정했다. 
- 최대한 개발을 하는 도중에 변경되지 않도록 꼼꼼히 설정했(으나 개발 도중에 무수한 수정을 하며 눈물을 흘렸)다.
<br>


## 데이터
: 프로그램을 만드는동안 기능을 테스트할 데이터가 있으면 더 편할 것 같아서 작성했다. <br>
![image](https://github.com/CheeseYoung/cheeseyoung.github.io/assets/132384527/d8fc7390-1f65-4e81-80fd-7766d381ed81) <br>
- 데이터는 실제 숙박업소 목록을 사용했고, 3만건 중에 일반호텔,관광호텔으로 분류된 3500건만 사용했다.
- 가격대의 다양성을 위해 주중가격은 랜덤으로 생성했고, 주말가격 또한 주중가격 * 1.2~1.5 로 랜덤으로 생성했다.
- 쿠폰 적용 여부는 나중에 사용할 때를 대비해서 쿠폰사용불가를 0으로, 쿠폰사용가능을 1로 설정했다.










