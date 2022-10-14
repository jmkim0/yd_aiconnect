# 비매너 댓글 식별 (22.02.23 ~ 22.03.04) [[Notion]](https://salty-reward-0b7.notion.site/85585d4e42ab41e9b9ff8737b8662d8f)
뉴스 기사의 댓글 (comment) 중 편견, 혐오 표현 (bias, hate)이 포함된 댓글을 식별하는 과제
- Hugging Face Transformers 라이브러리와 BERT, ELECTRA 등 사전학습된 모델을 활용한 분류
- 한국어 뉴스 댓글로 사전학습된 KcELECTRA 모델 사용
- F1-macro 평가 지표 향상을 위해 bias, hate label을 각각  fine-tuning
- 총 16팀 중 2위 (F1-macro: 0.7502138408)
- 팀 제출 코드: [nlp_jmkim.ipynb](https://github.com/jmkim0/yd_aiconnect/blob/main/2-Team_Competition/3-comment_bias_hate/nlp_jmkim.ipynb)
## 폴더 설명
### exp_config
실험을 수행한 config 파일(.json) 저장 폴더
### result
모델 checkpoint 파일(.pt)과 예측한 결과 파일(.csv) 저장 폴더 (모델 checkpoint의 경우 용량 문제로 git으로 관리 안 함)

## 발표자료
[비매너_댓글_식별_발표자료.pdf - Google Drive](https://drive.google.com/file/d/1BPBOqudmrnJkeyNxUClRYD8bB9fIcktO/view?usp=sharing)
