## 티처블 머신을 활용한 이미지 분류 프로젝트
- **주제**  : 티처블 머신으로 만든 분류 모델과 카메라를 이용해 카미봇이 블록 지도에서 특정 나라(위치)로 이동
- **유형**  : Classification
- **개발**  : Kamibot, Jupyter Notebook, Python, Keras, Opencv

## 알고리즘
- **Data** : 신용카드 사용자들의 개인 신상정보
- **Shape** : (26457, 17)
- **출처**: https://mp.weixin.qq.com/s/upjzuPg5AMIDsGxlpqnoCg

## 사용 자료
- **Train** : 2 LGBMClassifier, 1 XGBClassifier
- **Stacking** : LGBMClassifier

## 평가
- **Metric** : Logloss
- **Public Score** : 0.69909
- **Private Score** : 0.67894 (7th)
