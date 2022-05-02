# fsrcnn_game

FSRCNN을 이용한 게임 화면 업스케일링 및 품질 개선

## 구성 내용
jupyter_notebook 로 작성함  

+ 영상 프레임 추출 + 이미지 리사이즈
+ SRCNN
+ FSRCNN

+ 화면 모니터링2
+ 선명하게



## 사용방법
**srcnn 모델**
1. 영상 프레임 추출 + 이미지 리사이즈.ipynb : 영상 -> 이미지화 하여 hr, lr 이미지를 각각 다른 폴더에 저장
2. srcnn2.ipynb : 전체 구현 코드 + 모델 저장 + 테스트 + 수치 비교  


**fsrcnn 모델**
1. 영상 프레임 추출 + 이미지 리사이즈.ipynb : 영상 -> 이미지화 하여 hr, lr 이미지를 각각 다른 폴더에 저장
2. fsrcnn2.ipynb : 전체 구현 코드 + 모델 저장 + 테스트 + 수치 비교  


**실시간 출력**
1. 화면 모니터링2.ipynb : 화면에 특정 영역을 읽고 학습된 모델을 거쳐 업스케일링된 화면 출력
2. " : 그중에서 윈도우 환경 + 모델2 이용 을 사용함(mss)  


**CLAHE을 이용한 이미지 선명화**
2가지 방법으로 사용가능
1. 화면 모니터링2.ipynb : 아래에 윈도우 환경 + 모델2 이용 + CLAHE 적용 을 사용하기
2. 선명하게.ipynb : 다양한 선명화 기법들 소개, 그래프+히스토그램 비교등 자세하게 확인가능, CLAHE 이미지 적용도 존재  


## 주의사항
**실시간 출력**
맥에서는 작동이 안되고 윈도우 환경에서만 가능  

## 문제점들
