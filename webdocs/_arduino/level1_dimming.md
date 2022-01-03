---
title: Begin Arduino - LED 밝기 조절
layout: code_import
---

>> 아두이노 보드의 아날로그 핀에 LED를 연결하여 LED의 밝기가 서서히 밝아졌다가 서서히 어두워지도록 밝기를 조절하여 보자.


# 준비물 `| Preparations`
{: .alert .alert-success }

|우노보드 X 1개| LED X 1개 | 저항 X 1개|


# 회로도 `| Circuit diagram`
{: .alert .alert-success }

![]({{ site.baseurl }}/assets/images/arduino/level1/led_dimming1.png){: .img-thumbnail} 
![]({{ site.baseurl }}/assets/images/arduino/level1/led_dimming2.png){: .img-thumbnail}  

# 알고리즘 `| Algorithm`
{: .alert .alert-success }

빨간색 LED가 밝아졌다 어두워졌다를 반복한다.    

+ 빨간색 LED는 6번 (아날로그) 핀에 연결한다.
+ 회로는 전원 -> 저항 -> LED -> GND의 순서로 연결한다.
+ 조금씩 밝아지기, 조금씩 어두워지기를 for문을 이용하여 만든다.


# 코드 `| Code`
{: .alert .alert-success }
   

+ S4A 코드   
![]({{ site.baseurl }}/assets/images/arduino/level1/led_dimming3.png){: .img-thumbnail}  


+ Sketch 코드  
[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_led1/sketch_led1_dimming.ino/sketch_led1_dimming.ino.ino){: .btn .btn-primary target="_blank" }
<pre id="show1" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_led1/sketch_led1_dimming.ino/sketch_led1_dimming.ino.ino', 'show1', '300px');</script>


# 실행 `| Run`
{: .alert .alert-success }

<iframe width="544" height="306" src="https://serviceapi.nmv.naver.com/flash/convertIframeTag.nhn?vid=AC513032CD803FDCE214E6266BF15086C11A&outKey=V129c6a860460b7c67dce12d4408fa70512e43a1ccda85efaf50712d4408fa70512e4" frameborder="no" scrolling="no" title="NaverVideo" allow="autoplay; gyroscope; accelerometer; encrypted-media" allowfullscreen></iframe>

