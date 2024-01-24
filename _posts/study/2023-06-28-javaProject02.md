---
layout: post
title: 자바 팀프로젝트 2. 프로젝트 구체화
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


오늘의 주제 : 첫번째 팀프로젝트를 준비해보자2 <br>
 * * *

대략적인 틀(이라고 쓰고 구체적인 사항까지)을 정했고, 구글 시트에 작성해서 공유했다.<br>
사실 코딩 자체가 처음이라 팀 프로젝트를 어떻게 시작해야하는지조차 몰라서,, 정말 난감했다...!<br>
그래서 대략적인 주제를 혼자 생각해보고 어떻게 해야하는건지 생각하려고 대강 만든건데 이대로 하게되었다.<br>

## 전체 개요
![image](https://github.com/CheeseYoung/cheeseyoung.github.io/assets/132384527/890b3d88-d474-4765-a388-8ea48d4588ee) <br>
- DB를 어떻게 구성할지, 어떤 요구사항이 있는지, 출력화면은 어떻게 출력하고 싶은지를 대략적으로 나타냈다.
- 요구사항명세서는 배우진 않았지만 프로젝트를 진행하려면 필요할 것 같다고 해서 찾아보고 작성했다.
<br>


## DB 구성
![image](https://github.com/CheeseYoung/cheeseyoung.github.io/assets/132384527/d181331a-3e24-4642-96b4-e8b1f3c0a8e0) <br>
- 각 테이블의 칼럼명, 타입 등을 설정했다. 
- 숙소테이블의 숙소번호와 고객테이블의 id가 예약테이블에 사용된다.
<br>

## 출력화면
![image](https://github.com/CheeseYoung/cheeseyoung.github.io/assets/132384527/46281592-3d51-4ca4-82d6-699e7644c845) <br>
- 요구사항 명세서에 적혀있는 사항들을 직관적으로 보고 싶어서 출력화면을 상상으로 제작해뒀다.
- 모든 기능의 출력화면을 만들어두어 요구사항을 직관적으로 볼 수 있고, 코드를 짤 때 큰 도움이 되었다.
<br>

## 데이터
: db 구성에서 미리 짜놓은 데이터테이블에 맞춰서 데이터를 가공해뒀다.<br>
![image](https://github.com/CheeseYoung/cheeseyoung.github.io/assets/132384527/d8fc7390-1f65-4e81-80fd-7766d381ed81) <br>
- 데이터는 실제 숙박업소 목록을 사용했고, 3만건 중에 일반호텔,관광호텔으로 분류된 3500건만 사용했다.
- 가격대의 다양성을 위해 주중가격은 랜덤으로 생성했고, 주말가격 또한 주중가격 * 1.2~1.5 로 랜덤으로 생성했다.
- 쿠폰 적용 여부는 나중에 사용할 때를 대비해서 쿠폰사용불가를 0으로, 쿠폰사용가능을 1로 설정했다.











