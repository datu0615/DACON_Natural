# DACON_Natural
![20220524_130309](https://user-images.githubusercontent.com/84311270/169977205-f33c7354-e8da-4491-9d7d-01a0507ed5d4.png)
국가 연구개발과제를 '기후기술분류체계'에 맞추어 라벨링하는 알고리즘 개발

## Dataset
train.csv :		   
train 데이터   
기후기술분류 label 포함  
train.shape: (174304, 13)  

test.csv :   
test 데이터   
기후기술분류 label 미포함  
test.shape: (43576, 12)  

sample_submission.csv :   
sample_submission 데이터   
sample_submission.shape: (43576, 2)  

labels_mapping.csv :   
label과 기후기술분류체계를 mapping 한 meta data  

## Model
불용어 및 필요없는 단어 제거 전처리와 Kobert 모델을 사용하여 학습을 진행.

## Results
Public Score : 0.79361, Private Score : 0.76919로 최종 40등으로 마무리.
![20220524_130337](https://user-images.githubusercontent.com/84311270/169977652-095529d9-2b64-45c2-9f7c-fe0a37058695.png)
