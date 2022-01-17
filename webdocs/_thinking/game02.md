---
title: 게임 만들기 01 - 지구를 지켜라. STEP2. 로켓 공격효과
---

스페이스바를 누르면 로켓이 발사되어 달걀을 공격한다.    

# STEP2. 로켓 공격효과

## 1. 로켓 공격기능 추가
 + 시작 클릭
    + { 스페이스 키를 누르면 나자신 복제하기} 를 무한반복     
    + 1초 기다리기; 공격하면 1초 후에 다시 공격할 수 있다.    
 
 + 복제되었을 때
    + { y좌표를 10만큼 바꾸기 } 를 y좌표가 180보다 클때까지 반복
    + 복제본 삭제하기

 ![]({{ site.baseurl }}/assets/images/game/egg01_04.png){: .img-thumbnail }


## 2. 지금까지 코딩결과 실행

<iframe width="560" height="315" src="https://www.youtube.com/embed/WOr_qf50kyM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## 3. 로켓 공격효과 주기
+ 복제되었을 때
    + 투명도 효과를 30만큼 바꾸기
    + 크기를 -10만큼 바꾸기

+ 나자신 복제하기 후에
    + 투명도 효과를 10만큼 바꾸기
    + 밝기 효과를 10만큼 바꾸기
+ 1초 기다리기 후에
    + 투명도와 밝기를 원래대로 바꾸기

 ![]({{ site.baseurl }}/assets/images/game/egg01_05.png){: .img-thumbnail }

## 4. 달걀 공격효과 주기
+ 종료위치 신호를 받았을 때
    + 모양을 egg-b로 바꾸기

+ 시작위치 신호를 받았을 때
    + 모양을 egg-a로 바꾸기

![]({{ site.baseurl }}/assets/images/game/egg01_06.png){: .img-thumbnail }

## 5. 실행
+ 공격효과가 추가된 코딩 결과 [예제보기](https://scratch.mit.edu/projects/629430809/){: .btn .btn-primary target="_blank" }    

<iframe src="https://scratch.mit.edu/projects/629493337/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>