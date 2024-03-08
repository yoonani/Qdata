# Qdata

## Data 목록

|Folder|Filename|Title|Description|
|------|--------|-----|-----------|
|./|sgg_code_2023.csv|ㅣ시군구별 코드와 행정기관코드|2023년 기준으로 시도와 시군구의 코드와 행정기관 코드|
|Social/balanced|grdp_birth_2020.csv|GRDP와 신생아출생수|2020년 시군구 단위 GRDP와 신생아 출생수데이터|
|Social/balanced/nabis|by_year/index_*.csv|년도별 균형발전지표|2019년부터 2022년까지의 시군구 단위 핵심지표와 객관지표 통계 데이터|
|Social/popFlow|day_residual_index_sgg_2020.csv|2020년 주간인구지수(시군구)|2020년 주간인구지수로 주간인구지수는 "100 * 주간인구 / 상주(야간)인구"의 시군구별로 제공 |


### sgg_code_2023.csv

* 주민등록인구로부터 기초지자체의 코드를 구하고, 행정표준코드를 join 한 파일
* 강원특별자치도, 전북특별자치도의 경우 sido_nm_2에 반영