1일차
# 목표 🌟데이터 전처리 그리고 EDA🌟

- 빅쿼리에 대한 이해 
- 데이터 전처리, 파이썬 시각화 
- 워드클라우드
  - 워드클라우드 색상으로 나눠서 분석

## BigQury
- partition
  - 테이블 크기가 큰 경우(예시 : 유저 로그 데이터) 분석가가 query를 날릴 때 where절을 넣지 않으면 querya를 사용할 수 없음
  
- 샤딩
  - 특정 기준으로 테이블을 자르는 것
  
 
 
## 📍 분석결과 
분석가에게 필요한 언어는 **SQL**
- cohort 분석 
- 커뮤니케이션
- 서비스

➕추가  
- 통계 지식
- 태블로
- 구글 시각화
=> 다양한 시각화 툴을 사용한 경험이 있는지가 중요함 !

- 가설에 대한 문제 정의가 중요함

## 💡 배운점
### SQL
```
SPLIT(컬럼, 글자)[safe_offset(1)]
```

## 보충 
- wordcloud사용 시에 반복작업이면 함수를 사용해서 코드 작성해 보기
  - 컬럼만 변경해서 작업하기 때문

- 연차별로 나눠서 (저연차) 주요업무 분석, 우대사항, 자격요건을 시각화했을 때 전체 분석과 얼마나 차이가 나는지 분석
  - 저연차에게는 **지표설정**이 중요함
<img width="734" alt="image" src="https://user-images.githubusercontent.com/109959349/223116796-4459330c-9701-467c-bc01-8a5327572792.png">

- 필수요건
  - product 분석에 기본이 되는 것들이 중요함
  - 각 단계별로 어떤 지표가 있고 개념에 대해서 명확하게 설명이 가능해야 함
<img width="725" alt="image" src="https://user-images.githubusercontent.com/109959349/223116989-32e8a72b-5345-41a2-86ba-5ec747e7346d.png">

- ✍ homework
  - 분석한 흐름에 따라 EDA 리포트 만들어 보기 
  - EDA를 하면서 생각나는 가설을 리스트업 해보기 
