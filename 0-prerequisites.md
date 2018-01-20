# 준비작업

## 1. S3 Bucket 생성

1. Servies > S3 선택
2. `Create bucket` 클릭 
3. 고유 버킷 이름 설정, Region은 `us-east-1`
  ![Bucket](https://github.com/awskrug/reinvent2017-recap-workshop/blob/master/img/Screen%20Shot%202018-01-20%20at%203.45.44%20AM.png)
4. `Next`를 클릭하여 버킷 생성

> 해당 버킷의 이름은 아래 형식으로 사용합니다.
>
> bucket="YOUR_BUCKETNAME" 

## 2. Amazon Sagemaker Notebook 생성

1. Services > Amazon SageMaker 선택
2. Dashboard 패널에서 `Create Notebook Instance` 클릭
3. __Notebook instance name__ 입력 후 `Create Notebook Instance` 클릭
  ![Sagemaker](https://github.com/awskrug/reinvent2017-recap-workshop/blob/master/img/Screen%20Shot%202018-01-20%20at%203.49.28%20AM.png)

## 3. Amazon Sagemaker Notebook에서 git pull

![Notebook](https://github.com/awskrug/reinvent2017-recap-workshop/blob/master/img/Screen%20Shot%202018-01-20%20at%2011.57.17%20AM.png)

![Notebook](https://github.com/awskrug/reinvent2017-recap-workshop/blob/master/img/Screen%20Shot%202018-01-20%20at%2011.57.49%20AM.png)

```bash
%%bash
git clone https://github.com/awskrug/reinvent2017-recap-workshop.git
```

