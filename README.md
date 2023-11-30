# Final_project_fastcampus
  ### Feedback-question-generator__ with Medistream

#### 📌Outline of project

  - team : 'Life is Hanbang' (GS, SJ, SN)
  - with : Medistream
  - Goal : Making Feedback_question_generator, with given FAQ and management performance indicators.
  - time : 2023.05.02 ~ 2023.06.22

#### 🎆 1st Ideation

  - Understanding the given Data
    - Given datas are 'management performance indicators' and 'patients record' from members of Medistream.
    - Using SQL library from python, we will change needed datas into csv file and handle.
    - Specific explanation of data will be indicated in Korean.
      1. 경영지표데이터
         - 일/월 별 비급여 항목, 전체 매출 유입 경로 및 공단청구금등에 관한 데이터이다.
	     - 각 병원별 고유 아이디로 분류되어있으며, 월 단위로 증감률에 관한 데이터 테이블이 존재한다.

      2. 환자진료데이터
	     - 각 환자들의 진료별 진단 명, 처방 명등의 의료진료데이터이다.
      	  - 마찬가지로 고유 아이디로 분류되어있으며, 환자에 대한 개인정보는 제공되지 않았다.

      3. 월간 지표분석데이터
        	- 메디스트림의 멤버스에 등록된 한의원별로 만들어진 마크다운 형식의 파일이다.
        	- 월별로 증감률과 최대, 최소치의 항목등 여러 데이터들을 종합하여 만든 분석테이블이다.
        	- '월간 지표분석 질문'이 존재하며 이 질문 데이터가 우리의 target value이다.


  -  EDA Plan
      - 
