# AWSKRUG 2017 Re:Invent Recap

1. [준비작업 : S3 생성 - 5분](0-prerequisites.md)
2. [준비작업 : Sagemaker Notebook - 5분 ](0-prerequisites.md)
3. [Training : CIFAR 10 자료 준비 - 5분](1-dataset-preparation.ipynb)
4. [Training : Training - 25 분](2-training.ipynb)
5. [Training : 결과 확인 - 5 분](3-training-result.ipynb)
6. [Serving : Serving - 25 분](4-serving.ipynb)
7. [Serving : 결과 확인 - 5 분](5-perform-inferece.ipynb)
8. [Clean Up - 5 분](6-cleanup.ipynb)

> 소요시간 - 약 1시간 20분

## 목적

Amazon Sagemaker에서 제공하는 서비스 실습

1. Amazon Sagemaker Notbook
2. Amazon Sagemaker 제공하는 Built-In 알고리즘 중 Image Classification을 이용
   1. [Linear Learner](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/linear-learner.html)
   2. [Factorization Machines](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/fact-machines.html)
   3. [XGBoost Algorithm](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/xgboost.html)
   4. [Image Classification Algorithm](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/image-classification.html)
   5. [Amazon SageMaker Sequence2Sequence](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/seq-2-seq.html)
   6. [K-Means Algorithm](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/k-means.html)
   7. [Principal Component Analysis (PCA)](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/pca.html)
   8. [Latent Dirichlet Allocation (LDA)](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/lda.html)
   9. [Neural Topic Model (NTM)](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/ntm.html)
   10. [DeepAR Forecasting](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/deepar.html)
   11. [BlazingText](https://docs.aws.amazon.com/ko_kr/sagemaker/latest/dg/blazingtext.html)
3. Amazon Sagemaker Training 서비스를 이용하여 CIFAR 10 데이터를 Fine-tuning 한 모델 생성
4. Amazon Sagemaker Serving 서비스를 이용하여 Endpoint 생성

> 이 가이드는 AWS Tech Evangelist Julien Simon의 [Youtube - 동영상](https://www.youtube.com/watch?v=weYHuyyEtyU)을 기반으로 번역 및 수정 하여 작성하였습니다. 
>
> 원문 [Github Repo - ipynb](https://github.com/juliensimon/dlnotebooks/blob/master/sagemaker/01-Image-classification-transfer-learning-cifar10.ipynb) 
>
> [Julien Simon 블로그](https://medium.com/@julsimon)
