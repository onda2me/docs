---
title: Begin Arduino - LED 3색 신호등
layout: code_import
---

>> 아두이노 우노보드에 빨간색, 초록색, 노란색 3가지 색의 LED를 연결하여 신호등처럼 순서대로 켜졌다 꺼지도록  만들어 보자.


# 준비물 `| Preparations`
{: .alert .alert-info }

|우노보드 X 1개| LED X 3개 | 저항 X 3개|
|![]({{ site.baseurl }}/assets/images/arduino/level1/uno.png) | ![]({{ site.baseurl }}/assets/images/arduino/level1/led3.png) | ![]({{ site.baseurl }}/assets/images/arduino/level1/res3.png)  |

# 알고리즘 `| Algorithm`
{: .alert .alert-info }

빨간색 LED가 1초 켜졌다 꺼지면, 초록색 LED가 1초 켜졌다 꺼지고, 노란색 LED가 1초 켜졌다 꺼지기를 반복한다.    

+ 빨간색은 13번 핀, 초록색은 12번 핀, 노란색은 11번핀에 연결한다.
+ 회로는 전원 -> 저항 -> LED -> GND의 순서로 연결한다.

# 회로도 `| Circuit diagram`
{: .alert .alert-info }

![]({{ site.baseurl }}/assets/images/arduino/level1/led3_c1.png){: .img-thumbnail style="width:300px; vertical-align: top;"} 
![]({{ site.baseurl }}/assets/images/arduino/level1/led3_c2.png){: .img-thumbnail style="width:400px; vertical-align: top;"}  


# 코드 `| Code`
{: .alert .alert-info }
   
[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_led1/sketch_led3.ino){: .btn .btn-primary target="_blank" }

<pre id="show1" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_led3/sketch_led3.ino', 'show1', '500px');</script>


# 실행 `| Run`
{: .alert .alert-info }

<iframe width="544" height="306" src="https://serviceapi.nmv.naver.com/flash/convertIframeTag.nhn?vid=05549C14DD8E706A84616929DE2B9D715323&outKey=V129f5107b070ab440cd2ab2fadaed8d2f0a22ff25bd9e604dfe7ab2fadaed8d2f0a2" frameborder="no" scrolling="no" title="NaverVideo" allow="autoplay; gyroscope; accelerometer; encrypted-media" allowfullscreen></iframe>

