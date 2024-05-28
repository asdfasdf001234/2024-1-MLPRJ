# 2024-1-MLPRJ

전처리
1. crop
2. white balance : gray-world

기본augmentation
1. 좌우반전
2. blur
3. 컷아웃
4. rotate

hyper paramter augmentation
1. 상하반전
2. PixMix

model
1. GoogleNet
   1-1. 기대 효과
   1-2. 실패 요인
     모델 구조 분석 결과 모델의 장점을 프로젝트에 사용할 수 없음
3. ResNet50
4. convfacenet
   3-1. 기대 효과
     얼굴 사진으로 pre-train된 모델을 사용하면 성능이 증가할 것이다
   3-2. 실패 요인
     전처리 모델을 사용할 수 없고, 공개된 구조만 사용할 수 있음
