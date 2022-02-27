---
title: Begin Arduino - 온/습도 센서
layout: code_import
---


>> **온도**는 뜨겁고 찬 정도를 수치로 나타낸 것이고, **습도**는 공기중에 포함된 수증기의 비율이다.    
**섭씨 온도**는 물의 어는점을 0°C로 끓는점을 100°C로 하여 그사이의 값을 수치화하여 나타내는 방식이다.    
**상대 습도**는 대기중의 수증기가 꽉 차서 더이상 수증기가 들어갈 수 없는 상태를 습도 100% 으로 하고  습도의 농도를 0 ~ 100 % 사이의 값으로 수치화한 방식을 상대습도 라고 한다.    
(습도가 100% 인 상태에 수증기를 추가하면 안개가 낀 것처럼 뿌연 물방울이 생긴다)    

>> 이번 예제에서 사용한 온/습도 센서는 DHT11로  1000원대의 가격으로 가성비가 좋은 센서이다.    

+ DHT11 온습도 센서    
![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_01.jpg)    

+ 센서의 특징
    - 가격이 싸다
    - 3 ~ 5 V 전압 사용 
    - 20 ~ 80 % 습도 측정 
    - 0 ~ 50 °C  온도 측정 (오차범위 ±2°C) 
+ 핀 연결    
    - GND -> GND 
    - DATA -> Digital PIN (2) 
    - VCC -> 3.3V   


# 준비물 `| Preparations`
{: .alert .alert-success }

|우노보드 X 1개| 온습도센서 X 1개 | 
|![]({{ site.baseurl }}/assets/images/arduino/level1/uno.png) | ![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_01.jpg) | |


# 알고리즘 `| Algorithm`
{: .alert .alert-success }

+ 온습도 센서를 연결하면, 현재의 온/습도 정보를 시리얼창에 출력한다.    
+ 빨간색은 전원, 노란색은 2번 아날로그핀, 검정색은 그라운드에 연결한다.   
 

# 회로도 `| Circuit diagram`
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_011.jpg){: .img-thumbnail style="width:400px;"}     

# 코드 `| Code`
{: .alert .alert-success }
   
[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_sensor_dht/sketch_sensor_dht.ino){: .btn .btn-primary target="_blank" }

<pre id="show1" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_sensor_dht/sketch_sensor_dht.ino', 'show1', '500px');</script>


# 실행 `| Run`
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_02.jpg){: .img-thumbnail style="width:320px; vertical-align: top;"}
![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_03.png){: .img-thumbnail style="width:500px; vertical-align: top;"}

# 문제해결 `| Trouble Shooting`
{: .alert .alert-success }

+ 업로드를 할때 아래와 같은 오류코드가 뜨면 DHT 헤더 정보가 없다는 것이다.    
+ DHT를 사용하기 위해 DHT 관련 라이브러리를 추가해야 한다.    


1. DHT로 검색하여 DHT sensor를 설치한다.    
​![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_04.png){: .img-thumbnail style="width:500px; vertical-align: top;"}

2. Adafruit Unified Sensor 를 설치한다.    
![]({{ site.baseurl }}/assets/images/arduino/level1/sensor_01_05.png){: .img-thumbnail style="width:500px; vertical-align: top;"}
