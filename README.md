# A Medical Image Test Set Corresponding to Human Perceptual Similarity Judgment

## 제 28기 서울대학교 대학원 의과학과 학부 연구생 인턴 프로그램을 통해 수행한 task 입니다.

### Medical Image Classification
- ImageNet dataset으로 사전 훈련된 ResNet50을 통해 transfer learning을 수행했습니다.
- 논문([Efficient Pneumonia Detection in Chest Xray Images Using Deep Transfer Learning, 2020]())을 참고하여 augmentation을 수행했습니다.
- 훈련 시 사용한 파라미터는 아래의 표와 같습니다.
<img width="1319" alt="스크린샷 2022-02-18 오후 12 57 03" src="https://user-images.githubusercontent.com/63288666/154614759-11fdd618-57f0-4b18-8b1e-5f5a919b7cee.png">

***
<img width="855" alt="스크린샷 2022-02-18 오후 12 57 39" src="https://user-images.githubusercontent.com/63288666/154614816-2e503577-35aa-4ab6-9bef-049e3f9afafc.png">
