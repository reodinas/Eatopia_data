# Eatopia_data
Eatopia 프로젝트에서 사용한 데이터들의 전처리 과정이 있는 레파지토리입니다.  
<br><br>


## File
* `인천광역시_일반음식점 현황_20221230.csv`: 크롤링 하기 위한 기반으로 사용한 음식점 데이터. 다운로드 링크: https://www.data.go.kr/data/15048906/fileData.do?recommendDataYn=Y

* `restaurant.ipynb`:  `인천광역시_일반음식점 현황_20221230.csv` 전처리와 크롤링 코드 테스트  

* `crawling.ipynb`: Selenium을 사용하여 네이버 지도에서 크롤링 하는 코드

* `preprocessing.ipynb`: 크롤링한 데이터를 필요에 맞게 전처리하는 코드

* `preprocessing2.ipynb`: 추가로 크롤링한 데이터를 전처리하고 이전 데이터와 병합하는 코드

* `preprocessing3.ipynb`: 프로젝트 진행 중 전처리가 미흡한 부분을 발견해서 추가 전처리 하는 코드

* `RESTAURANT_FINAL.csv`: 프로젝트에 사용한, 전처리 완료된 최종 식당 데이터

* `MENU_FINAL2.csv`: 프로젝트에 사용한, 전처리 완료된 최종 메뉴 데이터. 용량이 커서 링크로 대체 https://drive.google.com/file/d/1_FoHlUoA9WmOG8RPyvDrljZAqJNhBJU_/view

* `insertToDB.ipynb`: pymysql을 사용하여 최종 데이터를 데이터베이스에 저장하는 코드

* `data.7z`: 전처리 과정 중에 저장한 csv 파일 모음 압축파일

* `delivery_graph.ipynb`: 표로 작성된 통계치를 plotly를 사용하여 그래프로 시각화한 코드
