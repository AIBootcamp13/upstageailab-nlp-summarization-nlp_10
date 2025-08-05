# unsloth qLora 
- 모델:
  - DeepSeek-R1-Distill-Qwen-14B-unsloth-bnb-4bit
  - unsloth/Meta-Llama-3.1-8B-bnb-4bit
- NOTE
  - 배치 사이즈를 잘 조절하지 않으면 VRAM 간당간당함
  - 그 이유로 훈련 도중 평가셋 지표 돌리면 OOM 발생
  - 월요일 하루 동안만 작업하였다 보니 데이터셋 EDA나 전처리 등의 작업은 진행하지 않은 상태로 학습
  - 화요일 새벽에 LORA 훈련을 8시간하고 (잘못된 프롬프트로) 이어서 정상 프롬프트로 Lora 샘플 300개라 새로 훈련하면 결과가 좀 다를 수 있음
