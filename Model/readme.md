

## DEC 모델(Deep Embedded Clustering Model)
심층 신경망을 사용해 feature representation과 clustering 할당을 동시에 학습</br></br>
데이터 공간에서 더 낮은 차원의 특징 공간으로의 매핑을 학습해 최적 군집화 수행</br></br>
## Pretrained 모델을 활용한 클러스터링
두가지 모델을 활용했고, 인테리어와 가장 유사한 Scene 이미지를 학습한 Places365 모델 활용 시 성능이 가장 좋았음</br></br>
Pretrained 모델를 통해 얻은 feature값에 대해 k-means 클러스터링</br>
1. ResNet50 (ResNet50.ipynb)

2. Places365 (Places365.ipynb)
* Places365 활용과 함께 k-means clustering 전 PCA차원 축소를 수행


</br>

## 참고 자료
* [Unsupervised Deep Embedding for Clustering Analysis](https://arxiv.org/pdf/1511.06335.pdf)</br>
* [Restnet50](https://franky07724-57962.medium.com/using-keras-pre-trained-models-for-feature-extraction-in-image-clustering-a142c6cdf5b1 
)</br>
* [Compare to various pretrained model trained Scene image
](https://github.com/AMANVerma28/Indoor-Outdoor-scene-classification
)</br>
* [place365-vgg](https://github.com/AMANVerma28/Indoor-Outdoor-scene-classification
)</br>
* [Resne50 architecture 
](https://stackoverflow.com/questions/54207410/how-to-split-resnet50-model-from-top-as-well-as-from-bottom
)</br>
* [VGG16_PLACES_365 arhitecture
](https://bskyvision.com/504
)
</br></br>

  
