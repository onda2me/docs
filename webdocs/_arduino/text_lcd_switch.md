---
title: Begin Arduino - 텍스트 LCD와 택트 스위치로 게임만들기
layout: code_import
---

<!-- # 텍스트 LCD 1602 와 택트 스위치를 이용하여 간단한 게임을 만들어 보자.     -->

## 게임설명
+ LCD 화면의 오른쪽에서 왼쪽으로 폭탄(B)이 이동하고,   
+ 택트 스위치를 누르면 캐릭터(0)이 점프하며, 
+ 폭탄(B)이 캐릭터(0)에 가까이 오면 택트 스위치를 눌러 점프시켜 폭탄을 피하는 게임이다.    
+ 폭탄(B)을 피하면 점수가 1점 올라가고,
+ 폭탄(B)을 피하지 못하면 게임이 종료된다.

### 텍스트 LCD 1602 12C
+ I2C 인터페이스 사용하여 2개의 핀으로 LCD 동작 가능
+ 가변저항을 통하여 LCD 밝기 조절 가능 

![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_01.png){: style="width:450px" .img-thumbnail}    
![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_03.jpg){: style="width:450px" .img-thumbnail}    
   

### 택트 스위치    
![]({{ site.baseurl }}/assets/images/arduino/level1/switch_01.png){: style="width:150px" .img-thumbnail}       

## 준비물 `| Preparations`
{: .alert .alert-success .font-weight-bold}

|  준 비 물 | 수 량 | 
| 우노보드 | X 1개 | 
| 텍스트 LCD 1602 12C | X 1개 | 
| 택트 스위치 |  X 1개 |


## 알고리즘 `| Algorithm`
{: .alert .alert-success .font-weight-bold}

+ 게임준비   
![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_11.jpg)

## 회로도 `| Circuit diagram`
{: .alert .alert-success .font-weight-bold}



## 코드 `| Code`
{: .alert .alert-success .font-weight-bold}
   
[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_lcd_switch2/sketch_lcd_switch2.ino){: .btn .btn-primary target="_blank" }

<pre id="show1" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_lcd_switch2/sketch_lcd_switch2.ino', 'show1', '500px');</script>


## 실행 `| Run`
{: .alert .alert-success .font-weight-bold}

<iframe width="544" height="306" src="https://serviceapi.nmv.naver.com/flash/convertIframeTag.nhn?vid=8CFA857B892E587625E08FAC19A6E0BB2F43&outKey=V128716c3870d3edf4e96d9da3dc67eb9f2d67db988af20f8e639d9da3dc67eb9f2d6" frameborder="no" scrolling="no" title="NaverVideo" allow="autoplay; gyroscope; accelerometer; encrypted-media" allowfullscreen></iframe>


# 문제해결 `| Trouble Shooting`
{: .alert .alert-success .font-weight-bold}

