# R4DS

## 영상1
* CSV를 비롯한 파일을 R에 불러오려면 파일이 저장된 경로를 확인해서 불러온다
* 이번 영상에서는 dat <- read.csv("/Users/junghyun/chb_m.csv") 로 CSV파일을 불러옴

## 영상2(Select)
* Select 함수는 column을 선택하는데 사용
* Rename함수를 이용하여 column을 선택하는 동시에 이름을 바꾸기 가능
* Starts_with(), Ends_with(), contains() 등을 통해 조건 부여 가능

## 영상3(filter)
* Filter 함수는 Row를 선택하는데 사용
* is.na() 함수를 이용하여 NA 값 filter 가능

## 영상4(Mutate)
* 기존 data에 없던 새로우 변수 생성 가능
* ifelse()를 이용하여 Mutate()내에 조건 부여 가능
* Cut()을 이용하여 continuous variable을 변주형 변수로 바꿀 수 있음

## 영상5
* Arrange: 정렬 
* Summarize: aggregated function(개별 data를 뭉쳐서 특정한 data)
  ** 여러개의 요약 정보를 동시에 도출 가능
* Group by: subgroup analysis에 유용(그룹을 나눠서 내가 원하는 값 도출)
* na.rm=T(NA 값을 지우고 원하는 값 도출)
