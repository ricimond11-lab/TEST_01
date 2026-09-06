# Hello Flask

가장 단순한 Flask 웹앱입니다.

## 실행 방법

1. 가상환경 생성 및 활성화

   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

2. 패키지 설치

   ```bash
   pip install -r requirements.txt
   ```

3. 환경변수 설정

   `.env.example` 파일을 참고하여 `.env` 파일을 만들고 `SECRET_KEY` 값을 채워주세요.

4. 앱 실행

   ```bash
   python app.py
   ```

5. 브라우저에서 확인

   http://localhost:5000
