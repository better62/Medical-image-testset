# A Medical Image Test Set Corresponding to Human Perceptual Similarity Judgment

## 제 28기 서울대학교 대학원 의과학과 학부 연구생 인턴 프로그램을 통해 수행한 task 입니다.

### Medical Image Classification
- Chest X-ray dataset을 통해 폐렴 유무를 예측하는 모델을 구축했습니다.
- ImageNet dataset으로 사전 훈련된 ResNet50을 통해 transfer learning을 수행했습니다.
- 논문([Efficient Pneumonia Detection in Chest Xray Images Using Deep Transfer Learning, 2020](https://github.com/better62/Medical-image-testset/blob/Classification-ResNet50/augmentation/Efficient%20Pneumonia%20Detection%20in%20Chest%20Xray%20Images%20Using%20Deep%20Transfer%20Learning.pdf))을 참고하여 augmentation을 수행했습니다.
- Augmentation example (원본 이미지 & Horizontal shift 수행 후)
####
![NORMAL1000](https://user-images.githubusercontent.com/63288666/154616422-517426fc-abf7-4cc2-806a-cb65ecd01a9b.png) ![NORMAL1000-2](https://user-images.githubusercontent.com/63288666/154616581-de51c45b-50e6-475e-98c5-15593eb8aef5.png)

- 훈련 시 사용한 파라미터는 아래의 표와 같습니다.
<img width="1335" alt="스크린샷 2022-02-18 오후 1 05 18" src="https://user-images.githubusercontent.com/63288666/154615497-f7b06d72-3e04-419c-b264-d5c807da868a.png">

***
- Test accuracy가 92.16%로 나왔습니다.
- 훈련 과정에서 생성한 그래프는 아래와 같습니다.
<img width="1335" alt="스크린샷 2022-02-18 오후 12 52 22" src="https://user-images.githubusercontent.com/63288666/154615599-c010867e-7c5d-4be6-973b-c195963b0827.png">
