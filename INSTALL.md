아나콘다를 이용한 프로그래밍 환경 설정과 도커(docker) 이미지 생성 과정을 설명합니다.
설치환경에 따라 세세한 부분은 달라질 수 있지만 기본적으로 아래 과정을 수행하면 어렵지 않게 환경설정을 준비할 수 있습니다.

아래 설명은 윈도우(Windows) 10을 기준으로 합니다.
리눅스의 경우는 설치 방식만 다를 뿐 과정은 거의 동일하지만, 아래에서 설명하는 도커 이미지를 활용하는 방식을 추천합니다. 

### 윈도우 10 + 아나콘다(Anaconda) + Tensorflow 2(GPU 지원 가능)

* 환경설정 과정 및 주피터 노트북 실행
  1. [아나콘다(Anaconda)](https://www.anaconda.com/products/individual) 설치
  1. 이후 아래 참조 사이트 내용대로 GPU 드라이버 설치
  1. 터미널(terminal) 창애소 environment.yml 를 이용하여 아나콘다 환경 설정 완료
     ```bash
     $ conda env create -f environment.yml
     $ conda activate tf2
     $ python -m ipykernel install --user --name=python3
     ```
   1. 주피터 노트북 실행
      ```bash
      $ jupyter notebook
      ```
      브라우저가 자동으로 실행되지 않을 경우 수동으로 `localhost:8888` 방문 후 `index.ipynb` 노트북 선택.
     
* GPU 드라이버 설치 참조 사이트
  * 주(main): [TensorFlow: GPU support](https://www.tensorflow.org/install/gpu) (한글 선택 가능)
     * 주의사항: 텐서플로우2 부터는 cpu/gpu 용도 구분하지 않음.
     * "소프트웨어 요구사항"을 반드시 확인할 것
     * cuDNN SDK 사이트는 (무료) 계정 필요.
  * 보조: [텐서플로우 윈도우 10 GPU 설치](https://teddylee777.github.io/colab/tensorflow-gpu-install-windows)
     * 설치 순서 및 방법 참고용
     * 세부사항은 반드시 앞서 언급한 "소프트웨어 요구사항"의 내용대로 해야 함.
     * 특히 각 소프트웨어의 버전에 주의해야 함. 임의로 설치하면 안됨.

* 아나콘다 환경설정 사용법

### 도커(docker) 이미지 생성

