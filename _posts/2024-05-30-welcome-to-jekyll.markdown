---
layout: post
title:  "추천 알고리즘 정리 [쇼핑몰 프로젝트]"
date:   2024-06-09 22:00:00 +0900
categories: recommend update
---

## 추천 알고리즘

<span style="color: gray; font-size: 10px">쇼핑몰 프로젝트에 사용하기 위해 찾은 내용을 정리하였다</span>


추천 알고리즘에는 **Content Based Filtering(콘텐츠 기반 필터링)**과 **Collaborative Filtering(협업 필터링)**이 존재한다.

![alt](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FdJEzTS%2Fbtrp96bndoU%2FPRjKhEf1k1FJdHwmpGp0HK%2Fimg.png)

출처 : Designing of Recommendation Engine for Recyclalbe Waste Mobile App

---

<br>

**콘텐츠 기반 필터링**은 *A* 라는 상품을 사용자가 구매한 경우, *A* 상품과 유사한 특성을 갖는 상품들을 사용자에게 추천해준다.

예를 들면, 사용자가 장거리 달리기에 적합한 런닝화를 구매한 경우, 장거리 달리기에 특화된 런닝화들이 추천목록에 올라오는 것이다.

![alt](https://img.gqkorea.co.kr/gq/2023/03/style_6414b4e977553.jpg)
![alt](https://img.gqkorea.co.kr/gq/2023/03/style_6414b4e7b372c.jpg)

<br>

**협업 필터링**은 *유사한 사용자* 를 찾는 것에서 출발하는 알고리즘이다.

이 **협업 필터링**은 또한 **사용자 기반 필터링**과 **아이템 기반 필터링**으로 구분 지을 수 있다.

<br>

**협업 필터링**의 종류인 **사용자 기반 필터링**은 *비슷한 성향*의 사용자들을 찾아서 해당 사용자들이 구매한 물건들을 추천해준다.

예를 들면, 어떠한 물건에 대해 다른 사용자도 *같은 평점*을 남겼을 경우, *비슷한 성향*이라 판단하여 비슷한 성향의 사용자가 구매한 물건을 추천해주는 것이다.

![alt](https://velog.velcdn.com/images/sagesrkim/post/11271216-fc97-4eed-aef5-b3b4e1b42073/image.png)
