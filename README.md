# HBC-5_DeepLearning_Hackathon
2020 Hallym Hackathon

# 대회 설명

교내 건물 (공학관, 일송아트홀, 산학협력관, 대학본부 별관, CLC 총 5개의 class)의 데이터를 직접 수집하여, <br>

수집한 사진을 분류하는 딥러닝 모델을 개발.

# evaluation

전체 참가팀이 수집한 데이터로 최종 Test set을 구성하여 정확도 측정


# Data

<table>
  <tr>
    <td>Class</td>
    <td>Name</td>
    <td>Image</td>

  </tr>
  
  <tr>
  <td>0</td>
  <td>공학관</td>
  <td><img src = 'https://user-images.githubusercontent.com/77375223/118389887-2a26ba80-b667-11eb-9b09-01292f5b6961.png' width = 100></td>
  </tr>
  
  <tr>
  <td>1</td>
  <td>일송아트홀</td>
  <td><img src = 'https://user-images.githubusercontent.com/77375223/118390053-0ca62080-b668-11eb-9d31-934a384bb645.png' width = 100></td>
  </tr>
  
  <tr>
  <td>2</td>
  <td>산학 협력관</td>
  <td><img src = 'https://user-images.githubusercontent.com/77375223/118390106-5989f700-b668-11eb-89bf-dd866c0910ba.png' width = 100></td>
  </tr>
  
  <tr>
  <td>3</td>
  <td>대학본부 별관</td>
  <td><img src = 'https://user-images.githubusercontent.com/77375223/118390234-f6e52b00-b668-11eb-9818-a7d3b541eba8.png' width = 100></td>
  </tr>
  
  <tr>
  <td>4</td>
  <td>CLC</td>
  <td><img src = 'https://user-images.githubusercontent.com/77375223/118389775-7a514d00-b666-11eb-8c63-15a70f46ea24.png' width = 100></td>
  </tr>
</table>
  
Train set : 7688

Validation set : 1569

Test set : 1522

Total : 10779

# Train

### Model : resnet50

### epoch : 20

### loss : CrossEntropy

### optimizer : Adam

### Learning rate : 3e-3 (0.003)

validation의 성능이 가장 좋았던 weight를 저장하여 최종 weigt로 사용

<img src ='https://user-images.githubusercontent.com/77375223/118391020-2d24a980-b66d-11eb-823e-00794667d449.png' width = 500>

# Result

### our Test set accuracy : 99%

### competition Test set accuracy : 84%
