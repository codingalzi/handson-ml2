오렐리앙 제롱(Aur&eacute;lien G&eacute;ron)의 핸즈온 머신러닝(2판)의 주피터 노트북과 강의 슬라이드 제공

#### 감사의 글

자료를 공개한 저자 오렐리앙 제롱과 강의자료를 지원한 한빛아카데미에게 진심어린 감사를 전합니다.

### 슬라이드 목차

- 1장 한 눈에 보는 머신러닝 &nbsp;
    [[html]](./slides/handson-ml2-01.slides.html)
    [[pdf]](./slides/handson-ml2-01-slides.pdf)
- 2장 머신러닝 프로젝트 처음부터 끝까지 &nbsp;
    [[html]](./slides/handson-ml2-02.slides.html)
    [[pdf]](./slides/handson-ml2-02-slides.pdf)
- 3장 분류 &nbsp;
    [[html]](./slides/handson-ml2-03.slides.html)
    [[pdf]](./slides/handson-ml2-03-slides.pdf)
- 4장 모델 훈련 &nbsp;
    [[html]](./slides/handson-ml2-04.slides.html)
    [[pdf]](./slides/handson-ml2-04-slides.pdf)
- 5장 서포트벡터머신 &nbsp;
    [[html]](./slides/handson-ml2-05.slides.html)
    [[pdf]](./slides/handson-ml2-05-slides.pdf)
- 6장 의사결정나무 &nbsp;
    [[html]](./slides/handson-ml2-06.slides.html)
    [[pdf]](./slides/handson-ml2-06-slides.pdf)
- 7장 앙상블 학습과 랜덤포레스트 &nbsp;
    [[html]](./slides/handson-ml2-07.slides.html)
    [[pdf]](./slides/handson-ml2-07-slides.pdf)
- 8장 차원축소 &nbsp;
    [[html]](./slides/handson-ml2-08.slides.html)
    [[pdf]](./slides/handson-ml2-08-slides.pdf)
- 9장 비지도학습 &nbsp;
    [[html]](./slides/handson-ml2-09.slides.html)
    [[pdf]](./slides/handson-ml2-09-slides.pdf)
- 10장 케라스를 사용한 인공신경망 소개 &nbsp;
    [[html]](./slides/handson-ml2-10.slides.html)
    [[pdf]](./slides/handson-ml2-10-slides.pdf)
- 11장 심층신경망 훈련 &nbsp;
    [[html]](./slides/handson-ml2-11.slides.html)
    [[pdf]](./slides/handson-ml2-11-slides.pdf)
- 14장 합성곱신경망: 컴퓨터비전
    - 1부 &nbsp;
        [[html]](./slides/handson-ml2-14-1.slides.html)
        [[pdf]](./slides/handson-ml2-14-1-slides.pdf)
    - 2부 &nbsp;
        [[html]](./slides/handson-ml2-14-2.slides.html)
        [[pdf]](./slides/handson-ml2-14-2-slides.pdf)
- 15장 RNN과 CNN 활용: 순차데이터 처리 &nbsp;
    [[html]](./slides/handson-ml2-15.slides.html)
    [[pdf]](./slides/handson-ml2-15-slides.pdf)
- 18장 강화학습
    - 1부 &nbsp;
        [[html]](./slides/handson-ml2-18-1.slides.html)
        [[pdf]](./slides/handson-ml2-18-1-slides.pdf)
    - 2부 &nbsp;
        [[html]](./slides/handson-ml2-18-2.slides.html)
        [[pdf]](./slides/handson-ml2-18-2-slides.pdf)
- ...

*주의: HTML을 이용하여 슬라이드를 사용할 경우 전진과 후진을 `space`와 `shift+space` 키를 활용할 것.*

### 딥러닝 훈련 코드 모음집

- [Keras Code Examples](https://keras.io/examples/)
    - 다양한 주제에 대한 딥러닝 모델 구현 및 훈련방법 소개

### 주피터 노트북 학습

#### 온라인

추천: [구글 코랩 활용 ](https://colab.research.google.com/github/liganega/handson-ml2/blob/master/)
<a href="https://colab.research.google.com/github/liganega/handson-ml2/blob/master/"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

*주의: 온라인 상에서 작업한 내용은 저장되지 않으며, 따라서 먼저 자신의 계정으로 사본을 만들어야 함.

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

---

#### 깃허브 마크다운 사용법 

깃허브에서 사용되는 마크다운에 자세한 안내는 [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/) 참조.
