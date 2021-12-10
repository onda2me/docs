---
title: 사고력 키우기 03 - 이진법을 이용한 암호만들기
---

### **이진법을 이용하여 암호를 만들어 보자.**    

알파벳을 10진수로 바꾼 뒤 다시 2진수로 변환하여 암호를 만들고 (암호화), 
2진수를 10진수로 변환한 뒤 다시 알파벳으로 만들어 암호를 해독 (복호화) 할 수 있다.

**2진수를 알파벳으로 변환하는 과정**
>> 2진수 :     
>> 10진수 : 8, 5, 12, 12, 15    
>> 알파벳 : H, E, L, L, O    

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
1. 공을 이용해 2진수를 만들기
2. 2진수를 10진수로 변환하여 암호리스트에 저장하기
3. 암호보기를 클릭하면 암호리스트에 저장된 숫자를 문자로 보여주기
```

![]({{ site.baseurl }}/assets/images/scratch/begin_data21.png){: .img-thumbnail }


## 1.알고리즘 생각하기

```
1. 5자리 2진수(11111 -> 31)가 되어야 알파벳 (26글자)를 표현할 수 있다.
2. 5자리 2진수 위치에 맞게 공을 배치한다. 
3. 각 자리수에 해당하는 숫자를 저장할 변수를 만든다. (5자리 = 5개의 변수)
4. 10진수 계산 결과를 저장할 변수를 만든다. 

Hint: 공의 자리수 = 공의 번호 = 5개변수 번호를 통일하면 알고리즘 과정이 쉽다.
```



## 2.프로그램 구현하기

[예제보기](https://scratch.mit.edu/projects/609105285/){: .btn .btn-primary target="_blank" }    
    

+ 공버튼 :2진수를 10진수로 변환    
![]({{ site.baseurl }}/assets/images/scratch/begin_data25.png){: .img-thumbnail }    

+ 암호보기 버튼 : 10진수를 알파벳으로 변환    
![]({{ site.baseurl }}/assets/images/scratch/begin_data24.png){: .img-thumbnail }    

+ 알파벳 버튼 : 1~26 숫자에 해당하는 알파벳 모양 저장    
![]({{ site.baseurl }}/assets/images/scratch/begin_data23.png){: .img-thumbnail }    


## 3.도전하기
```
1. 이 프로그램의 반대인 알파벳 문자를 2진수로 변환 해보자.
```

    