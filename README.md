# QUIZ_GAME_mini_project
파이썬으로 만든 콘솔 기반 퀴즈 게임.
“넌센스”와 “IT 용어” 두 가지 종류의 퀴즈를 JSON 파일로 관리하고, 랜덤 출제/정답 체크/점수 집계 기능을 제공합니다.

## 프로그램 구조
**4가지의 json 파일**
- Q_nonsense.json : nonsense quiz의 문제를 dictionary 형태로 저장
- A_nonsense.json : nonsense quiz의 정답을 dictionary 형태로 저장
- Q_IT.json : IT 용어 quiz의 문제를 dictionary 형태로 저장
- A_IT.json : IT 용어 quiz의 정답을 dictionary 형태로 저장
  
**2가지의 실행 파일**
- quiz_DB.py
- quiz_main.py

```bash
        .
        ├── Q_nonsense.json # nonsense 문제(딕셔너리 형태) 
        ├── A_nonsense.json # nonsense 정답(딕셔너리 형태)
        ├── Q_IT.json # IT 문제(딕셔너리 형태)
        ├── A_IT.json # IT 정답(딕셔너리 형태)
        ├── quiz_DB.py # DB/문제 선택 관련 로직
        ├── quiz_main.py # 메인 실행 파일(게임 실행)
        └── README.md
```

## 기술 스택
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
버전 : Python 3.13.7


## 프로그램 환경
## 실행 결과 (코드 실행하면 무슨일이?) - 단계별

## 프로젝트 후기

## 참고
https://cocoon1787.tistory.com/689 (기술스택 벳지 설정방법 링크)


---------
### GPT 기술스택에 대한 답변

## 🛠 기술 스택 (Tech Stack)

### 언어 & 런타임
- **Python 3.x**
  - 기본 문법 (변수, 자료형, 조건문, 반복문, 함수, 클래스)
  - 객체지향 프로그래밍 (클래스/메서드 설계)
  - 문자열 처리 (`strip()`, `lower()` 등)

### 주요 라이브러리
- **random** : 문제 랜덤 추출
- **typing** : 타입 힌트(`List`, `Dict`)로 코드 가독성 향상
- **threading** *(선택)* : 시간 제한 기능 구현 시 활용

### 프로그램 구조
- **클래스 기반 설계**
  - `Question` : 문제와 정답 관리
  - `QuizSet` : 문제집 관리 및 랜덤 추출
  - `QuizGame` : 메뉴 출력, 게임 진행, 정답 확인
- 함수형 프로그래밍 일부 활용 (정답 비교, 입력 처리)

### 개발 환경
- **OS** : Windows 10/11
- **IDE/Editor** : Visual Studio Code
- **버전 관리** : Git / GitHub

### 협업 & 관리
- GitHub Repository로 코드 버전 관리
- README.md를 통한 문서화

---
-----------!!!! 예지님 일단 저는 이런식으로 한번 풀로 작성 해보고 있어요. 이거 넣으면 좋을거 같다 하는 부분 서로 얘기해보고 보완해서 완성해보아요 !!!!! (소영)
## 📌 프로젝트 특징
- CLI(콘솔 기반) 퀴즈 게임
- OOP(Object-Oriented Programming) 적용
- 사용자 입력 처리 (공백/대소문자 무시)
- 문제 랜덤 출제 기능
- *(선택 기능)* 제한 시간 내 정답 입력

# 🧩 Python Quiz Game
콘솔 기반 랜덤 퀴즈 게임

# 🎮 게임 시작 화면
(시작 부분만 스크린샷?)

# 프로그램 특징
(사용자가 실행했을 때 체감할 수 있는 결과물 / 사용 경험 기록) (** 괄호 내용은 아래 목록으로 따로 빼내기?)
- 게임 선택 기능 → 2개의 퀴즈 게임 중 원하는 게임을 선택할 수 있음 (프로그램의 아쉬움-> 파이썬 객체지향언어(OOP)의 특징을 살려보려고 하였으나 첫 프로젝트 경험이다 보니까 2개의 퀴즈 게임밖에 구성하지 못했다는 아쉬움)
- 🤗 첫 실행 화면에서 귀여운 이모티콘을 만나볼 수 있음 🤗
- 랜덤 문제 출제 기능 → 게임을 실행할 때마다 새로운 문제를 풀어볼 수 있음 (아쉬움 -> 역시나 좀 더 다양한 출제 문제가 있었으면 좋았을 듯)
- 20초 안에 문제의 답을 입력해야 하기 때문에 게임을 조금 더 흥미롭게 느낄 수 있음

