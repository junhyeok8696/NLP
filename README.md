# NLP

### [IMDB 영화 리뷰 감성 분석](https://github.com/junhyeok8696/NLP/blob/main/IMDB_movie_reviews_sentiment_analysis.ipynb)
- IMDB 영화 리뷰 데이터셋을 이용한 감성 분석

### [네이버 영화 리뷰 감성 분석](https://github.com/junhyeok8696/NLP/blob/main/Naver_movie_reivew_classification.ipynb)
- 네이버 영화 리뷰 데이터셋을 이용한 감성 분석
- 한글 형태소 Okt 사용 전처리
- Keras Tokenizer, pad_sequences 함수 사용

### [개체명 인식 모델](https://github.com/junhyeok8696/NLP/blob/main/NER_recognition_Bi_LSTM.ipynb)
- CoNLL2003 dataset 이용
- BI - LSTM 모델로 구성

### [Encoder-Decoder Model](https://github.com/junhyeok8696/NLP/blob/main/language_translation_KerasAPI_teacherForcing.ipynb)
- Encoder-Decoder 기계 번역 모델
- 학습 데이터 부족으로 인한 overfitting 현상이 일어나 모델의 성능은 떨어짐

### [Simple chatbot](https://github.com/junhyeok8696/NLP/blob/main/ChatBot_encoder_decoder_sentencepiece.ipynb)
- Chatbot_data_for_Korean v1.0 dataset (https://github.com/songys/Chatbot_data) 을 이용한 Chatbot model 개발
- 학습 데이터 부족으로 인한 overfitting 현상이 일어나 모델의 성능은 떨어짐
- Stochastic Sampling 기법 사용

### [Transformer](https://github.com/junhyeok8696/NLP/blob/main/Transformer.ipynb)
<img src=https://www.tensorflow.org/images/tutorials/transformer/transformer.png width=500>
- Portugese-English translation dataset을 이용한 Transformer 번역기 모델

### [BERT Fine Tuning](https://github.com/junhyeok8696/NLP/blob/main/classify_text_with_bert_tfhub_Kor.ipynb)
- 네이버 영화 리뷰 Dataset을 이용한 BERT Fine Tuning
- 리뷰 Text로 긍정 / 부정 분류
- Tensorflow Hub에서 필요한 모델을 load해 Modeling

### [Huggingface Sentiment_Analysis_model](https://github.com/junhyeok8696/NLP/blob/main/Huggingface_Sentiment_Analysis_navermovie.ipynb)
- NAVER Movie review dataset을 이용하여 transformers BERT model을 fine tuning
- Pytorch 와 Trainer를 이용한 Fine Tuning (Pytorch version이 Tensorflow 보다 안정적)

### [Huggingface pipeline](https://github.com/junhyeok8696/NLP/blob/main/HuggingFace_QuickStart_pipeline_tokenizer.ipynb)
- Huggingface pipeline을 이용해 원하는 목적에 맞게 한줄의 코드로 모델을 불러와 사용 가능
