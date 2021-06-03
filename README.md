# AwesomeKorean_Speech

음성과 신호처리(정리중)     
-  모두의연구소 ASR 랩에 참여하면서 논의된 내용을 바탕으로 정리하였습니다.   


# 신호처리

- 관련 책 
	* [음향 및 청취 음성학의 이해(절판)](http://used.kyobobook.co.kr/product/viewBookDetail.ink?cmdtBrcd=7281961375243&orderClick=LIP&Kc=SEBLBkusedsearch)

	* [Think DSP](https://github.com/AllenDowney/ThinkDSP)

- 위의 두 책 관련 스터디 자료 [링크](https://drive.google.com/drive/folders/10rIXVgjbe6Y4OvVBp4jNSVYsxPwo61P1?usp=sharing)

- 관련 강의 
	* [토크 ON 세미나 디지털 신호 처리 이해](https://www.youtube.com/watch?v=RxbkEjV7c0o&list=PL9mhQYIlKEhem5_wrQqDtNqNcaDyFrYGN)
	  


# 음성 인식 automatic speech recognition (ASR)
-관련 책       

	- [ratsgo's speech book](https://ratsgo.github.io/speechbook/docs/neuralam/deepspeech)

- 관련 강의

	- Connectionist Temporal Classification(CTC) 모델 관련 강의: [토크ON세미나 딥러닝 기반 음성인식 기초 4강](https://www.youtube.com/watch?v=xQ0kkGb5gLk)     
	- wave2vec 논문 관련 강의 : [wav2vec: Self-Supervised Learning of Discrete Speech Representations[(https://www.youtube.com/watch?v=mPtyfqWHs3s).  


- 관련 논문      

	*Wiliam Chan et al. [Listen, Attend and Spell](https://arxiv.org/abs/1508.01211) arXiv: 1508.01211*      

	*Dario Amodei et al. [Deep Speech2: End-to-End Speech Recognition in English and Mandarin](https://arxiv.org/abs/1512.02595) arXiv: 1512.02595*

	*Jung-Woo Ha et al. [ClovaCall: Korean Goal-Oriented Dialog Speech Corpus for Automatic Speech Recognition of Contact (Centers](https://github.com/clovaai/ClovaCall), arXiv: 2004.09367*   

	

	*Soohwan Kim, Seyoung Bae, Cheolhwang Won, [Open-source toolkit for end-to-end Korean speech recognition](https://www.sciencedirect.com/science/article/pii/S2665963821000026),SIMPAC*

	*Park, Kyubyong and Mulc, Thomas, [CSS10: A Collection of Single Speaker Speech Datasets for 10 Languages](https://github.com/Kyubyong/css10), arXiv:1903.11269*

	*[논문 정리한 깃헙 : awesome-speech-recognition-speech-synthesis-papers](https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers)*

- 관련 블로그
	*[딥 러닝 음성 인식에 필요한 훈련 데이터를 직접 만들어보자](https://engineering.linecorp.com/ko/blog/voice-waveform-arbitrary-signal-to-noise-ratio-python/)
	* [Librosa python library로 음성파일 분석하기](https://banana-media-lab.tistory.com/entry/Librosa-python-library%EB%A1%9C-%EC%9D%8C%EC%84%B1%ED%8C%8C%EC%9D%BC-%EB%B6%84%EC%84%9D%ED%95%98%EA%B8%B0)


# 데이터    
## 영어    

	- LJSpeech
	- [LibriSpeech](https://www.openslr.org/11/) : https://paperswithcode.com/sota/speech-recognition-on-librispeech-test-clean
	- Libri-Light: 60k hour unlabelled speech + (10h, 1h or 10min) labelled speech (same as LibriVox???) https://github.com/facebookresearch/libri-light
	- [open source voice and music datasets 정리된 자료](https://github.com/jim-schwoebel/voice_datasets)
	


## 한국어    

	- [KsponSpeech ](https://aihub.or.kr/aidata/105/download
	- 모두의말뭉치[일상대화_음성_말뭉치](https://corpus.korean.go.kr/)
	- [한국어 1인 음성 데이터 ]( https://www.kaggle.com/bryanpark/korean-single-speaker-speech-dataset)
	- [로봇의 감정 및 개성을 표현할 수 있는 대화형 음성합성 오픈소스](https://github.com/songys/emotiontts_open_db)

- 신청 접수 후 다운로드 가능
- 철자 전사, 전사 기호(웃음 {laughing}등), 비식별화 기호(이름 &name& 등) 사용

## 툴킷  

	- [Librosa](https://librosa.org/doc/latest/index.html): python 패키지
	- Touch Audio : 모델링
	- [Kaldi](https://kaldi-asr.org/) : C++로 작성
	- [Praat](https://www.fon.hum.uva.nl/praat/)  




## 한국어 구현 
KoSpeech : https://github.com/sooftware/KoSpeech                    

speech-recognition : https://github.com/cosmoquester/speech-recognition

# DECODE
[CTC decode](https://github.com/parlance/ctcdecode)

# 한국어 음성합성  
참고 링크 : https://pororo-tts.github.io/        








