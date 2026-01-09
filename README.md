# 🏭 SCM 안전 재고 최적화 시뮬레이터 (Safety Stock Simulator)

### 1. 프로젝트 개요
불확실한 시장 수요와 생산 리드타임(Lead Time)을 고려하여, **최적의 안전 재고(Safety Stock)와 재발주점(ROP)**을 자동으로 산출하는 대시보드입니다. 
엑셀로 반복하던 수동 계산 업무를 파이썬으로 자동화하고, 시각화하여 의사결정 효율을 높이기 위해 제작했습니다.

### 2. 주요 기능
* **수요 시뮬레이션:** 추세(Trend)와 계절성(Seasonality)을 반영한 가상 판매 데이터 생성
* **재고 리스크 분석:** 목표 서비스 레벨(95%, 99% 등)에 따른 필요 안전 재고량 자동 산출
* **시나리오 테스트:** 리드타임 변경 시 재고 비용이 어떻게 변하는지 실시간 시뮬레이션

### 3. 사용 기술 (Tech Stack)
* **Language:** Python 3.9
* **Library:** Streamlit (Web Dashboard), Pandas (Data Analysis), Numpy (Statistics)
* **Logic:** * Safety Stock Formula = $Z \times \sigma \times \sqrt{L}$
    * Reorder Point = $(Avg.Demand \times L) + Safety Stock$

### 4. 개발자
* **Name:** 김대유 (Kim Dae-yu)
* **Contact:** (이메일 주소나 블로그가 있다면 적으세요, 없으면 삭제)
