### 모델 스코어 정리

|모델명|프레임워크|결과|설명
|------|---|---|---|
|VGG16|파이토치(전이학습 미세조정)|val accurancy 0.9445|라벨 6개, Multi-class 분류
|resnet18|파이토치(전이학습 미세조정)|val accurancy 0.9275|라벨 6개, Multi-class 분류
|resnet34|파이토치(전이학습 미세조정)|val accurancy 0.9390|라벨 6개, Multi-class 분류
|resnet50|파이토치(전이학습 미세조정)|val accurancy 0.9464|라벨 6개, Multi-class 분류
|mobilenet_v2|파이토치(전이학습 미세조정)|val accurancy 0.9195|라벨 6개, Multi-class 분류 
|mobilenet_v3_s|파이토치(전이학습 미세조정)|val accurancy 0.8941|라벨 6개, Multi-class 분류
|mobilenet_v2|텐서플로(전이학습 미세조정)|val accurancy 0.9179|라벨 6개, Multi-class 분류
|mobilenet_v3_s|텐서플로(전이학습 미세조정)|val accurancy 0.8447|라벨 15개, Multi-class 분류

Multi-label은 정확도가 너무 낮아서 높일 방법을 더 찾아봐야할듯..
