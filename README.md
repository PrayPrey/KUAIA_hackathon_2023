# KUAIA_hackathon_2023
2023.01에 진행한 고려대학교 산업경영공학부 주관 제 3회 KUAIA 해커톤 입니다.

## 프로젝트 내용
![image](https://github.com/PrayPrey/KUAIA_hackathon_2023/assets/73458088/425b11f8-ac64-4387-855f-d667d54835db)

## 데이터 분석
![image](https://github.com/PrayPrey/KUAIA_hackathon_2023/assets/73458088/acb1ec80-ba8e-4c5c-b952-3f340f824772)
![image](https://github.com/PrayPrey/KUAIA_hackathon_2023/assets/73458088/f31d2e41-96fc-4fc4-9207-0d20571a733a)

## 추천 알고리즘 내용 & 흐름도
### 이때, NLP 관련 코드는 다음 블로그 글을 참조했음을 밝힙니다. (https://teddylee777.github.io/huggingface/huggingface-text-classification)
![image](https://github.com/PrayPrey/KUAIA_hackathon_2023/assets/73458088/68e66ed4-f74c-4728-a316-7d7e4cde1f3f)
![image](https://github.com/PrayPrey/KUAIA_hackathon_2023/assets/73458088/8093e030-fec3-414b-ae8b-d0e4a139612d)


## 추천시스템 결과
![image](https://github.com/PrayPrey/KUAIA_hackathon_2023/assets/73458088/871513f4-12e7-42fd-afd6-045fe4471ed1)
![image](https://github.com/PrayPrey/KUAIA_hackathon_2023/assets/73458088/1e47aad7-bec6-406f-a2b9-d962c7b0c7ad)

## 코드 내용
- 데이터는 용량이 매우 많아 올리지 못하였습니다. 크롤링 코드를 참조하시길 바랍니다. (Crawling.ipynb)
- 이미지 처리 모델은 Mask-RCNN, NLP 모델은 BERT 모델을 활용하였습니다. 이미지 모델 같은 경우에는 사전 학습된 모델을 가지고 Fine-tunning 시켰으며, BERT 모델 또한 그렇습니다. (MRCNN_~~.ipynb, NLP_influencer.ipynb)
- 사전학습 모델은 'https://github.com/Viveckh/Fashion-Detection-Mask-RCNN-DeepFashion2/tree/master'에서  다운받아 사용하였습니다.

