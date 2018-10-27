
# 인공지능을 위한 수학 - 응용편 소스코드

TBD: 책 표지 이미지 넣을 것

'인공지능을 위한 수학'의 응용편 소스코드입니다.
* 출판사: 프리렉
* 저자: Ishikawa Akihiko
* 역자: 이진희, 신상재
* 발행일: 
* ISBN-13:


## 도서 판매처
* [yes24](TBD: 링크 넣을 것)
* [알라딘](TBD: 링크 넣을 것)


## 원서 정보
* 도서명: [人工知能プログラミングのための数学がわかる本](https://www.amazon.co.jp/dp/4046021969/)
* 출판사: KADOKAWA
* 저자: 石川 聡彦
* 발행일: 2018년 2월
* ISBN-13: 978-4046021960


## 소스 코드 
파이썬으로 만들어져 있으며 간단한 동작 확인을 주피터 노트북에서 확인할 수 있게 만들어졌습니다.

폴더 | 관련 장 | 내용
-- | -- | --
01_regression | 응용편 5장 인공지능에서 활용하기 Part 1 | 주택 추정하기
02_nlp | 응용편 6장 인공지능에서 활용하기 Part 2 | 문서 분류하기
03_deeplearning | 응용편 7장 인공지능에서 활용하기 Part 3 | 손글씨 인식하기


## 실습을 위한 필요 사양
- Python 3.4 이상
- Jupyter Notebook
- (주피터 노트북을 사용하지 않고 직접 pip를 사용하는 경우에는 'requirements.txt'를 참고)


## 실습 목표

제공되는 소스코드를 Jupyter Notebook에서 실행해보면서 책에서 배운 내용을 상기하는 것이 목적입니다.
인공지능에서 활용되는 수학적 개념이 실제로 어떻게 쓰이는지 체험해보시기 바랍니다.

이 책은 인공지능에 활용되는 수학적 개념과 활용되는 방식을 쉽게 감 잡으실 수 있도록 
실습에 필요한 Python과 Jupyter Notebook, Anaconda과 같은 환경에 대해서는 
실습에 필요한 최소한의 내용만 다루고 있습니다.

좀 더 자세한 내용을 알고 싶다면 Python과 Jupyter Notebook, Anaconda와 관련된 
별도의 책이나 온라인 문서를 참고하시기 바랍니다. 




## 실행 환경 구성 방법

실습의 편의를 위해 Python과 Jupyter Notebook을 직접 설치하여 사용하는 대신 Anaconda를 설치합니다.
Anaconda가 설치되면 Anaconda Navigator를 사용하여 Jupyter Notebook을 사용합니다.

### Anaconda 다운로드 및 설치

다음 경로에서 자신의 운영체제에 맞는 아나콘다를 설치합니다.

* [아나콘다 다운로드](https://www.anaconda.com/download/)

![](/images/installation/001.png)

다음은 Windows에서 설치하는 과정이나 MacOS에서 설치하는 과정도 크게 다르지 않습니다.
설치하는 버전은 다음과 같습니다. (2018년 10월 기준)

* Anaconda 5.3
* Python 3.7
* 64bit Graphical Installer (자신의 PC 환경에 맞는 비트를 선택)

다운로드 받은 파일은 다음과 같습니다.

![](/images/installation/003.png)

다운로드 받은 파일을 실행합니다.

![](/images/installation/004.png)

이후 기본 설정으로 설치를 진행합니다.

![](/images/installation/005.png)

![](/images/installation/006.png)

![](/images/installation/007.png)

![](/images/installation/008.png)

![](/images/installation/009.png)

![](/images/installation/010.png)

![](/images/installation/011.png)

### Anaconda Navigator 실행

설치가 완료되었으면 실행을 해봅니다. 'anaconda navigator'를 검색하면 실행 파일을 찾을 수 있습니다.

![](/images/installation/012.png)

### Jupyter Notebook 실행

Anaconda Navigator를 실행해보면 그 안에 Jupyter Notebook이 포함되어 있는 것을 알 수 있습니다.
Jupyter Notebook을 Lauch합니다.

![](/images/installation/013.png)

![](/images/installation/014.png)

이제 실습을 할 준비가 되었습니다.

### 실습할 소스파일 다운로드 및 Jupyter Notebook에서 읽기

Jupyter Notebook에서 실행할 소스파일을 다운로드 받습니다. 
Git으로 Clone 받는 것이 일반적이지만 직접 소스코드를 다운로드 받아도 상관없습니다.

TBD: 이미지 삽입

다운로드 받은 파일을 Jupyter Notebook에서 읽어들입니다.

TBD: 이미지 삽입

이제 실습을 해볼 준비가 되었습니다.

### 실습하기

각 소스코드는 다음과 같은 순서로 실행을 해주십시오. 

폴더 | 실행 순서
-- | -- 
01_regression | main.ipynb를 먼저 실행
02_nlp | cleaning.ipynb를 먼저 실행한 다음 main.ipynb를 실행
03_deeplearning | main.ipynb를 먼저 실행


