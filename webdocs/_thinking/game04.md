---
title: 게임 만들기 01 - 지구를 지켜라. STEP4. 레벨 기능
---

# STEP4. 레벨 기능

특정 점수를 획득하면 레벨이 올라가도록 만들어 보자.
```
레벨 기준
+ 1레벨 :  0점 ~  9점, Egg 속도 : -5 (= 0*2)
+ 2레벨 : 10점 ~ 19점, Egg 속도 : -7 (= 1*2)
+ 3레벨 : 20점 ~ 29점, Egg 속도 : -9 (= 2*2)
+ 4레벨 : 30점 ~ 39점, Egg 속도 : -11 (= 3*2)
```

## 1. 변수 추가
+ 점수별 레벨 설정을 위해 레벨 변수 추가하기
+ 레벨에 따른 속도 조절을 위해 속도 변수 추가하기
+ 레벨계산 블럭 추가하기 (점수가 추가될 때마다 레벨을 계산한다.)
+ 레벨이 올라갈 때마다 배경화면 변경해 주기   

![]({{ site.baseurl }}/assets/images/game/egg01_14.png){: .img-thumbnail }

```
+ 게임의 재미를 위한 밸런스 (레벨과 속도에 따른 난이도) 조절은 스스로 결정해도 된다.    
```
## 2. 지금까지 코딩결과 실행
+ 레벨이 추가된 코딩 결과 [예제보기](https://scratch.mit.edu/projects/630074962/){: .btn .btn-primary target="_blank" }    

<iframe src="https://scratch.mit.edu/projects/630074962/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>


## 3. 게임화 UI 개선
+ 게임의 레벨(= 스테이지)이 변경되면 게임 사용자에게 안내문구를 보여주자.
+ 게임의 난이도 (레벨 및 속도) 를 게임 사용자에게 안보이도록 변경하자.

![]({{ site.baseurl }}/assets/images/game/egg01_16.png){: .img-thumbnail }    

+ 스테이지 변경 안내문구 보여주기
+ 게임 음악 추가하기    
![]({{ site.baseurl }}/assets/images/game/egg01_17.png){: .img-thumbnail }    

## 4. 실행
+ 안내문구가 추가된 코딩 결과 [예제보기](https://scratch.mit.edu/projects/633666587/){: .btn .btn-primary target="_blank" }    
<iframe src="https://scratch.mit.edu/projects/633666587/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>