# 2024-1-MLPRJ

전처리
1. crop (done)
2. white balance : gray-world (done)

기본augmentation
1. 좌우반전
2. blur
3. 컷아웃
4. rotate

hyper paramter augmentation
1. 상하반전
2. PixMix

model
1. GoogleNet </br>
   1-1. 기대 효과 </br>
   1-2. 실패 요인 </br>
     모델 구조 분석 결과 모델의 장점을 프로젝트에 사용할 수 없음</br>
3. ResNet50
4. convnext</br>
   3-1. 기대 효과</br>
   3-2. 실패 요인 </br>
   과적합 문제가 발생하는 걸로 보임</br>
   3-3. convfacenet </br>
   얼굴 사진으로 pre-train된 모델을 사용하면 성능이 증가할 것이라 판단</br>
   전처리 모델을 사용할 수 없고, 공개된 구조만 사용할 수 있기에 convface는 사용이 어려움</br>



6. 진행상황</br>
ResNet50, ResNet101둘다 정확도 0.5미만 => 색이 아니라 얼굴 모양을 보고 학습하는 것 같음</br>

7. 시도할 수 있는 것</br>
   6-1. 형태를 알 수 없도록 blur</br>
   6-2. HSV 색공간으로 바꾸기</br>
   6-3. attention</br>
   6-4. 피부만 뜯기</br>

8. 시도한 것</br>
   7-1. Fine tuning 조정</br>
