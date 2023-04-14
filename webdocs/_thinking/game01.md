---
title: 게임 만들기 01 - 지구를 지켜라. STEP1. 게임 기본설정
permalink: /thinking/game
---

스크래치의 기본사용법과 제어, 반복, 랜덤, 연산등의 코딩 문법에 대해 알아보았고, 이를 토대로 게임을 만들어 보자.    

한번에 완벽한 게임을 만드는 건 매우 어려운 일이다.    
스프라이트 제어에서 시작하여, 공격하기, 점수계산, 게임끝 등의 게임 요소를 하나씩 추가하며, 게임만들기의 난이도 조금씩 높여가며 만들어 보자.

# 지구를 지켜라 
>> 1. 하늘에서 달걀이 지구로 떨어진다.
>> 2. 달걀이 지구에 떨어지면 달걀에서 나온 빌런이 지구를 공격한다.
>> 3. 달걀이 지구에 도착하기 전에 로켓으로 달걀을 깨뜨리자.
>> 4. 스페이스바를 누르면 로켓이 발사된다.
>> 5. 좌/우 방향키로 로켓의 위치를 이동할 수 있다.

![]({{ site.baseurl }}/assets/images/game/egg01_01.png){: .img-thumbnail }

# STEP1. 게임 기본설정

## 1. 스프라이트 추가
 + 로켓 스프라이트 추가    
 + 달걀 스프라이트 추가    
 + 무대 배경 변경    

<iframe width="560" height="315" src="https://www.youtube.com/embed/Kvc9PzdqEic" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## 2. 시작 위치 조정
 + 로켓 시작위치 (0, -130)    
 + 달걀 시작위치 ((-10 ~ 10)*20, 160)    

## 3. 달걀 공격기능 추가
+ 시작위치
+ { 바닥에 닿을때까지 y좌표를 -5만큼 바꾸기 } 를 무한반복    
![]({{ site.baseurl }}/assets/images/game/egg01_02.png){: .img-thumbnail }

## 4. 로켓 제어기능 추가
+ { 왼쪽화살표 키를 누르면 -10만큼 이동 } 를 무한반복    
+ { 오른쪽화살표 키를 누르면 -10만큼 이동 } 를 무한반복    
![]({{ site.baseurl }}/assets/images/game/egg01_03.png){: .img-thumbnail }

## 5. 실행
+ 달걀공격과 로켓제어 기능이 추가된 코딩 결과 [예제보기](https://scratch.mit.edu/projects/629430809/){: .btn .btn-primary target="_blank" }    

<div class="if-containerm">
<iframe src="https://scratch.mit.edu/projects/629430809/embed" allowtransparency="true" width="485" height="402" class="if-video"  frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>