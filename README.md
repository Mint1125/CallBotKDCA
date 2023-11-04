- 요약서
    - 과제명 질병관리청에서 활용되는 ars를 대체하는 시스템 개발
    - 총수행기간 12/21 (1차)
    - 과제목표
        1. fine-tuning 을 위한 데이터셋 구축
        2. pre-train 된 모델을 활용한 ars 데이터셋 fine-tuning
        3. stt, tts를 활용한 시스템 통합 구축
    - 개발내용
        1. fine-tuning 을 위한 데이터셋 구축
            1. aihub에서 원천 데이터 추출 및 가공
            2. hugging face dataset 포맷에 맞는 데이터 변환
        2. data set을 활용한 pre-train 된 모델 fine-tuning
            1. 한국어 pre-train 이 된 모델을 활용한 fine-tuning
            2. polyglot, kogpt, kullm 등 여러 모델을 활용한 정확도 비교
        3. stt, tts를 활용한 시스템 통합 구축
            1. whisper (openai) 를 활용한 stt 모델을 통한 정확도 높은 시스템 구축
    - 과제수행방법
        1. fine-tuning 을 위한 데이터셋 구축
            1. aihub에서 원천 데이터 추출 및 가공
                
                [원천 데이터 출처](https://www.notion.so/dfd4bf7fdfeb4ea485351761bfa010a3?pvs=21)
                
                질병관리청에 해당되는 데이터를 추출 및 가공
                
            2. hugging face dataset 포맷에 맞는 데이터 변환
                
                [원천 데이터 포맷](https://www.notion.so/b4a04dc4bf194fbd95b0ad4fe70796d2?pvs=21)
                
                chating 모델에 알맞는 데이터셋 포맷으로 변환
                
            3. hugging face dataset에 업로드
        2. data set을 활용한 pre train 된 모델 fine- tuning
            1. 한국어 pre-train 이 된 모델을 활용한 fine-tuning
                
                [모델 평가 지표](https://www.notion.so/012bfbf70d084256996069da2aa8e231?pvs=21)
                
                [fine-tuning 순서도](https://www.notion.so/fine-tuning-165bc2e8434f45538a0106d4128a6799?pvs=21)
                
            2. polyglot, kogpt, kullm 등 여러 모델을 활용한 정확도 비교
            3. gradio 를 이용한 web gui 구현
                
                [gradio 사용 예시](https://www.notion.so/gradio-400bc130d1e94beebdc153b41087a144?pvs=21)
                
        3. stt, tts를 활용한 시스템 통합 구축
            1. whisper (openai)등 automatic speeech recognition 을 활용한 시스템 구축
    - 결과활용계획
        1. 상용화 모델
            1. 질병관리청에서 활용하는 1339 콜센터 대체 시스템
        2. 수요처
            1. 질병관리청
            2. 기타 정부 기관
            3. ars를 활용하는 민간 업체
    - 최종결과물
        1. 질병관리청 ars 데이터셋
        2. 질병관리청 데이터 기반 fine-tuning된 llm 모델 web gui
        3. stt, tts를 활용한 ars 대체 시스템
    - 경제적파급효과
        1. 정부 기관과 같은 ars 활용이 빈번한 기관에서의 업무 대체
        2. 민간 기관 또한 예시를 통한 자체 ars 대체 사업화 모델 제시
