## 소개
![프로필이미지](https://github.com/SonDooHwan/Resume/blob/master/images/SonDooHwan_200x200.jpg)
- 이름: 손두환
- 군필여부: 현 병역특례 지원중 (1급 현역)
- Email: dhson_@naver.com

```
높은 퍼포먼스 및 설명 가능한 머신러닝 개발을 지향하고 있습니다.
```


## 학력
- 고려대학교 바이오의공학과 졸업(2013 ~ 2017)
- 고려대학교 바이오융합공학과 졸업예정(2017~2020.8)

## 사용 기술
최신 머신러닝 기술, 통계 기법들을 구현하고 검증할 수 있을정도의 코딩 스킬을 가지고 있습니다.
- python
- MATLAB

## 연구 이력
### 연구내용
-멀티 모달리티 뇌 영상 Deep learning 기술 기반 예후예측 방법 개발<br/>
- A.	BRATS 2015데이터를 사용하여 Inception V3 네트워크로 High grade glioma, Low grade glioma를 구분하도록 학습<br/>
- B.	Classification 성능이 확보된 딥러닝 네트워크의 latent 특징을 각 환자마다 추출하고 각 환자의 특징을 average한 최종 특징벡터와 환자간 최종 특징의 구분을 Louvain method로 진행함을 제안하여 통계적으로 유의미한 survival양상 차이를 보임<br/>
- C.	latent특징의 Class Activation Map 가시화를 통해 종양 부위를 딥러닝 모델이 잘 판단함을 확인,  clustering 결과로 나뉜 환자마다의 CAM 이미지 상에 차이가 있는지 임상적인 관점으로 해석<br/>

-딥러닝을 활용한 뇌 병변 부위 자동 추출<br/>
- A.	뇌경색 부위 추출, 뇌종양 부위 추출, white matter hyperintensity 부위 추출을 U-net모델을 활용해서 진행<br/>
- B.	멀티 모달리티 이미지 정합 및 전처리들을 통해 입력 이미지들을 만들고 딥러닝 모델이 학습하게 hyper-parameter 조정, 새로운 test set으로 성능 확인<br/>

-딥러닝을 활용한 뇌 병변 부위 자동 추출및 이를 활용한 간단한 classification <br/>
- A.	원발성 뇌암, 뇌전이암의 뇌종양 부위를 U-net모델을 활용해서 진행<br/>
- B.	멀티 모달리티 이미지 정합 및 전처리들을 통해 입력 이미지들을 만들고 뇌종양 추출<br/>
- C.	추출한 뇌종양 label에서 feature vector 생성 후 이를 활용한 원발성뇌암/뇌전이암 classification 진행, 정확도 0.85 달성 <br/>

-NMOSD환자, MS환자의 fatigue score, subcortical shape mesh를 활용한 statistical analysis <br/>
- A.	Samsung Medical Center의 NMOSD, MS환자의 Fatigue score와 T1 brain MRI데이터를 사용하여 fatigue score와 significant한 correlation을 보이는 sub-cluster를 추출하고자 함<br/>
- B.	T1 이미지에서 brain parcellation을 진행하고, 3D mesh surface를 추출하고 surface를 registration한 후 vertext별 정보를 추출하기 위해 local-shape-volume을 계산함 <br/>
- C.	vertex별 local shape volume과 fatigue score와의 partial rank correlation분석을 진행하고, Cluster-based-statistics를 활용하여 통계적으로 유의미한 subcluster를 추출하여 가시화 함. <br/>

## 프로젝트 이력
### 바이오·의료기술개발사업
- 소개: 인공지능 기반 정밀진단기법 개발
- 기간: 2017.08 ~ 2020.05
- 역할: Glioma tumor 예후예측 기법 개발, 뇌종양 감별진단 machine learning 기술 개발, 개발 보고서 작성
- 관련기술: Python3, PyTorch

읽어주셔서 감사합니다. <br/>
부족한 부분이나 더 궁금하신 내용이 있다면 [이슈](https://github.com/SonDooHwan/Resume/issues)로 남겨주시겨나, dhson_@naver.com으로 연락주세요.<br/>
감사합니다.


## patent
- "딥 러닝 네트워크 기반 멀티 MR 이미지를 활용한 원발성뇌암 뇌전이암 구분 방법", 성준경, 손두환, KR Patent 10-2020-0065178 (2020)
- "딥 러닝 기반 멀티 MR 이미지의 이미지 특징을 활용한 환자 예후 예측 방법", 성준경, 손두환, 김정훈, KR Patent 10-2020-0065249 (2020)

