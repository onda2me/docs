---
title: Begin Arduino - LED 깜박이기

---

>> 스케치와 S4A 에서 간단하게 아두이노 프로그램을 개발하는 방법에 대해 알아보자.

# LED 란?
**LED (Light Emitting Diode, 발광 다이오드) 란?**    
LED는 전기 에너지를 빛 에너지로 변환한 발광 다이오드이다.     
LED는 2개의 전극단자로 구성되어 있는데, 긴 단자쪽이 + (Anode : 양극), 짧은 단자쪽은 - (Cathode : 음극) 이다.
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/led.jpg){: .img-thumbnail style="width:300px"}


LED의 스펙보다 많은 전류가 흐르게 되면 LED가 파손될 수 있으므로 저항을 달아 전류를 조정해주어야 한다.    
저항을 고를 때에는 옴의법칙을 이용하여 저항값을 선정한다.    
정확한 수치의 저항이 없을 경우 근사치 저항을 사용하면 된다.    

**옴의법칙**    
V(전압) = I (전류) x R(저항)    
{: .alert .alert-success }

대부분의 아두이노 우노보드의 공급전압은 5V 이고, LED의 필요전압은 2V, 소모전류는 10mV (= 0.01A) 이다.     

**필요저항**    
R(저항) = V(전압) / I(전류)    
필요저항 = (보드 공급전압 - LED 필요전압 ) / 소모 전류    
**300 Ω** = (5V - 2V) / 0.01A     
{: .alert .alert-success }


# LED 깜박이기 예제    
>> LED가 1초동안 켜졌다가 1초동안 꺼졌다가를 반복하게 해 보자.    

## 준비물 `| Preparations`
{: .alert .alert-success }   

|우노보드 X 1개| LED X 1개 | 저항 X 1개|    

## 회로도 `| Circuit diagram`
{: .alert .alert-success }
![]({{ site.baseurl }}/assets/images/arduino/level1/led1_01.png){: .img-thumbnail style="width:350px"}
![]({{ site.baseurl }}/assets/images/arduino/level1/led1_02.jpg){: .img-thumbnail style="width:350px"}

## 알고리즘 `| Algorithm`
{: .alert .alert-success }

빨간색 LED가 1초동안 켜졌다가 1초동안 꺼졌다가를 반복한다.    

+ 빨간색 LED는 1번 디지털핀에 연결한다.
+ 회로는 전원 -> 저항 -> LED -> GND의 순서로 연결한다.

## 코드 `| Code`
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/led1_03.png){: .img-thumbnail style="width:350px"}

## 실행 `| Run`
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/led1_blink3.gif){: .img-thumbnail}   


