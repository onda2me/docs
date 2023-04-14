---
title: 게임 만들기 01 - 지구를 지켜라. STEP3. 점수 기능
---

로켓을 발사하여 달걀 깨뜨리기가 성공하면 점수를 1점 추가한다.    

# STEP3. 점수 기능

## 1. 변수 추가
+ 점수 기능을 위해 변수 추가하기    

![]({{ site.baseurl }}/assets/images/game/egg01_061.png){: .img-thumbnail }    
![]({{ site.baseurl }}/assets/images/game/egg01_10.png){: .img-thumbnail }

## 2. 공격 감지
+ 복제되어 발사된 로켓이 달걀에 닿았는지 감지
+ 만약 공격이 감지되었다면 공격성공 신호 보내기
+ 공격성공 시 소리효과와 점수 +1 추가하기

**공격 감지**는 로켓과 Egg에 각각 다른 명령을 수행하기 위해 이벤트로 분리하였다.    
공격은 로켓에서 Egg를 감지할 수도 있고, Egg에서 로켓을 감지할 수도 있다.
{: .alert .alert-warning }    
![]({{ site.baseurl }}/assets/images/game/egg01_07.png){: .img-thumbnail style="vertical-align: top;"}
![]({{ site.baseurl }}/assets/images/game/egg01_08.png){: .img-thumbnail style="vertical-align: top;"}

## 3. 실행
+ 점수가 추가된 코딩 결과 [예제보기](https://scratch.mit.edu/projects/629554845/){: .btn .btn-primary target="_blank" }    

<div class="if-containerm">
<iframe src="https://scratch.mit.edu/projects/629554845/embed" allowtransparency="true" width="485" height="402" class="if-video"  frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

