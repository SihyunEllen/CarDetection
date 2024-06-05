yolov8모델을 사용한 CarDetection 진행

1. 데이터 전처리
   -yaml 파일을 만드는 것이 핵심!
   -20%를 val set으로 지정
   -사진 경로, 박스가 처진 부분을 파일로 따로 저장
   - 따로 저장한 것들의 경로를 yaml파일에다 저장(yaml 파일로 만들어야 모델이 돌아감)

2.yolov8로 detection 학습 진행
  - epoch 20, batch 16,  lr=0.01
3.정밀도(map50): 0.9755213275235209 달성


   
