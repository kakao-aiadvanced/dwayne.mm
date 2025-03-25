# LLM 학습 환경

이 프로젝트는 LLM(Large Language Models)을 학습하고 실험하기 위한 주피터 노트북 환경입니다.

## 환경 설정

1. Python 가상환경 생성 및 활성화:
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
```

2. 필요한 패키지 설치:
```bash
pip install -r requirements.txt
```

3. 주피터 노트북 실행:
```bash
jupyter notebook
```

## 주요 패키지
- jupyter: 주피터 노트북 환경
- transformers: Hugging Face 트랜스포머 라이브러리
- torch: PyTorch 딥러닝 프레임워크
- python-dotenv: 환경변수 관리
