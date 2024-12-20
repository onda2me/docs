---
title: 사고력 키우기 03 - 이진법을 이용한 암호만들기
---

### 이진법을 이용하여 암호를 만들어 보자.    

>> 알파벳을 10진수로 바꾼 뒤 다시 2진수로 변환하여 암호화 하고,     
2진수를 10진수로 변환한 뒤 다시 알파벳으로 만들어 암호를 해독 (= 복호화) 할 수 있다.    

# 2진수를 알파벳으로 변환
>> 2진수 : 01000, 00101, 01100, 01100, 01111     
10진수 : 8, 5, 12, 12, 15    
알파벳 : H, E, L, L, O    

# 알파벳 변환표    
**2진수 -> 10진수 -> 알파벳 변환표**    
![]({{ site.baseurl }}/assets/images/scratch/begin_data22.png){: .img-thumbnail }

# 2진수 변환 공식
>> 1000 => 1x8 => 8    
>> 1010 => 1x8 + 0x4 + 1x2 + 0 => 8 + 0 + 2 + 0 => 10    
>> 1111 => 1x8 + 1x4 + 1x2 + 1 => 8 + 4 + 2 + 1 => 15    
>>    
>> **dcba => dx8 + cx4 + bx2 + a**    

# 암호만들기 
```
암호만들기 순서 : 2진수 숫자 -> 10진수 숫자 -> 알파벳    

1. 공을 이용해 2진수를 만들기
2. 2진수를 10진수로 변환하여 10진수 변수에 저장하기
3. 10진수 숫자를 문자로 변환하여 보여주기
```

![]({{ site.baseurl }}/assets/images/scratch/begin_data20.png){: .img-thumbnail }

>> 실행해보기    
 
<div class="if-containerm">
<iframe src="https://scratch.mit.edu/projects/619908484/embed" allowtransparency="true" width="485" height="410" class="if-video"  frameborder="0" scrolling="no" allowfullscreen></iframe>
</div> 

## 1.알고리즘 생각하기

```
1. 5자리 2진수(11111 -> 31)가 되어야 알파벳 (26글자)을 모두 표현할 수 있다.
2. 5자리 2진수 위치에 맞게 공을 배치한다. 
3. 각 자리수에 해당하는 숫자를 저장할 변수를 만든다. (2진수 5자리 = 5개의 변수)
4. 10진수를 저장할 변수를 만든다. (2진수 5자리 숫자 -> 10진수 1개의 숫자로 변환)
5. 10진수에 해당하는 알파벳을 보여준다. 

Hint: 공의 자리수 = 공의 번호 = 5개변수 번호를 통일하면 알고리즘 과정이 쉽다.
```

## 2.프로그램 구현하기

[예제보기](https://scratch.mit.edu/projects/619908484/){: .btn .btn-primary target="_blank" }
[공 스프라이트 다운로드](/docs/assets/file/sprite/Ball1.sprite3){: .btn .btn-primary target="_blank" }
[알파벳 스프라이트 다운로드](/docs/assets/file/sprite/Glow-A.sprite3){: .btn .btn-primary target="_blank" }

    

+ 공버튼 :2진수를 10진수로 변환    
![]({{ site.baseurl }}/assets/images/scratch/begin_data25.png){: .img-thumbnail }    

+ 암호보기 버튼 : 10진수를 알파벳으로 변환    
![]({{ site.baseurl }}/assets/images/scratch/begin_data24.png){: .img-thumbnail }    

+ 알파벳 버튼 : 1~26 숫자에 해당하는 알파벳 모양 저장    
![]({{ site.baseurl }}/assets/images/scratch/begin_data23.png){: .img-thumbnail }    


## 3.도전하기
```
1. 이 프로그램과 반대로 알파벳 문자를 10진수로 변환 해보자.
2. 2개이상의 알파벳으로 구성된 단어를 보여주도록 해보자
```


<div class="if-containerm">
<iframe src="https://scratch.mit.edu/projects/609105285/embed" allowtransparency="true" width="485" height="410" class="if-video"  frameborder="0" scrolling="no" allowfullscreen></iframe>
</div> 
    