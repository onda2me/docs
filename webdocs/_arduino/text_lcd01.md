---
title: Begin Arduino - 텍스트 LCD 1602 12C
layout: code_import
---

>> 텍스트 LCD 1602 12C를 사용하여 Hello World를 출력해보자.


+ 텍스트 LCD 1602 12C    
![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_01.png)    

+ 텍스트 LCD 1602 12C의 특징    
    - I2C 인터페이스 사용하여 2개의 핀으로 LCD 동작 가능    
    - 가변저항을 통하여 LCD 밝기 조절 가능    

# 준비물 `| Preparations`
{: .alert .alert-success }

|우노보드 X 1개 | 텍스트 LCD 1602 12C X 1개 | 



# 알고리즘 `| Algorithm`
{: .alert .alert-success }

+ LCD를 연결하면 Hello World를 출력한다.    

# 회로도 `| Circuit diagram`
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_02_01.jpg){: .img-thumbnail style="width:450px; vertical-align: top;"} 
![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_02_02.jpg){: .img-thumbnail style="width:170px; vertical-align: top;"}     

# 코드 `| Code`
{: .alert .alert-success }
   
[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_lcd/sketch_lcd.ino){: .btn .btn-primary target="_blank" }

<pre id="show1" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_lcd/sketch_lcd.ino', 'show1', '500px');</script>


# 실행 `| Run`
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_03.jpg){: .img-thumbnail style="width:400px; vertical-align: top;"}

# 문제해결 `| Trouble Shooting`
{: .alert .alert-success }

>> LCD 화면이 나오지 않을 경우    

1.가변저항을 돌리면 저항값이 조정되면서 화면의 밝기가 변하면서 글씨가 나타난다.    
​![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_04.png){: .img-thumbnail style="width:500px; vertical-align: top;"}    

2.I2C Scanner를 이용하여 주소값을 알아낸 후 LCD 객체 선언 부분에서 이 주소값을 변경한다.    
 (I2C의 주소값은  부품마다 다를 수 있다.)    

![]({{ site.baseurl }}/assets/images/arduino/level1/lcd_05.png){: .img-thumbnail style="width:500px; vertical-align: top;"}


[LCD I2C Scanner 정보](http://playground.arduino.cc/Main/I2cScanner){: .btn .btn-primary target="_blank" } http://playground.arduino.cc/Main/I2cScanner       
    

[Scanner 아두이노 파일]({{ site.repo_ad}}/s1/sketch_i2c_scannin_g/sketch_i2c_scannin_g.ino){: .btn .btn-primary target="_blank" } {{ site.repo_ad}}/s1/sketch_i2c_scannin_g/sketch_i2c_scannin_g.ino
