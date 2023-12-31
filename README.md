### 분석 목적 : 입원기간에 영향을 미치는 요인들을 찾고자 함

<details>
<summary>변수 선택 이유</summary>

### DDA분석
| 변수명 | 변수 설명 | 변수 타입 | 분석가 의견 |
|------|-----------|------------| ---------- |
| 입원기간 | 환자의 입원기간 | 날짜형 | |
| 신장 | 환자의 키 | 연속형 | 연속적인 값을 가질 수 있고 소수점으로 표현될 수 있음 |
| 체중 | 환자의 몸무게 | 연속형 | 연속적인 값을 가질 수 있고 소수점으로 표현될 수 있음 |
| 고혈압여부 | 고혈압여부 | 범주형 | 고혈압 유/무 2가지로 나뉘는 데이터 |
| 당뇨여부 | 당뇨여부| 범주형 | 당뇨 유/무 2가지로 나뉘는 데이터 |
| 심혈관질환 | 심혈관질환 여부| 범주형 | 심혈관질환 유/무 2가지로 나뉘는 데이터 |
| 연령 |환자의 나이| 연속형 | 실수 범위 내에서 정해지지 않은 값을 가질 수 있음 |
| 성별 |환자의 성별 | 범주형 | 남/여 2가지로 나뉘는 데이터 |
| 재발여부 | 재발여부 | 범주형 | 재발 유/무 2가지로 나뉘는 데이터 |
| 수술시간 | 수술 소요시간 | 연속형 | 연속적인 값을 가질 수 있고 소수점으로 표현될 수 있음 |
| 스테로이드치료 | 스테로이드 치료 여부 | 범주형 | 스테로이드치료 유/무 2가지로 나뉘는 데이터 |
| 환자통증정도 | 환자가 느끼는 통증정도| 범주형 | 통증정도를 10단계로 나누어서 표현 |
| BMI | 환자의 비만도 | 연속형 | 연속적인 값을 가질 수 있고 소수점으로 표현될 수 있음 |

</details>

<details>
<summary>시각화</summary>

### EDA분석


</details>

<details>
<summary>변수의 상관관계를 객관적인 수치를 통해 검증</summary>

### CDA분석
| 목표변수 | 설명변수 | pvalue | 귀무가설/대립가설 |
| ------- | ------- | ------- | ------------- |
|입원기간| 고혈압여부 | pvalue=1.468698026856349e-142 | 대립가설 참|
|입원기간| 당뇨여부 |pvalue=1.0616331899646055e-74 | 대립가설 참 |
|입원기간| 심혈관질환 | pvalue=1.1692919294566776e-44 | 대립가설 참|
|입원기간| 연령 | pvalue=0.002 | 대립가설 참 |
|입원기간| 성별 ||  |
|입원기간| 재발여부 | |  |
|입원기간| 수술시간 | | |
|입원기간| 스테로이드치료 | | |
|입원기간| 환자통증정도 | | |
|입원기간| BMI | pvalue=0.39 | 귀무가설 참 |


</details>