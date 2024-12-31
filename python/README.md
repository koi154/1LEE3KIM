# 퇴사율 분석 결과

## 개요

본 프로젝트는 2014~2022년 동안 KOSIS에서 수집한 데이터를 기반으로 국내 직원들의 퇴사율에 영향을 미치는 다양한 요인을 분석했습니다.

연도별, 시도별 퇴사율 비교뿐만 아니라 연령대별 퇴사율과 육아, 근무 환경 등 개인적, 사회적 요인과의 상관관계를 분석하여 퇴사율에 대해 분석했습니다.

## 데이터

* **출처:**
	KOSIS
	지역별 퇴사인력(2014~2022)
	https://kosis.kr/statHtml/statHtml.do?orgId=380&tblId=DT_380002_A078_7TH&vw_cd=MT_ZTITLE&list_id=380_38002_021	&seqNo=&lang_mode=ko&language=kor&obj_var_id=&itm_id=&conn_path=MT_ZTITLE

	근로환경만족도
	https://kosis.kr/statHtml/statHtml.do?orgId=380&tblId=DT_380002_A078_7TH&vw_cd=MT_ZTITLE&list_id=380_38002_021	&seqNo=&lang_mode=ko&language=kor&obj_var_id=&itm_id=&conn_path=MT_ZTITLE

	직업 이외의 활동 참여 빈도(2017)
	https://kosis.kr/statHtml/statHtml.do?orgId=380&tblId=DT_380002_A078_7TH&vw_cd=MT_ZTITLE&list_id=380_38002_021	&seqNo=&lang_mode=ko&language=kor&obj_var_id=&itm_id=&conn_path=MT_ZTITLE

* **기간:** 2014~2022

* **구성:** 연도, 시도, 연령, 퇴사 여부, 육아 여부, 요리 및 집안일 참여 시간, 운동 시간, 근무환경 만족도, 자기계발 시간 등



## 분석 방법

* **상관분석:** 퇴사율과 다양한 변수 간의 상관관계를 분석하여 어떤 요인이 퇴사율에 영향을 미치는지 파악



## 주요 결과

* **[그래프 1]: 연도별 퇴사율 추이**

    * 퇴사자 수가 비약적으로 증가하지는 않으나, 일정한 수를 유지함

* **[그래프 2]: 시도별 퇴사율 비교**

    * 시도별 퇴사율을 비교해, 신입의 퇴사 이유에 접근할 수 있는 방법을 마련

* **[그래프 3]: 연령대별 퇴사율 전처리**

    * 퇴사율과의 비교를 위한 전처리 과정

* **[히트맵 1]: 퇴사율과 각 변수 간 상관계수**

    * 퇴사율에 영향을 미치는 요인들을 간단하게 분석


## 결론 및 시사점

본 연구에서는 KOSIS 데이터를 기반으로 2014년부터 2022년까지 국내 직원들의 퇴사율에 영향을 미치는 요인을 분석했습니다.
분석 결과, 근무 환경 불만족, 육아, 자기계발 등이 퇴사율과 유의미한 상관관계를 보였습니다.
특히, 2020년 코로나19 팬데믹 이후 육아 부담 증가하지만 퇴사율과의 관계가 음의 상관관계를 맺는 것으로 보였으며, 운동 부족이 근무 환경 불만족과 밀접하게 연관되어 있음을 확인했습니다.


## 코드

* 사용 언어: Python

* 사용 라이브러리: Pandas, NumPy, Matplotlib, Seaborn, folium


## 한계점 및 향후 연구

* 분석을 하고자 하는 데이터의 양이 적어, 이상치를 제거하지 않으면 유의미한 결과를 얻을 수 없었습니다. 추후에 다시 진행하게 된다면, 조금 더 많은 데이터를 수집해야할 것으로 보임.

**# 퇴사율 # 분석 # 데이터 분석 # 인사관리**