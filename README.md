# llama3-8B-finetune
한국어 파인튜닝

[<img src="https://raw.githubusercontent.com/unslothai/unsloth/main/images/unsloth%20made%20with%20love.png" width="200"/>](https://github.com/unslothai/unsloth)

### ko-alpaca-finetune-1
- base model: beomi/Llama-3-Open-Ko-8B
- dataset: Bingsu/ko_alpaca_data

### ko-dialogue-finetune-1
- base model: beomi/Llama-3-Open-Ko-8B
- dataset: https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=117
- [open-ko-llm-leaderboard](https://huggingface.co/spaces/upstage/open-ko-llm-leaderboard) submit을 위한 작업 포함

### evaluation
- BERTScore
- ROUGE-1, ROUGE-2, ROUGE-L with [korouge](https://github.com/HeegyuKim/korouge)
- openAI GPT-3.5-turbo test code
