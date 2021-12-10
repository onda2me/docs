---
title: 사고력 키우기 02 - 기수법과 진법

---

### 기수법과 진법을 이용하여 프로그램을 만들어 보자.    
    

우리는 수를 셀때 10진수를 이용하지만, 컴퓨터는 모든 정보를 2진수로 처리한다.    
    

컴퓨터는 전기 신호의 스위치 형식(전기적 신호가 들어오면 1, 안 들어오면 0) 으로 작동하기에    
0과 1 두개의 숫자만 사용하여 문자, 숫자, 그림 등의 모든 정보를 저장한다.    

    

**숫자로 그림을 표현하는 방법**    
![]({{ site.baseurl }}/assets/images/scratch/begin_data11.png){: .img-thumbnail }    


# 기수법
**기호를 사용하여 수를 나타내는 방법**    

>> + 인도식 기수법    
인도식 기수법이 우리가 지금 쓰고 있는 숫자로 0, 1, 2, 3 ... 9 등의 기호로 수를 표현    
+ 로마식 기수법    
고대 로마에서 쓰인 기수법으로 I, II, III, IV, V, VI, VII, VIII, IX, X 등의 기호로 수를 표현    

# 진법
**수를 표기하는 기수법의 하나로 수를 셀 때, 자리수가 올라가는 단위를 기준으로 하는 셈법**    

>> + 10진법    
우리가 일반적으로 사용하는 1부터 9까지의 숫자를 사용하는 셈법     
+ 2진법    
0과 1,  두개의 숫자만으로 수를 표현하는 방법    
1(1), 10(2), 11(3), 100(4), 101(5), 110(6), 111(7), 1000(8), ... 

# 기수법과 진법표
![]({{ site.baseurl }}/assets/images/scratch/begin_data10.png){: .img-thumbnail }


# 2진수를 10진수로 변환하기
>> *2진수를 10진수로 변환하는 공식*    
>> dcba => dx8 + cx4 + bx2 + a    
>> 1010 => 1x8 + 0x4 + 1x2 + 0   =>   8 + 0 + 2 + 0 => 10    

![]({{ site.baseurl }}/assets/images/scratch/begin_data12.png){: .img-thumbnail }

## 1.알고리즘 생각하기

```
1. 2진수 자리수 위치에 맞게 공을 배치한다. 
2. 각 자리수에 해당하는 숫자를 저장할 변수를 만든다. (4자리 = 4개의 변수)
3. 10진수 계산 결과를 저장할 변수를 만든다.

Hint: 공의 자리수 = 공의 번호 = 4개변수 번호를 통일하면 알고리즘 계산이 쉽다.   
```

## 2.프로그램 구현하기

[예제보기](https://scratch.mit.edu/projects/608948325/){: .btn .btn-primary target="_blank" }    
    

![]({{ site.baseurl }}/assets/images/scratch/begin_data13.png){: .img-thumbnail }
![]({{ site.baseurl }}/assets/images/scratch/begin_data14.png){: .img-thumbnail }


## 3.도전하기
```
1. 공의 개수를 1개 추가하여 5자리 2진수를 10진수로 변환해 보자.

```


참고자료 :    

+ [https://terms.naver.com/entry.naver?docId=957709&cid=47308&categoryId=47308](https://terms.naver.com/entry.naver?docId=957709&cid=47308&categoryId=47308)    
+ [https://ko.wikipedia.org/wiki/%EC%9D%B4%EC%A7%84%EB%B2%95](https://ko.wikipedia.org/wiki/%EC%9D%B4%EC%A7%84%EB%B2%95) 
+ [https://terms.naver.com/entry.naver?docId=4397001&cid=60010&categoryId=60010&expCategoryId=60010](https://terms.naver.com/entry.naver?docId=4397001&cid=60010&categoryId=60010&expCategoryId=60010) 
