## 2018 지방선거 결과 예측

###### Purpose
- Bayesia을 활용한 2018 지방선거 예측모델
- R 프로그램 및 MCMCpack의 함수(MCmultinomdirichlet) 사용

###### 2014 서울시장 선거(박원순 vs 정몽준)
- 분석자료: 중앙선거여론조사위원회 등록된 여론조사결과 수집
- Prior: 선거 유세 시작 전 정당지지도, Weight: 선거일 기준 '7/(선거일 – 현재일수)' 계산


<2014 Seoul Trend>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\1. 2014_seoul_trend.png">


<2014 Seoul Prior:no - weght:no>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\2. 2014_seoul_prior_no_info.png">

<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\\2014 Seoul\3. 2014_seoul_prior_no_info(2).png">

<2014 Seoul Prior:no - weght:yes>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\4. 2014_seoul_prior_no_info_weight_recent.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\5. 2014_seoul_prior_no_info_weight_recent(2).png">


<2014 Seoul Prior:yes - weght:no>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\6. 2014_seoul_prior_party_info.png">

<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\7. 2014_seoul_prior_party_info(2).png">

<2014 Seoul Prior:yes - weght:yes>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\8. 2014_seoul_prior_party_info_recent_weight.png">

<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Seoul\9. 2014_seoul_prior_party_info_weight_recent(2).png">


###### 2014 부산시장 선거(서병수 vs 오거돈)
- 분석자료: 중앙선거여론조사위원회 등록된 여론조사결과 수집,
- Prior: 선거 유세 시작 전 정당지지도, Weight: 선거일 기준 '7/(선거일 – 현재일수)' 계산

<2014 Pusan Trend>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Pusan\1. 2014_pusan_trend.png">

<2014 Pusan Prior:no - weght:yes>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Pusan\2. 2014_pusan_no_prior_info(2).png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2014 Pusan\3. 2014_pusan_prior_no_info.png">



###### 2018 경기도지사 지방선거(남경필 vs 이재명)
- 분석자료: 중앙선거여론조사위원회 등록된 여론조사결과 수집, 각 여론조사 내용은 중앙선거여론조사심의위원회 홈페이지 참조
- 기간: 2018.03.30~2018.06.02
- 여론조사 수: 총 18건
- R 프로그램 및 MCMCpack의 함수(MCmultinomdirichlet) 사용
- Prior: 2018년 4월 1주차 정당지지도(더불어민주당 49%, 자유한국당 13%, 바른미래당 8%, 정의당 6%, 민주평화당 0.3%, 기타0%, 모름 25%)
- Weight: 선거일 기준 '7/(선거일 – 현재일수)' 계산

<2018 Gyeonggi Trend>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\1. 2018_Gyeonggi_trend.png">


<2018 Gyeonggi Prior:no - weght:no>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\2. 2018_Gyeonggi_prior_no_info.png">

<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\3. 2018_Gyeonggi_prior_no_info(2).png">

<2018 Gyeonggi Prior:no - weght:yes>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\4. 2018_Gyeonggi_prior_no_info_weight_recent.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\5. 2018_Gyeonggi_prior_no_info_weight_recent(2).png">

<2018 Gyeonggi Prior:yes - weght:no>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\6. 2018_Gyeonggi_prior_party_info.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\7. 2018_Gyeonggi_prior_party_info(2).png">

<2018 Gyeonggi Prior:yes - weght:yes>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\8. 2018_Gyeonggi_prior_party_info_weight_recent.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\9. 2018_Gyeonggi_prior_party_info_weight_recent(2).png">

<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\10. 2018_Gyeonggi_histogram_comparison.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeonggi\11. 2018_Gyeonggi_histogram_comparsion(1).png">


###### 2018 경남지사 지방선거(김경수 vs 김태호)
- 분석자료: 중앙선거여론조사위원회 등록된 여론조사결과 수집, 각 여론조사 내용은 중앙선거여론조사심의위원회 홈페이지 참조
- 기간: 2018.04.13~2018.06.04
- 여론조사 수: 총 27건
- R 프로그램 및 MCMCpack의 함수(MCmultinomdirichlet) 사용
- Prior: 2018년 4월 1주차 정당지지도(더불어민주당 49%, 자유한국당 13%, 바른미래당 8%, 정의당 6%, 민주평화당 0.3%, 기타0%, 모름 25%)
- Weight: 선거일 기준 '7/(선거일 – 현재일수)' 계산


<2018 Gyeongnam Trend>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\1. 2018_kyungnam_trend.png">

<2018 Gyeongnam Prior:no - weght:no>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\2. 2018_kyungnam_prior_no_info.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\3. 2018_kyungnam_prior_no_info(2).png">

<2018 Gyeongnam Prior:no - weght:yes>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\4. 2018_kyungnam_prior_no_info_weight_recent.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\5. 2018_kyungnam_prior_no_info_weight_recent(2).png">

<2018 Gyeongnam Prior:yes - weght:no>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\6. 2018_kyungnam_prior_party_info.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\7. 2018_kyungnam_prior_party_info(2).png">

<2018 Gyeongnam Prior:yes - weght:yes>
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\8. 2018_kyungnam_prior_party_info_weight_recent.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\9. 2018_kyungnam_prior_party_info_weight_recent(2).png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\10. 2018_kyungnam_histogram_comparison.png">
<img src="C:\Users\injatist\Desktop\Foresight\foresighters.github.io\img\2018 Gyeongnam\11. 2018_kyungnam_histogram_comparison(1).png">
