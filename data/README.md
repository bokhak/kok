## 국면분석 데이터 모음


#### train
  1. kospi_train.csv
  
    2001-01-02부터 2016-12-31까지
    
    kospi_train_1.csv
    - kospi_train의 수정 ver.1
      - 지수시가, 지수고가, 지수저가 삭제
      - diff(:기준일 지수종가 - 5일 후 지수종가) 추가
      - Y_TF(:diff>0에 대한 논리연산) 추가
    
    
  2. economic_train.csv
  
    2001-01-31부터 2016-12-31까지 (월단위)
    
    
  3. exchange_train.csv
  
    2001-01-02부터 2016-12-30까지
    
    
  4. market_train.csv
  
    2001-01-02부터 2016-12-29까지
    
    
  5. per_train.csv
  
    2001-01-02부터 2016-12-29까지
    
    
#### test 

  1. kospi_test.csv
  
    2017-01-02부터 2018-12-28까지
    
    
  2. economic_test.csv
  
    2017-01-31부터 2018-12-31까지
    
    
  3. exchange_test.csv
  
    2017-01-01부터 2018-12-31까지
    
    
  4. market_test.csv
  
    2017-01-02부터 2018-12-31까지
    
    
  5. per_test.csv
  
    2017-01-02부터 2018-12-28까지
    
    
    
## 데이터 탐색 및 전처리 ipynb


1. data_preview.ipynb

    - 데이터별 변수 종류 확인용
  
    - 데이터 구조 확인용
  
    - 데이터 기준 날짜 및 결측치 확인용


  
2. kospi_dsc.ipynb

    - kospi 데이터 탐색용
  
      - 변수별 분포 뜯어보기
