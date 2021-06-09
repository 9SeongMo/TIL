
# Normalization	
-----------------------------------------------

- 왜 정규화를 해야하는가
	- 데이터가 가진 feature의 스케일이 심하게 차이가나는경우 문제있지
	- 모든 데이터가 동일한 정도의 스케일로 반영되도록 해주는게 정규화
	- 중요도를 동일하게 가져간다고 생각!

- 종류
  - Min-Max Normalization (최소-최대 정규화)
    + 모든 feature에 대해 각각의 최소값이 0, 최대값이 1이 되게 변환
    + x라는 값에대해 
      + X = (x-min)/(max-min) 로 정규화 수식 사용가능
    + 하지만 이상치(outlier)에 영향 너무 심함 
      + ex) 엄청 큰 max값이나 min값 하나
      + Z-Score Normalization이 이상치 문제를 피하는 정규화 전략

  - Z-Score Normalization
    + Z = (x-평균)/표준편차
    + 표준편차 : 데이터들이 평균에서 얼마나 떨어져있느냐 지표
    + 즉 표준편차가 크면(데이터가 넓게 분포해 있으면) Z점수는 0에 가까워진다
      + 표준편차 = 분산의 양의 제곱근
      + 분산 = (변량 - 평균)^2/평균
	<br/>


	<br/><br/><br/>