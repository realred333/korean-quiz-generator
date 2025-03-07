# 한국어 문제 생성기 (Korean Quiz Generator)

Google Gemini API를 활용한 한국어 지문 기반 문제 생성 애플리케이션입니다.

## 주요 기능

- 한국어 지문을 입력하면 AI가 자동으로 문제를 생성합니다.
- 객관식, 주관식, 서술형 등 다양한 문제 유형 지원
- 난이도 조절 기능 (쉬움, 보통, 어려움)
- 생성된 문제 저장 및 내보내기
- 다크 모드 등 다양한 테마 지원

## 설치 방법

1. 저장소 클론
```bash
git clone https://github.com/realred333/korean-quiz-generator.git
cd korean-quiz-generator
```

2. 필요한 패키지 설치
```bash
pip install -r requirements.txt
```

3. Google Gemini API 키 설정
- [Google AI Studio](https://aistudio.google.com/)에서 API 키를 발급받습니다.
- 프로젝트 루트에 `.env` 파일을 생성하고 다음과 같이 API 키를 설정합니다:
```
GEMINI_API_KEY=your_api_key_here
```

## 사용 방법

1. 애플리케이션 실행
```bash
python app.py
```

2. 한국어 지문을 입력 창에 붙여넣기 또는 입력합니다.
3. 문제 수, 문제 유형, 난이도를 선택합니다.
4. "문제 생성하기" 버튼을 클릭합니다.
5. 생성된 문제는 하단 창에 표시되며, 파일로 저장할 수 있습니다.

## 주요 기술 스택

- Python 3.8+
- Tkinter (GUI)
- Google Generative AI (Gemini API)
- 비동기 처리 (ThreadPoolExecutor)

## 라이센스

MIT License

## 기여하기

이슈와 풀 리퀘스트는 언제나 환영합니다. 대규모 변경사항은 먼저 이슈를 열어 논의해주세요.