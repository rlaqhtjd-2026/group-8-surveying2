---
layout: report
advanced: true
title: "녹지–지표면 온도 관계의<br>환경조건 보정 및 계절별 이질성"
subtitle: "품질 기준 민감도와 공간 블록 예측 검증을 포함한 합성자료 기반 분석"
team: "예시 조 · 학술 보고서 작성 예시"
period: "관측 기간 없음 · 합성자료"
status: "합성 분석 실행 확인"
badge: "DEMO / 실제 관측 결과 아님"
---

> **교육용 합성자료에 기반한 학술 보고서 예시.** 본문은 실제 도시·Landsat 관측 결과를 제시하지 않는다. 기본 탐색용 36개 표본과 세부목적 분석용 384행은 서로 다른 합성자료이다. 연구 질문을 학술적 목적으로 구체화하는 과정을 보여주기 위해 일상적 질문과 정식 목적 진술을 함께 제시하였다.

### 초록 {#abstract}

작성 예정. 연구의 필요성과 관련 선행연구를 조사하고 출처를 기록합니다.

**주제어:** 작성 예정. 연구의 필요성과 관련 선행연구를 조사하고 출처를 기록합니다.

## 1. 연구 배경 {#background}

작성 예정. 연구의 필요성과 관련 선행연구를 조사하고 출처를 기록합니다.

## 2. 연구 질문 {#question}

작성 예정. 연구의 필요성과 관련 선행연구를 조사하고 출처를 기록합니다.

### 2.1 연구 질문 1

> **일상적 질문:** “녹지가 많은 곳이 더 시원한 건, 고도가 높거나 포장된 면적이 적어서 그런 것 아닐까?”

**학술적 연구 질문.** 작성 예정

### 2.2 연구 질문 2

> **일상적 질문:** 작성 예정

**학술적 연구 질문.** 작성 예정

### 2.3 연구 질문 3

> **일상적 질문:** 작성 예정

**학술적 연구 질문.** 작성 예정

## 3. 연구 목적 {#objectives}

### 3.1 전체 연구목적

**작성 예정** 



### 3.2 세부목적 1 · 작성 예정


### 3.3 세부목적 2 · 작성 예정



### 3.4 세부목적 3 · 작성 예정

**연구 질문 3의 목적화.** 

**필요성 및 평가 지표.** 

## 4. 재료 {#materials}

### 4.1 자료 구성 및 생성 조건 {#advanced-data}

작성 예정


## 5. 방법 {#method}

### 5.1 기초 탐색

작성 예정

### 5.2 세부목적 1의 분석: 작성 예정




### 5.3 세부목적 2의 분석: 작성 예정



### 5.4 세부목적 3의 분석: 작성 예정


### 5.5 불확실성 및 재현성


## 6. 결과 {#results}

### 6.1 기초 탐색: 작성 예정


### 6.2 세부목적 1 · 작성 예정


### 6.3 세부목적 2 · 작성 예정


### 6.4 세부목적 3 · 작성 예정



## 7. 토의 {#discussion}
작성 예정


## 8. 결론 {#conclusion}
작성 예정

### 부록 · 재현성 및 연구 기여 {#reproduce}

#### 직접 실행하기

[Colab에서 합성자료 노트북 열기](https://colab.research.google.com/github/{{ site.github.owner_name }}/{{ site.github.repository_name }}/blob/main/02_개인분석/01_demo_analysis.ipynb)

심화 분석도 EE 인증 없이 실행됩니다. 공통 자료 준비 블록을 먼저 실행하고 해당 분석 셀을 따라가세요.

- [세부목적 1: 환경조건 보정 — Colab](https://colab.research.google.com/github/{{ site.github.owner_name }}/{{ site.github.repository_name }}/blob/main/02_개인분석/02_confounding.ipynb)
- [세부목적 2: 계절별 관계 — Colab](https://colab.research.google.com/github/{{ site.github.owner_name }}/{{ site.github.repository_name }}/blob/main/02_개인분석/03_seasonality.ipynb)
- [세부목적 3: 강건성·공간 검증 — Colab](https://colab.research.google.com/github/{{ site.github.owner_name }}/{{ site.github.repository_name }}/blob/main/02_개인분석/04_robustness.ipynb)

GitHub 저장소의 코드를 로컬에서 실행하려면 다음을 사용합니다.

```text
python -m pip install -r requirements.txt
python 01_공통코드/make_demo.py
python 01_공통코드/advanced_analysis.py
```

예시 합성 분석은 2026-10-26 로컬 환경에서 실행 확인했습니다. GEE 시작 노트북의 실제 서버 실행은 검증하지 않았습니다.

[별도 연습: GEE 시작 노트북](https://colab.research.google.com/github/{{ site.github.owner_name }}/{{ site.github.repository_name }}/blob/main/01_공통코드/01_gee_starter.ipynb)

#### 조원별 기여를 쓰는 방법

실제 조에서는 “조원 A: 공통 전처리 및 품질 점검 / 조원 B: 공간 비교 / 조원 C: 시계열 분석”처럼 **분석 내용과 연결된 기여**를 기록하세요. 위 역할은 작성 예시이며 실제 참여자 명단이 아닙니다. 별도 주간 보고서는 만들지 않아도 됩니다.

#### 자료와 참고

- 합성자료: 이 저장소의 생성 코드, seed 2026(기본), 20261026(심화). 외부 관측 데이터 사용 없음.
- [Landsat 8 Collection 2 Level-2 공식 자료 설명](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C02_T1_L2)
- [학생 사용 안내]({{ site.github.repository_url }}/blob/main/STUDENT_GUIDE.md)
- [빈 보고서 틀](report-template.html)

- [섹션별 작성 지침]({{ site.github.repository_url }}/blob/main/05_보고서양식/섹션별_작성지침.md)


#### 연구 배경 참고문헌

- Voogt, J. A., & Oke, T. R. (2003). Thermal remote sensing of urban climates. *Remote Sensing of Environment, 86*(3), 370–384. [https://doi.org/10.1016/S0034-4257(03)00079-8](https://doi.org/10.1016/S0034-4257(03)00079-8).
- Schwaab, J., Meier, R., Mussetti, G., Seneviratne, S., Bürgi, C., & Davin, E. L. (2021). The role of urban trees in reducing land surface temperatures in European cities. *Nature Communications, 12*, 6763. [https://doi.org/10.1038/s41467-021-26768-w](https://doi.org/10.1038/s41467-021-26768-w).
