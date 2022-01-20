---
title: 게임 만들기 01 - 지구를 지켜라. STEP4. 레벨 기능
---

# STEP4. 레벨 기능

특정 점수를 획득하면 레벨이 올라가도록 만들어 보자.
```
레벨 기준
+ 1레벨 : 10점 미만; Egg 속도 -5
+ 2레벨 : 10점 ~ 19점, Egg 속도 -7 (= 레벨-1)*2
+ 3레벨 : 20점 ~ 29점, Egg 속도 -9 (= 레벨-1)*2
+ 4레벨 : 30점 이상, Egg 속도 -11 (= 레벨-1)*2
```

## 1. 변수 추가
+ 점수별 레벨 설정을 위해 레벨 변수 추가하기
+ 레벨에 따른 속도 조절을 위해 속도 변수 추가하기
+ 점수가 추가될때마다 레벨을 계산하는 블럭 추가하기    
+ 레벨이 올라갈때마다 배경화면을 변경해 주기   

![]({{ site.baseurl }}/assets/images/game/egg01_14.png){: .img-thumbnail }

```
+ 레벨과 속도의 기준은 똑같이 설정할 필요는 없다.
+ 게임의 재미를 위한 밸런스 조절은 스스로 결정해도 된다.    
```

## 2. 실행
+ 레벨이 추가된 코딩 결과 [예제보기](https://scratch.mit.edu/projects/630074962/){: .btn .btn-primary target="_blank" }    

<iframe src="https://scratch.mit.edu/projects/630074962/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>

