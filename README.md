# 스타듀밸리 촌장님 챗봇

스타듀밸리 테마의 AI 챗봇으로, Azure OpenAI와 Gradio를 활용하여 게임 정보를 제공합니다.

## 스크린샷
![스크린샷 1](https://github.com/user-attachments/assets/7df3343c-0559-4a89-84e4-3ad0a57ec8da)
![스크린샷 2](https://github.com/user-attachments/assets/6b83f1ed-2a52-4d0c-8060-c31b8e041e6d)

## 주요 기능
- 스타듀밸리 게임 관련 질문에 대한 답변
- 대화 내용에 맞는 게임 캐릭터 이미지 자동 표시
- 정보 소스 인용 및 참조

## 기술 스택
- Azure OpenAI Services - 자연어 처리 및 대화 생성
- Azure AI Search - 게임 정보 데이터베이스 검색
- Gradio - 사용자 친화적 웹 인터페이스
- Python - 백엔드 개발 언어

## 설치 및 실행 방법
1. 저장소 클론:

git clone https://github.com/Young4424/Stardew-valley-NPC-advisor.git


2. 필요 패키지 설치
pip install -r requirements.txt

3. 환경 변수 설정 (또는 .env 파일 생성)


4. 애플리케이션 실행:
jupyter notebook openai_gradio_0314.ipynb


cf) Azure AI Search에서 데이터를 학습하고 의미 체계를 구성해야 합니다.

### 데이터 출처 
https://www.kaggle.com/datasets/srgiomanhes/stardew-valley-villagers-dataset

https://www.kaggle.com/datasets/jessicaebrown/stardew-valley-full-catelog



