---
title: 사고력 키우기 08 - 연산
---
# 연산 블럭
## 사칙 연산
>> '+', '-', '*', '/' 의 사칙연산을 수행하는 명령블럭     

![]({{ site.baseurl }}/assets/images/scratch/oper_01.png){: .img-thumbnail }
![]({{ site.baseurl }}/assets/images/scratch/oper_011.png){: .img-thumbnail }    

## 비교 연산
>> 크다, 작다, 같다를 비교하는 명령블럭     

![]({{ site.baseurl }}/assets/images/scratch/oper_02.png){: .img-thumbnail }

## 논리 연산
>> 참, 거짓에 대해 AND, OR 연산을 수행하는 명령블럭     
![]({{ site.baseurl }}/assets/images/scratch/oper_03.png){: .img-thumbnail }

## 문자열 연산
>> 문자열을 연결하거나, 문자열의 길이를 다루는 명령블럭     
![]({{ site.baseurl }}/assets/images/scratch/oper_05.png){: .img-thumbnail }

# 수학실력 테스트 게임
>> 연산블럭과 제어블럭을 이용하여 수학문제를 만들어 실력을 테스트하는 게임을 만들어 보자    

![]({{ site.baseurl }}/assets/images/scratch/oper_01.gif){: .img-thumbnail style="width: 400px"}




## 1.알고리즘 생각하기
```
1) 변수 만들기
    1. 1 ~ 9 사이의 난수값을 가지는 변수 2개 (앞의수와 뒤의수 각각 저장)
    2. 1 ~ 4 사의의 난수값을 가지는 연산자 (1: +, 2:-, 3:*, 4:/)
    3. 문제수를 저장할 변수 1개
    4. 정답수를 저장할 변수 1개
    5. 연산결과를 저장할 변수 1개
2) 변수 초기화
    1. 숫자1 초기화 (1 ~ 9 사이의 난수값 )
    2. 숫자2 초기화 (1 ~ 9 사이의 난수값 )
    3. 연산자 초기화 (1 ~ 4 사이의 난수값 )
3) 문제내기와 정답계산
    1. 연산자 변수값에 따라 연산자 스프라이트 모양 바꾸기
    2. 숫자와 연산자에 해당하는 결과 계산하기
    3. 문제수 +1 
    4. "정답을 입력하세요" 라고 묻고 기다리기
4) 정답체크
    1. 정답이 맞을 경우 정답수 +1 
5) 반복하기
    2) ~ 4)의 과정 반복하기
```

## 2.프로그램 구현하기
[예제보기](https://scratch.mit.edu/projects/626460384/){: .btn .btn-primary target="_blank" }    

![]({{ site.baseurl }}/assets/images/scratch/oper_07.png){: .img-thumbnail }

## 3.실행하기
<div class="if-containerm">
<iframe src="https://scratch.mit.edu/projects/626460384/embed" allowtransparency="true" width="485" height="402" class="if-video"  frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>


