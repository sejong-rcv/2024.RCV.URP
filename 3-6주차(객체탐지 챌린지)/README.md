# 3-6주차

## KAIST Pedestrian Detection Dataset 🚶‍♀️🚶‍♂️

### 📢 이번주차 목표
1. KAIST Dataset으로 DataLoader 구현하여 원복하기 💻
2. KAIST PD dataset 을 보고 어떻게 개선해야할지 연구🔍


- 데이터셋 정보 [알아보기](https://soonminhwang.github.io/rgbt-ped-detection/data/)
- 리더보드 [바로가기](https://eval.ai/web/challenges/challenge-page/2343/overview)



## KAIST 데이터셋 평가코드 돌리기

### 📍 이번 주차 데이터셋 관련 자료 [바로가기](03-kaist_PD_dataset.pdf)   
> 바로가기를 누르면 나오는 해당 pdf 에 평가코드 돌리는 법도 나와있습니다    
> 데이터셋에 대한 이해가 당연히 필요 (CLASS, LABEL, ANNOTATION FORMAT 등)

### ❓ 평가코드는 어디에 ?
> 평가코드는 [여기서](official_Evaluation/) 확인 가능


### 📍 평가코드 돌리는 방법

```bash
git clone https://github.com/sejong-rcv/2024.RCV.URP.git
# 아래 .py 파일에 들어가서 경로 변경!
python Evaluation_official.py
```

평가코드는 `kaist_annotations_test20.json` 라는 GT json 파일과 여러분이 생성해낸 `prediction_example.json`을 비교하여 성능을 계산합니다.   
따라서 성능 확인을 위해서는 평가코드 포맷을 맞춘 `prediction_example.json` 파일을 생성해내야 합니다 (당연히 파일명은 자유로움)   

official_Evaluation/ 디렉토리 안에 있는 `prediction_example.json` 이 예제이므로, 해당 포맷에 맞춰 여러분 모델이 예측한 파일을 생성하시기 바랍니다!
