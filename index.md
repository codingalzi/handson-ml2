[&lt;핸즈온 머신러닝(2판)&gt;의 소스코드](https://github.com/ageron/handson-ml2)를 
담은 주피터 노트북을 바탕으로 머신러닝/딥러닝의 기초를 소개합니다.

### 감사의 글

자료를 공개한 저자 오렐리앙 제롱(Aur&eacute;lien G&eacute;ron)과 강의자료를 지원한 한빛아카데미에게 진심어린 감사를 전합니다.

### 목차

| 주제 | 구분 | 링크 |
| :--: | :--: | :--: |
| 강의소개 | 슬라이드 | [&#x1F4F1;](./slides/handson-ml-00.slides.html) &nbsp; [&#x1F4BB;](./slides/handson-ml-00-slides.pdf) |
| 한 눈에 보는 머신러닝 | 슬라이드 | [&#x1F4F1;](./slides/handson-ml-01.slides.html) &nbsp; [&#x1F4BB;](./slides/handson-ml-01-slides.pdf) |
|                  | 주피터 노트북 | [&#x1F578;](./notebooks/handson-ml-01.html) &nbsp; [&#x1F4D8;](https://colab.research.google.com/github/codingalzi/handson-ml/blob/master/notebooks/handson-ml-01.ipynb) |
| 머신러닝 프로젝트 처음부터 끝까지 | 1부 슬라이드 | [&#x1F4F1;](./slides/handson-ml-02a.slides.html) &nbsp; [&#x1F4BB;](./slides/handson-ml-02a-slides.pdf) |
|                           | 2부 슬라이드 | [&#x1F4F1;](./slides/handson-ml-02b.slides.html) &nbsp; [&#x1F4BB;](./slides/handson-ml-02b-slides.pdf) |
|                           | 3부 슬라이드 | [&#x1F4F1;](./slides/handson-ml-02c.slides.html) &nbsp; [&#x1F4BB;](./slides/handson-ml-02c-slides.pdf) |
|                  | 주피터 노트북 | [&#x1F578;](./notebooks/handson-ml-02.html) &nbsp; [&#x1F4D8;](https://colab.research.google.com/github/codingalzi/handson-ml/blob/master/notebooks/handson-ml-02.ipynb) |
| 분류 (준비중) | 슬라이드 | [&#x1F4F1;](./slides/handson-ml-03.slides.html) &nbsp; [&#x1F4BB;](./slides/handson-ml-03-slides.pdf) |
|                  | 주피터 노트북 | [&#x1F578;](./notebooks/handson-ml-03.html) &nbsp; [&#x1F4D8;](https://colab.research.google.com/github/codingalzi/handson-ml/blob/master/notebooks/handson-ml-03.ipynb) |

**링크 활용법**
* &#x1F4F1;: 좌우방향 터치 지원 슬라이드
* &#xF4BB;: pdf 슬라이드
* &#x1F578;: 읽기 전용 주피터 노트북 웹 페이지
* &#x1F4D8;: 구글 코랩(colab) 주피터 노트북

### QnA

* 챕터별 질의응답을 [QnA 파일](qna.md)에 모아놓았습니다.

### 주피터 노트북 학습법

#### 온라인(추천)

* [구글 코랩 ](https://colab.research.google.com/github/codingalzi/handson-ml/blob/master/)
<a href="https://colab.research.google.com/github/codingalzi/handson-ml/blob/master/"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> 활용

**주의사항:** 온라인 상에서 실습한 내용을 저장하려면 먼저 자신의 계정으로 사본을 만들어 저장한 후에 수정 및 실행해야 합니다.

#### 오프라인

먼저 자신의 컴퓨터에
[프로젝트 리포지토리](https://github.com/codingalzi/handson-ml)
[<img src="view-on-github.png" alt="View On GitHub" style="height:25px;"/>](https://github.com/codingalzi/handson-ml) 를 
복제합니다.

```bash
$ git clone https://github.com/codingalzi/handson-ml.git
$ cd handson-ml
```

아래 두 가지 방식 중에 하나를 선택하여 주피터 노트북과 소스코드를 실행할 수 있습니다.

* 윈도우 10 + 아나콘다(Anaconda) + Tensorflow 2(GPU 지원) 활용
    * 참고: [프로그래밍 환경설정 안내](./INSTALL.md)
* 도커(docker) 활용
    * 참고: [저자의 도커 이미지 활용](https://github.com/ageron/handson-ml2/tree/master/docker)

### 추가 자료

머신러닝/딥러닝 학습에 도움을 주는 자료를 소개합니다.

#### 추천 강의동영상
- [Stanford CS229: Machine Learning (Autumn 2018)](https://www.youtube.com/watch?v=jGwO_UgTS7I&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)
- [Deep Learning with PyTorch](https://atcold.github.io/pytorch-Deep-Learning/)

#### 딥러닝 학습 참고 동영상
- [SVM with polynomial kernel visualization](https://www.youtube.com/watch?v=OdlNM96sHio&t=0s)
- [수학자가 설명하는 심층 신경망](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
- 딥러닝 옵티마이저 선택 문제
   - [Tom Goldstein: "An empirical look at generalization in neural nets"](https://youtu.be/kcVWAKf7UAg?t=1304)
- 손실함수 그래픽
   - [Tom Goldstein: "What do neural loss surfaces look like?"](https://youtu.be/78vq6kgsTa8?t=237)

#### 강화학습 관련 동영상
- [알파고(이세돌) vs. 알파고 제로 비교 소개 동영상](https://www.youtube.com/watch?v=MgowR4pq3e8)
- [강화학습 학습과정 예제: Multi-Agent Hide and Seek](https://www.youtube.com/watch?v=kopoLzvh5jY)

#### 딥러닝 학습용 코드 모음집

- [Keras Code Examples](https://keras.io/examples/)
- [PapersWithCode datasets](https://www.paperswithcode.com/datasets)
- [Sebastian Raschka's datasets](https://sebastianraschka.com/blog/2021/ml-dl-datasets.html)
