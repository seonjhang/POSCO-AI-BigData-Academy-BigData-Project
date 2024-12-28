# POSCO-Academy-AI-BigData
## Overview
- Organization: POSCO AI Big Data Academy
- Industry: Health
- Project Title: 척추질환 환자의 특성을 반영한 차별화된 개인화 서비스 신규 개발로 수익성 향상
- Project Description: P병원의 환자에 대한 지속적인 Care활동과 더불어 재방문율을 높일 수 있는 방안 제시
- Date: Nov 10, 2021 - Nov 19, 2021

## Dataset
- patient_diagnosis_dat.csv: 환자 특성 정보 (row: 1,894 / column: 30)
- patient_surgery_data.csv: 환자 수술 및 치료 내용 (row: 1,894 / column: 15)
- medical_image_data.csv: 척추 이상 실적 정보 (row: 1,894 / column: 18)  
Patient ID  
ADH: Anterior Disc Height (mm)  
PDH: Posterior Disc Height (mm)  
FA: Fat Accumulation  
Instability: Instability  
MF + ES: MF + ES  
Modic change: Modic Change  
PI: PI (Pelvic Incidence)  
PT: PT (Pelvic Tilt)  
Seg Angle: Segment Angle (raw)  
Vaccum disc: Vacuum Disc  
Bone Density  
DCA: Disc Cross-sectional Area  
DP: Disc Position  
SMS: Spinal Movement Scale  
SAS: Spinal Anterior Spondylolisthesis  


## Timeline

date | day | note
----- | ----- | -----
Nov 10, 21 | Wed | 비즈니스 상황 분석, 추진 배경 작성
Nov 11, 21 | Thurs | 현황 및 개선 기회 작성
Nov 12, 21 | Fri | 도메인 지식 탐구, 변수 파악, 파생변수 생성
Nov 13, 21 | Sat | 도메인 지식 탐구, 탐색적 분석 및 인사이트 도출
Nov 14, 21 | Sun | 탐색적 분석 및 인사이트 도출
Nov 15, 21 | Mon | 탐색적 분석 후 분석 방향에 대한 고민, 데이터셋 통합 시도
Nov 16, 21 | Tue | 재발 여부 예측 모델(DT, RF, SVM, XGB), 의료진 수술 건수 예측 모델(시계열 분석)
Nov 17, 21 | Wed | 중점 care 대상 환자군 설정(군집 분석), 개선안 도출
Nov 18, 21 | Thurs | 최종 PPT 완성
Nov 19, 21 | Fri | 최종 발표

## Notebooks and Analysis


## Tech
The following technologies were used for this part of the project:
- Python 3
- Pandas: Python package for data analysis
- Matplotlib and Seaborn: Python 2D plotting library
