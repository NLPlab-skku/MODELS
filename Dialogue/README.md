# 한국어 대화 데이터셋 학습 모델

NLPLAB에서 구축한 NLPLAB Dialogue 데이터셋을 학습한 [KoBART](https://github.com/SKT-AI/KoBART)기반의 대화 상태 추적 모델 및 대화 응답 생성 모델입니다.

## 구축내용
|제목|내용|위치|
|------|---|---|
|**Music**|음악 도메인 대화 데이터셋|./Music_Knowledge_Graph_Grounded_Dataset|
|**Music Commonsense**|음악 도메인 대화에 일상 대화가 포함된 데이터셋|./Music_Commonsense_Knowledge_Graph_Grounded_Dataset|
|**Manual**|매뉴얼 기반 대화 데이터셋|./Manual_Grounded_Dialogue_Dataset|
  
## Models
|제목|내용|위치|
|------|---|---|
|**Dialogue State Tracking Model**|대화 상태 추적 모델(koBART), 대화 히스토리를 바탕으로 현 발화의 대화 상태 추적|./dstm|
|**Response Generation Model**|대화 응답 생성 모델(koBART), 대화 상태 추적 결과를 바탕으로 서브그래프 추출, 대화 히스토리와 입력하여 대화 응답 생성 |./rgm|