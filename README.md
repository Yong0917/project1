# 프로젝트 미정

# 한림대학교 소프트웨어융합대학
--- 

멤버 이름 및 담당 파트 소개
* **20165138 신승용**   : 코드 구현
* 20165141 안정희 : 코드 구현 및 발표

프로젝트 소개
* ubuntu 가상 머신에서 python과 pycharm을 이용해서 영상처리하는 프로그램.
* 먼저 요즘 코로나시대에서 얼굴을 인식해 온도를 재는 게 많아졌다. 그래서 얼굴을 인식하는 프로그램을 통해 단순히 얼굴을 검출하는게 아니라 다양한 시도를 했다.
* 얼굴을 검출하여 얼굴 영역만 따로 잘라내서 잘라낸 영역을 블러링하는 기술을 사용한다. 
* 웃는 얼굴은 먼저 얼굴을 검출하고 랜드마크를 검출해 윗입술과 아래사이의 거리를 임계치로 웃는 얼굴을 판단한다. 또한 그 영상을 마스킹해서 heart나 별등 여러가지 이미지를 마스킹해서 삽입해준다.
* 이미지를 받아들여 carrtoon 카툰화 하는 프로그램
* 영상을 받아들여 왼쪽마우스클릭하면 playing, 오른쪽 마우스 클리하면 stop 하게 하고 영상을 스케치화하는 프로그램 

개발 내용 소개
* 영상이나 사진을 받아드리면 얼굴을 인식하고 또한 그 검출된 모자이크를 할 수 있다.
* 얼굴 검출을 통해 웃는 얼굴을 인식해 입 주변에 이미지 삽입 (하트, 별표 등등)
* 얼굴에 있는 눈을 인식해 선글라스 삽입하는 프로그램
* 영상이나 사진을 스케치화 하는 프로그램

-----------

프로젝트 결과물 소개
1. 사진을 받아들이면 1차적으로 얼굴 검출을 한다. 다음으로 얼굴에 대한 랜드마크를 검출해 윗입술과 아랫입술 사이의 거리를 임계치로 계산해 웃는 얼굴을 판단한다. smile삽입
<img width = "700" src = "https://user-images.githubusercontent.com/65889807/101455157-73b30100-3975-11eb-9309-b596fd9af7d6.png">

2. 위 프로그램과 같고 smile 대신 하트이미지를 마스킹하여 웃는입술 옆에 삽입
<img width = "700" src = "https://user-images.githubusercontent.com/65889807/101455602-2f743080-3976-11eb-8919-e7ed5db74d7c.png">

3. 얼굴을 검출해 얼굴 영역만 블러링(모자이크) 하는 프로그램
<img width = "700" src = "https://user-images.githubusercontent.com/65889807/101455579-27b48c00-3976-11eb-81a6-c5c0b146fbdf.png">

4. 얼굴을 검출하고 눈의 위치를 판단하여 선글라스를 씌어주는 프로그램. 이때 선글라스도 마스킹 해줘야된다.
<div>
<img width = "500" src = "https://user-images.githubusercontent.com/65889807/101455524-10759e80-3976-11eb-8416-4be8a0717b4a.png">
<img width = "500" src = "https://user-images.githubusercontent.com/65889807/101455543-1a979d00-3976-11eb-9035-4230216c5630.png">
</div>
