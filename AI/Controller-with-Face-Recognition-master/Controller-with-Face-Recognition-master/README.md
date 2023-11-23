# Controller-with-Face-Recognition
Face-Recognition with ResNet + Door Lock Controller

 얼굴인식을 이용한 도어락 제어기
 
 

## 1. 개발 환경
**Controller**
1. Rasberry Pi 3+ model
2. python
 
**Camera**
 1. python (OpenCV + dlib + ResNet)
 
**Application**
 1. Android studio
 2. JAVA
 
 
## 2. 개발 기간
 프로젝트 기간 : 23.10 ~ 23.11
 프로젝트 인원 : 5명
 
 
## 4. 얼굴인식 과정

1. 얼굴 검출 : dlib.get_frontal_face_detector()
2. 특징 검출 : 68_face_landmarks
3. npy 파일에 학습된 사용자의 얼굴 정보 저장 (encoding)
4. 얼굴 인식 : resnet_model 


## 5. 작품 영상(결과물)
