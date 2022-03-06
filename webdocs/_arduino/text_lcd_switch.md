---
title: Begin Arduino - 텍스트 LCD와 택트 스위치로 게임만들기
layout: code_import
---

>> 텍스트 LCD 1602 와 택트 스위치를 이용하여 간단한 게임을 만들어 보자.    
LCD화면의 오른쪽에서 왼쪽으로 폭탄(B) 이 이동하고, 폭탄(B)이 0에 가까이 오면 택트 스위치를 눌러 0을 점프시켜 폭탄을 피하는 게임이다.    
폭탄을 피하면 점수가 1점 올라간다.

+ 텍스트 LCD 1602 12C    
![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_01.png)    

+ DHT11 온습도 센서    
![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_01.jpg)    

# 준비물 `| Preparations`
{: .alert .alert-success }

| 우노보드 X 1개 | 텍스트 LCD 1602 12C X 1개 | DHT11 온습도 센서 |


# 알고리즘 `| Algorithm`
{: .alert .alert-success }

+ LCD에 온습도 센서로 측정한 온도와 습도 정보를 출력한다.    
![]({{ site.baseurl }}/assets/images/arduino/level1/lcdsensor_01.jpg)

# 회로도 `| Circuit diagram`
{: .alert .alert-success }



# 코드 `| Code`
{: .alert .alert-success }
   
[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_sensor_dht_lcd/sketch_sensor_dht_lcd.ino){: .btn .btn-primary target="_blank" }

<pre id="show1" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_sensor_dht_lcd/sketch_sensor_dht_lcd.ino', 'show1', '500px');</script>


# 실행 `| Run`
{: .alert .alert-success }

<iframe width="544" height="306" src="https://serviceapi.nmv.naver.com/flash/convertIframeTag.nhn?vid=3825353A645EA0065A5DB1B943DB31A9A2C7&outKey=V12465c06e832ed444b92d393392697dfd470ebbaf66814c08e15d393392697dfd470" frameborder="no" scrolling="no" title="NaverVideo" allow="autoplay; gyroscope; accelerometer; encrypted-media" allowfullscreen></iframe>


# 문제해결 `| Trouble Shooting`
{: .alert .alert-success }

