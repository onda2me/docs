---
title: Begin Arduino - 피에조 부저
layout: code_import
---

>> 피에조 부저를 이용하여 음악을 연주해보자.

*피에조 부저(Buzzer)*는 전기의 압력으로 얇은 판에 떨림을 일으켜 소리를 내는 방식이다.    
소리가 크지 않다는 단점이 있지만, 주파수를 이용하여 음의 높이를 조절하여 음악 연주도 가능하다.
{: .notice }

![]({{ site.baseurl }}/assets/images/arduino/level1/buzzer_10_01.jpg)

+ 피에조 부저의 음높이     

| 도 | 레 | 미 | 파 | 솔 | 라 | 시 | 도 | 
| 262 | 294 | 330 | 349 | 392 | 440 | 494 | 523 | 

+ [음높이 설정하는 방법](https://www.arduino.cc/reference/en/){: .btn .btn-primary target="_blank" } 보기    

![]({{ site.baseurl }}/assets/images/arduino/level1/arduino_function.png){: .img-thumbnail style="width:600px;"}    
# 피에조 부저 

## 준비물 `| Preparations`
{: .alert .alert-success }
 
|우노보드 X 1개 | 피에조 부저 X 1개 |  


## 알고리즘 `| Algorithm`
{: .alert .alert-success }

+ 피에노 부저를 연결하여 도, 레, 미, 파, 솔, 라, 시, 도 음을 연주한다.    

## 회로도 `| Circuit diagram`
{: .alert .alert-success }
    
![]({{ site.baseurl }}/assets/images/arduino/level1/buzzer_10_02.png){: .img-thumbnail style="width:200px;"} 
    

| 아두이노 보드 | 피에조 부저 |  
| GND | - |  
| A9 | +  |  


## 코드 `| Code`
{: .alert .alert-success }


[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_buzzer_doremi/sketch_buzzer_doremi.ino){: .btn .btn-primary target="_blank" }

<pre id="show1" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_buzzer_doremi/sketch_buzzer_doremi.ino', 'show1', '500px');</script>


## 실행 `| Run`
{: .alert .alert-success }
<iframe width="560" height="315" src="https://www.youtube.com/embed/U8lzo1Y_nX4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# -----------------------    

# 피에조 부저 음악연주

>> 피에노 부저를 이용하여 '학교종이 땡땡땡'을 연주해 보자.    

## 코드 `| Code`
{: .alert .alert-success }
   

[GITHUB 소스보기]({{ site.repo_ad}}/s1/sketch_buzzer_music/sketch_buzzer_music.ino){: .btn .btn-primary target="_blank" }

<pre id="show2" class="show-json-from-git">소스로딩 실패</pre>
<script>showJsonFromGit('{{ site.repo_ad_raw }}/s1/sketch_buzzer_music/sketch_buzzer_music.ino', 'show2', '500px');</script>


## 실행 `| Run`
{: .alert .alert-success }

<iframe width="560" height="315" src="https://www.youtube.com/embed/MM0K4SxVdOk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

