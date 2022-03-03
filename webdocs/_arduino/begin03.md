---
title: Begin Arduino - 아두이노 개발환경 설정
---

# 아두이노 개발환경 설정   

>> 프로그램 개발을 위해 아두이노 보드를 설정하고, 펌웨어 업데이트를 해보자

# + 스케치 개발환경    

### 1. 아두이노 보드 USB로 연결

아두이노 보드에 케이블을 입력하고, USB 케이블은 PC에 연결한다.

![]({{ site.baseurl }}/assets/images/arduino/power_line.jpg){: .img-thumbnail }
### 2. 스케치 실행    
윈도우 프로그램에서 스케치를 실행한다.    

![]({{ site.baseurl }}/assets/images/arduino/arduino_icon.png){: .img-thumbnail }

### 3. 보드 선택    
도구(툴) - 보드 - Arduino Uno 선택되었는지 확인한다.   

![]({{ site.baseurl }}/assets/images/arduino/board_01.png){: .img-thumbnail style="width:600px"}

### 4. 포트 선택   
도구(툴) - 포트 에서 COM 포트가 선택되었는지 확인한다.    

![]({{ site.baseurl }}/assets/images/arduino/board_02.png){: .img-thumbnail style="width:600px"}   

### 5. 예제 실행
파일 - 예제 - 01.Basics - Blink를 선택하여 예제파일을 연다.

![]({{ site.baseurl }}/assets/images/arduino/board_03.png){: .img-thumbnail style="width:600px"}   

### 6. 보드인식 완료
13번 옆의 LED 등이 깜박거리면 보드 인식이 완료되었다.

![]({{ site.baseurl }}/assets/images/arduino/led1_blink2.gif){: .img-thumbnail style="width:600px"}   

# + S4A 개발환경
>> 스케치에 S4A 통신 펌웨어 업데이트

S4A는 아두이노(스케치)와 통신을 하며 블록코딩을 실행하기에 최초 한 번은 아두이노에 통신을 위한 펌웨어를 설치 해야한다.    
펌웨어를 설치하지 않고 S4A를 실행하면 **보드검색 중** 으로 아두이노 보드 인식이 되지 않는다.    

![]({{ site.baseurl }}/assets/images/arduino/board_search.png){: .img-thumbnail style="width:300px"}

### 1. 펌웨어 다운로드

[S4A 홈페이지](http://s4a.cat/){: .btn .btn-primary target="_blank" } 에 접속하여 
**`Download our firmware from here`** 클릭하여 S4AFirmware16.ino 다운 받는다.    

![]({{ site.baseurl }}/assets/images/arduino/down_s4a02_2.png){: .img-thumbnail style="width:600px"}

### 2. 펌웨어 설치
다운로드 후 파일열기를 클릭하면 스케치가 실행되며 파일이 열린다.    
아래와 같이 메세지가 뜨면 확인을 선택한다.    

![]({{ site.baseurl }}/assets/images/arduino/down_s4a05_1.png){: .img-thumbnail style="width:600px"}

### 3. 보드 인식완료
![]({{ site.baseurl }}/assets/images/arduino/board_04.png){: .img-thumbnail style="width:600px"}

