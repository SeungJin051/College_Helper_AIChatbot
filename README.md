![Untitled-6-01](https://github.com/SeungJin051/College_Helper_AIChatbot/assets/83889135/9aa02e96-7bf8-4eb4-b3a2-5edf17ea2d77)
<img width="1105" alt="스크린샷 2023-10-17 오후 10 51 15" src="https://github.com/SeungJin051/College_Helper_AIChatbot/assets/83889135/b5dcd9c7-b6b8-4178-8bfe-74db85f49003">
# College_Helper_AIChatbot | 대학생활 도우미 AI챗봇 
> 동의과학대학교 전공동아리 AI Coding Club 출품작!
>> 파이팅!

---

## 기술 스택
- Botpress
- StackAI
- JS

## 배포
- Github Pages
- Botpress Cloud

## [가이드라인](https://github.com/SeungJin051/College_Helper_AIChatbot/blob/main/%20%E1%84%83%E1%85%A2%E1%84%92%E1%85%A1%E1%86%A8%E1%84%89%E1%85%A2%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AF_%E1%84%83%E1%85%A9%E1%84%8B%E1%85%AE%E1%84%86%E1%85%B5_AI%E1%84%8E%E1%85%A2%E1%86%BA%E1%84%87%E1%85%A9%E1%86%BA_%E1%84%80%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B3%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%86%AB.pdf "가이드라인")


## [서비스 소개서](https://github.com/SeungJin051/College_Helper_AIChatbot/blob/main/%20%E1%84%89%E1%85%A5%E1%84%87%E1%85%B5%E1%84%89%E1%85%B3%20%E1%84%89%E1%85%A9%E1%84%80%E1%85%A2%E1%84%89%E1%85%A5-AI_Coding_Club.pdf "서비스 소개서")

---

# Why AIChatbot?
1. **프로젝트 개요**
    - DIT chatbot은 대학생들을 위한 ChatGPT 기반의 질의응답 챗봇입니다.
    - 이 프로젝트는 대학 생활에서 자주하는 교무부 문의, 학교생활과 관련된 정보, 그리고 캠퍼스 시설 안내 등 주제에 관한 사용자 질문에 유용한 답변을 제공합니다.
    - ChatGPT 기반의 AIChatbot으로써 성격부여의 부드러운 답변, 정보 학습, 데이터 저장이 가능합니다.

2. **목표**
    - 사용자(대학생) 질문에 대한 정확하고 유용한 학습된 정보를 제공:
        - DIT chatbot은 사용자(대학생)들의 교무부, 학교생활, 캠퍼스 안내에 관한 다양한 질문에 대해 정확하고 유용한 답변을 제공
    - 손쉬운 접근으로 사용:
        - PC, 모바일 제공 및 페이스북 메신저 (Messenger) 임베딩
3. **기능 설명**
   이 프로젝트는 다음과 같은 주요 기능을 제공합니다:  
    - 대학생활 : 교무부, 교내 통학|셔틀 버스에 대한 정보와 (시설이용 정보)를 학습시켜 사용자의 질문을 대답해주는 기능
    - 캠퍼스 안내 : 캠퍼스의 시설들을 학습시켜 사용자의 질문을 대답해주는 기능
    - 학사일정 : 월별 학사일정을 알려줍니다.
    - ChatGPT : Chatbot에서 ChatGPT를 구동하는 기능
    - 건의하기 : 사용자 피드백을  Table에 저장하는 기능
    - (만약 학습되지 않은 정보는 Table에 저장된다.)
    
    이 서비스는 Text, .pdf, .html, .txt, .doc, .docx 문서와 웹페이지를 학습시켜 콘텐츠를 이해하고 처리하는 기능을 갖추고 있습니다.
   
# What?
**Build ChatGPT chatbot surprisingly fast!을 목표로하는 Botpress와 StackAI(LLM)을 이용한 보다 빠른 개발**

## 그래서 Botpress랑 StackAI가 뭔데? 왜 쓰는데?
### Botpress : 오픈 소스 챗봇 개발 플랫폼으로, 대화형 인터페이스와 챗봇을 구축하는 데 사용되는 기술
<img width="948" alt="스크린샷 2023-10-17 오후 11 08 24" src="https://github.com/SeungJin051/College_Helper_AIChatbot/assets/83889135/2866f0ab-bdd3-44a4-80d9-6ca417233c89">

- Botpress는 무료로 사용할 수 있는 오픈 소스 챗봇 개발 플랫폼입니다. 이를 통해 개발 비용을 절감하고 빠르게 챗봇을 구축할 수 있습니다.
- 봇프레스는 다양한 기능을 제공하며, 사용자 관리, 대화 흐름 관리, 자연어 처리(NLP) 기능, 웹 기반 인터페이스 등 다양한 모듈을 활용하여 챗봇을 쉽게 개발할 수 있습니다. 
- 자연어 처리 기능을 통해 사용자의 입력을 이해하고 응답을 생성합니다. 
- 웹 기반 인터페이스를 통해 비개발자도 쉽게 챗봇을 관리하고 모니터링할 수 있으며, 다국어 처리를 지원하여 다양한 언어로 챗봇을 개발할 수 있습니다. 

### StackAI : 대형 언어 모델 (LLM)을 사용하여 AI 워크플로우를 설계, 테스트 및 배포 할 수있는 도구
<img width="1173" alt="스크린샷 2023-10-17 오후 11 07 07" src="https://github.com/SeungJin051/College_Helper_AIChatbot/assets/83889135/0c121da1-c9ab-4706-9b2b-a1445588a929">

- ChatGPT와 같은 대형 언어 모델을 사용하여 AI 워크플로를 설계, 테스트 및 배포할 수 있습니다. 
- 사용자는 직관적인 그래픽 인터페이스를 통해 대형 언어 모델(LLM), 벡터 데이터베이스, 도구 및 데이터 로더를 쉽게 연결할 수 있습니다. 
- 개발자 팀은 Stack AI를 사용하여 다양한 애플리케이션을 만들 수 있으며, 이를 통해 고객 지원 자동화, 문서 처리, 영업 리드 검증, 데이터 라이브러리 검색 등의 다양한 작업을 수행할 수 있습니다.

# How?
Botpress를 통한 챗봇을 개발한다.<br>
Botpress의 지식베이스, 성격, 노드, 변수를 활용한다.<br>
챗봇의 개발에는 공식 Youtube, Docs를 확인하면 된다.<br>
예외처리 및 유연한 데이터 업데이트를 위한 StackAI를 JS API로 연동한다. 그러면 원하는 정보를 학습한 AIChatbot이 빌드된다.

# IF.
정보화 시대 정보를 찾기 힘들어하는 대학생이 많다. 쉽고, 간단한 질문도 찾아보고 까먹게된다. <br>
이에 AIChatbot은 PC와 모바일의 손쉬운 접근으로 모르는 정보를 손쉽게 얻을 수 있을 것으로 기대됩니다. AI에는 데이터가 아주 중요합니다. <br>
저는 학교에서 내려주는 교내_대학_생활_백서.pdf를 참고하여 정보를 가공했습니다. <br>
하지만 저의 솔루션은 학습되지 않은 질문을 저장하고 추후에 우연한 업데이트가 가능하기에 사용자가 원하는 질문과 데이터 수집이 원할하다라고 생각하며 <br>
자동으로 테이블에 기록이 되기 때문에 부담없이 AIChatbot과 상호작용이 가능할 것입니다.

---

<img width="581" alt="스크린샷 2023-10-17 오후 11 40 27" src="https://github.com/SeungJin051/College_Helper_AIChatbot/assets/83889135/da29b68b-f0b2-4a9d-9a9d-93d488258d0f">

