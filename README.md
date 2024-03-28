# Bumblebee
Open Source Project


한국산업인력공단 자격증 리스트
https://www.data.go.kr/iim/api/selectAPIAcountView.do
./Bumblebee/dataset/CBTsubjectlist_20230308.csv


요청변수(Request Parameter)


항목명(국문)	항목명(영문)	항목크기	항목구분	샘플데이터	항목설명
인증키	serviceKey	100	필	공공데이터포털에서 받은 인증키	발급받은 인증키
등급코드	grdCd	2	필	10	등급코드
기준년도	baseYY	4	필	2020	기준연도
페이지 번호	pageNo	5	옵	1	페이지 번호
페이지당 데이터 수	numOfRows	5	옵	1	페이지당 데이터 수
출력결과(Response Element)


항목명(국문)	항목명(영문)	항목크기	항목구분	샘플데이터	항목설명
합격자수	examPassCnt	10	필	2	합격자수
필/실기 구분	examTypCcd	30	필	필기	필/실기 구분
등급명	grdNm	100	필	기술사	등급명
시행회차	implSeq	200	필	108	시행회차
시행년도	implYy	30	필	2016	시행년도
종목명	jmFldNm	200	필	가스기술사	종목명
합격률	passRate	4	필	10.5%	합격률
응시자수	recptNoCnt	10	필	19	응시자수
페이지당 데이터 수	numOfRows	5	필	10	페이지당 데이터 수
페이지 번호	pageNo	5	필	1	페이지 번호
데이터 총 개수	totalCount	10	필	10000	페이지 총 개수
결과코드	resultCode	2	필	00	결과코드
결좌메세지	resultMsg	50	필	NORMAL SERVICE	결좌메세지
