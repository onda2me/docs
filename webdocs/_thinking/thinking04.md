---
title: 사고력 키우기 04 - 순차와 반복구조
---

### 순차와 반복구조에 대해서 알아보자.    

>> 순차구조는 이름 그대로 순서에 따라 차례대로 처리하는 구조이다.     
>> 반복구조는 동일한 일을 계속 반복하여 처리하는 구조이다.

# 순차구조의 예    
>> 순서에 따라 차례대로 처리하는 구조

+ 무지개색의 순서
> **빨강 -> 주황 -> 노랑 -> 초록 -> 파랑 -> 남색 -> 보라** 의 순서대로 색이 있다.    
> 위의 순서가 바뀌거나 다른 색이 포함되면 무지개색이 아니다.    

+ 일주일 요일의 순서
> **월요일 -> 화요일 -> 수요일 -> 목요일 -> 금요일 -> 토요일 -> 일요일** 의 순서대로 요일이 정해진다.    
> 위의 순서가 바뀌면 일주일 요일이 아니다.    

+ 수업시간 표    
> **1교시 영어 -> 2교시 수학 -> 3교시 미술 -> 4교시 체육**{: .text-dark}   

![]({{ site.baseurl }}/assets/images/scratch/order_rainbow.png){: style="height:450px" .img-thumbnail }
![]({{ site.baseurl }}/assets/images/scratch/order_week.png){: style="height:450px" .img-thumbnail }

# 선택구조의 예    
>> 조건에 따라 처리하는 내용이 달라지는 구조

+ 4교시는 만약 비가 오면 음악수업을 하고, 비가 오지 않으면 체육수업을 한다.
+ 아침에 일찍 일어나면 학교에 천천히 걸어가고, 늦게 일어나면 뛰어간다.

# 반복구조의 예
>> 동일한 일을 계속 반복하여 처리하는 구조

+ 시계의 추처럼 왼쪽, 오른쪽, 왼쪽, 오른쪽 . . .  계속 왔다 갔다 하기    
+ 학교에 갔다가 집에 오기를 매일 반복하는 것    
+ 일주일(월, 화, 수, 목, 금, 토, 일)의 요일이 매주 반복되는 것    
+ 요일에 따라 수업시간표가 매주 반복되는 것    


# 순차와 선택구조가 함께 포함된 예
>> 순차적으로 수업을 진행하다가 4교시에 조건(비가 오는지 여부)에 따라 수업과목이 달라진다.    

![]({{ site.baseurl }}/assets/images/scratch/order_classes.png){: .img-thumbnail }

# 무지개 만들기
![]({{ site.baseurl }}/assets/images/scratch/order_01.png){: .img-thumbnail }

## 1.알고리즘 생각하기
```
무지개색의 순서 : 빨강 -> 주황 -> 노랑 -> 초록 -> 파랑 -> 남색 -> 보라

1. 무지개를 그릴 시작위치로 이동하기 (-200, -40) 
2. 펜 굵기 정하기 (20, 30, 40 등.. )
3. 펜 내리기
4. 펜 색깔을 빨강으로 정하기
5. 펜 움직이기 (100, 200 등 .. )
6. 다음색 시작위치로 이동하기 (-200, -20)
7. 펜 색깔을 주황으로 정하기
8. 펜 움직이기 (100, 200 등.. )
9. 다음색 위치로 이동하기 (-200, 0) 

... 이하 생략 ...
```

## 2.프로그램 구현하기

[예제보기](https://scratch.mit.edu/projects/619083044/){: .btn .btn-primary target="_blank" }    
+ 공버튼    
![]({{ site.baseurl }}/assets/images/scratch/order_02.png){: .img-thumbnail }
    

## 3.도전하기

![]({{ site.baseurl }}/assets/images/scratch/order_03.gif){: .img-thumbnail }    
    

```
1. 변수 리스트를 이용하여 일주일의 요일을 하나씩 말해주는 프로그램을 만들어 보자.
2. 월요일 ~ 일요일이 계속 반복되므로 반복구조를 이용하여 만들어 보자.
```

>> 이외 순차와 반복구문을 이용한 예제       
<div class="if-containerm">
<iframe src="https://scratch.mit.edu/projects/617168468/embed" allowtransparency="true" width="485" height="402" class="if-video"  frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

