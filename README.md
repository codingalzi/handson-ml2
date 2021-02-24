## 핸즈온 머신러닝 (2판) 정리 노트북

오렐리앙 제롱(Aur&eacute;lien G&eacute;ron)의 핸즈온 머신러닝(2판)의 주피터 노트북에 설명이 추가됨.

<div align="center"><img src="https://www.hanbit.co.kr/data/books/B7033438574_l.jpg" title="book-kr" width="200"></div>

### 강의 슬라이드

* 참조: [핸즈온 머신러닝(2판) 강의노트](http://formal.hknu.ac.kr/handson-ml2/)

### 주피터 노트북 학습

#### 온라인

추천: [구글 코랩 활용 ](https://colab.research.google.com/github/liganega/handson-ml2/blob/master/)
<a href="https://colab.research.google.com/github/liganega/handson-ml2/blob/master/"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

*주의: 온라인 상에서 작업한 내용은 저장되지 않으며, 따라서 먼저 자신의 계정으로 사본을 만들어야 함.*

#### 오프라인

추천 활용법: [GitHub:handson-ml2](https://github.com/liganega/handson-ml2)를 복제한 후에 도커 활용.
도커 이미지는 아래 방법으로 구할 수 있음:
- 방법1: 저자 제공 [도커 이미지](https://hub.docker.com/r/ageron/handson-ml2/tags) 사용
    * latest 또는 2020.03 Tag 사용 가능.
    * GPU 미지원.
- 방법 2: [Deepo](https://github.com/ufoym/deepo)에서 도커 이미지 활용
    * GPU 지원
    * 핸즈온 머신러닝 주피터 노트북 실행에 필요한 추가 패키지 설치 필요
- 방법 3: 윈도우 10 + 아나콘다 + Tensorflow 2(GPU 지원)
    * 준비사항
        * MS의 [Visual Studio](https://visualstudio.microsoft.com/) 설치
        * [Anaconda](https://www.anaconda.com/products/individual) 설치
        * 이후 아래 참조 사이트 내용대로 설치 진행
        * 주의사항: 텐서플로우2 부터는 cpu/gpu 용도 구분하지 않음.
    * 참조 사이트:
        * 주: [TensorFlow: GPU support](https://www.tensorflow.org/install/gpu)
            (한글 선택 가능)
            * "소프트웨어 요구사항"을 반드시 확인할 것
            * cuDNN SDK 사이트는 (무료) 계정 필요.
        * 보조: [텐서플로우 윈도우 10 GPU 설치](https://teddylee777.github.io/colab/tensorflow-gpu-install-windows)
            * 설치 순서 및 방법 참고용
            * 세부사항은 반드시 앞서 언급한 "소프트웨어 요구사항"의 내용대로 해야 함.
            * 특히 각 소프트웨어의 버전에 주의해야 함. 임의로 설치하면 안됨.
   
### 감사의 글

자료를 공개한 저자 오렐리앙 제롱과 강의자료를 지원한 한빛아카데미에게 진심어린 감사를 전합니다.
