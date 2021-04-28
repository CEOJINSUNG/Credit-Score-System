# HeartBeat-Safety-System

### 참고
    1. 캐글 데이터 : https://www.kaggle.com/shayanfazeli/heartbeat

### 주제선정 및 이유
    1. 건설현장에서 인재로 인한 지속적인 사고가 발생
    2. 이는 건설 현장에서의 업무강도가 높음
    3. 건설사고에 대한 기준과 안전체계에 대한 논의가 발생한지 오래 되지 않음

### 스토리 잡기
    1. 기존 건설 근로자의 안전을 위한 체계적인 시스템은 준비되어 있음 ex) 안전모 AI(Object Detection), 화재 감지 등 존재
    2. 미래의 웨어러블 기기가 보편화되는 측면에서 아직 건설현장에서 개인의 웨어러블 기기를 통한 안전 장치가 없고 발전 가능성이 풍푸함
    3. 변수/핵심 포인트
       - 심장박동 기반 측정
       - 자금 부족으로 인한 도입의 가능성 부족, 
       - 노동 제도의 발전과 웨어러블 기기 발전, 
       - 건설 노동자의 근로 실태 및 사고 원인 규정 가능
    
### 과업 수행의 Outline 잡기
    1. 서론
       - 건설 환경에서의 안전사고 현황
       - 뇌심장질환의 노재 인정 현황
    
    2. 건설 사고발생의 이해
       - 산업재해의 원인(기사, 통계)
       - 산업재해 사고 유형(추락사고, 질식사고, 화재사고)
       - 현재의 사고 방지 제도
       - 기술적 안전장치 현황
    
    3. 심장박동과 업무
       - 왜 심장박동을 활용하는가?
       (논문, 기사)
       - 업무의 과중성이란
       - 과중부하의 평가 기준이 되는 노동자
       - 장, 단기적 피로 축적 기준

    4. 심장박동 데이터를 활용한 모델링
       - 전체적인 모델링 구조
       - 심장박동 데이터 수집 및 정제
       - 학습을 통한 정상과 비정상 수치의 구분 모델 수립
       - 장, 단기적 피로 측정을 위한 세부 파라미터 설정
       - 최종 모델 평가
    
    5. 결론
       - 기기활용을 통한 기대효과
       - 한계점 도출
