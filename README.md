### 모델 스코어 정리

|모델명|프레임워크|결과|설명
|------|---|---|---|
|VGG16|파이토치(전이학습)|val accurancy 0.9445|라벨 6개, 단일 분류
|resnet18|파이토치(전이학습)|val accurancy 0.9275|라벨 6개, 단일 분류
|resnet34|파이토치(전이학습)|val accurancy 0.9390|라벨 6개, 단일 분류
|resnet50|파이토치(전이학습)|val accurancy 0.9464|라벨 6개, 단일 분류
|mobilenet_v2|파이토치(전이학습)|val accurancy 0.9195|라벨 6개, 단일 분류
|mobilenet_v3_s|파이토치(전이학습)|val accurancy 0.8941|라벨 6개, 단일 분류
|mobilenet_v2|텐서플로(전이학습)|val accurancy 0.9179|라벨 6개, 단일 분류
|mobilenet_v3_s|텐서플로(전이학습)|val accurancy 0.8447|라벨 15개, 단일 분류
|mobilenet_v2|텐서플로(전이학습)|val accurancy 0.9070|라벨 15개, 단일 분류
|resnet50|파이토치(전이학습)|val accurancy 0.9225|라벨 15개, 단일 분류
|VGG16|파이토치(전이학습)|val accurancy |라벨 6개, 단일 분류
|resnet18|파이토치(전이학습)|val accurancy  |라벨 15개, 단일 분류
|resnet34|파이토치(전이학습)|val accurancy  |라벨 15개, 단일 분류
|VGG16|케라스(전이학습)|val_accuracy 0.5185|라벨 7개, 다중 분류 


다중분류는 정확도가 너무 낮아져서 높일 방법을 더 찾아봐야할듯..
