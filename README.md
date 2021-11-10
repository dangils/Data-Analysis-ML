> ipynb 파일 html 변환방법
>cmd  
>ipynb 파일 위치로 이동  
>jupyter nbconvert --to <html> <Untitled0.ipynb>  
>ex) jupyter nbconvert --to html Untitled0.ipynb

# Data-Analysis-ML
차량 스펙 데이터 분석 및 연비 예측

## Stacks 
Python , Google-Colab , pandas, scikit-learn

## 분석과정  

1) 데이터 준비  
 차량별 스펙 데이터 준비(data 파일) 엑셀의 텍스트 마법사로 csv 파일로 변환,
 필요한 데이터 선정후 데이터 전처리 수행   
 
 2) 데이터 분석  
  데이터셋 분리후 지도학습 수행 (사이킷런 활용)
  회귀 분석에 결과로 독립변수에 의한 회귀식 산출  
  
 3) 데이터 시각화  
   matplotlib , seaborn 라이브러리를 활용한 산점도 + 선형 회귀 그래프로 데이터 시각화  
   

 ## 예측 결과 산출  
   산출한 회귀식을 바탕으로 분석 모델에 독립변수 데이터를 기입하여 예측값 확인  
 
<hr>  
   
 
 # Covid19-Data-seoul(2021.01~10 month)
 
## 프로젝트 목표  
서울시 코로나19 확진자 현황 데이터를 분석하여 유의미한 정보 도출  
데이터 분석을 위한 데이터 정제, 특성 분석, 시각화  
 
## 분석 과정  
데이터 수집  
코로나 감염 데이터를 수집하여 DataFrame 구조 확인  

데이터 전처리  
유용한 데이터만 사용하기 위한 데이터 전처리  

데이터 시각화  
각 변수 별로 추가적인 정제를 하여 시각화를 통한 데이터의 특성 파악  
  
데이터 출처 :  
http://data.seoul.go.kr/dataList/OA-20279/S/1/datasetView.do
 
 
 
 
 
 
