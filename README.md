# Tensorflow를 파이썬이 아닌 자바스크립트에서 지원하여 웹에서도 동작하게 한다면?

http://teachablemachine.withgoogle.com/을 통해 학습한 데이터 모델을 통해 밤/낮 여부에 따라 다른 화면 색상을 보여 주는 앱을 만들었습니다

자세한 소스 코드는 index.html을 참고

깃허브 페이지를 통해 실행하려면 https://younhong.github.io/Tensorflow-Python-JS/ 로 이동해서 실행

로컬 환경에서 실행하고 싶다면
```
ws --https --port 9999 --open
```

그 외의 학습 자료

1. src 폴더

* 동일한 데이터를 각각 파이썬과 자바스크립트를 통해 학습

> python 폴더

>> 파이썬으로 tensorflow를 사용하는 방법

> javascript 폴더

>> 자바스크립트로 tensorflow를 사용하는 방법

2. model 폴더

* 데이터를 학습을 마친 모델을 저장한 폴더

3. data 폴더

* 학습에 필요한 데이터(csv 자료형)을 저장한 폴더
