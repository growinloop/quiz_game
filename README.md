# 🧩 QUIZ GAME (mini project)
파이썬으로 만든 콘솔 기반 퀴즈 게임.  
“넌센스”와 “IT 용어” 두 가지 종류의 퀴즈를 JSON 파일로 관리하고, 랜덤 출제/정답 체크/점수 집계 기능을 제공합니다.

## 프로젝트 구조
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

## 프로그램 특징
- 게임 선택 기능 → 2개의 퀴즈 게임 중 원하는 게임을 선택할 수 있음
- 랜덤 문제 출제 기능 → 게임을 실행할 때마다 새로운 문제를 풀어볼 수 있음
- 정답 확인 기능 → 사용자가 입력한 답과 정답을 비교 후 결과 출력
- 입력 처리 기능 → 대소문자/공백 무시 → 누구나 편하게 정답 입력 가능
- 게임 종료/재시작 기능 → 원할 때 게임을 종료하거나 다시 시작 가능
- 점수 집계와 재도전 기능 → 계속 도전하며 실력 향상 가능
- 🤗 첫 실행 화면에서 귀여운 이모티콘을 만나볼 수 있음 🤗
- 20초 제한 시간 → 게임에 긴장감과 재미를 더함

## 기술 스택
### 언어 & 런타임
- **Python 3.13.7**
  - 기본 문법 (변수, 자료형, 조건문, 반복문, 함수, 클래스)
  - 객체지향 프로그래밍 (클래스/메서드 설계)
  - 문자열 처리 (`strip()`, `lower()`, `replace()` 등)

### 주요 라이브러리
- **random** : 문제 랜덤 추출
- **typing** : 타입 힌트(`List`, `Dict`)로 코드 가독성 향상

### 프로그램 구조
- **클래스 기반 설계**
  - `Question` : 문제와 정답 관리
  - `QuizSet` : 문제집 관리 및 랜덤 추출
  - `QuizGame` : 메뉴 출력, 게임 진행, 정답 확인
- 함수형 프로그래밍 일부 활용 (정답 비교, 입력 처리)

### 개발 환경
- **OS** : Windows 10/11
- **IDE/Editor** : Pycharm
  
### 협업 & 관리
- Git
- GitHub Repository로 코드 버전 관리
- README.md를 통한 문서화

<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">

## 참고
https://cocoon1787.tistory.com/689 (기술스택 벳지 설정방법 링크)
