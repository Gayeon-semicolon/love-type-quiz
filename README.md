# 💌 나의 연애 유형 테스트

애착 이론 기반의 연애 성향 분석 웹사이트입니다.

## 기능

- 성별(여성/남성)과 닉네임 입력
- 성별에 맞춘 20문항 리커트 척도 질문
- 4가지 애착 유형(안정/불안/회피/공포회피) 점수 계산
- 여성 12가지, 남성 12가지 유형 중 자동 매칭
- 상세 결과 (성향 요약, 강점, 주의할 점, 실제 모습, 궁합 유형)
- 결과 공유 기능

## 배포 방법

### 1. GitHub에 업로드
```bash
git init
git add .
git commit -m "첫 번째 배포"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/love-type-quiz.git
git push -u origin main
```

### 2. Vercel에서 배포
1. [vercel.com](https://vercel.com) 접속
2. GitHub 연동 후 이 레포지토리 선택
3. "Deploy" 클릭

배포 완료 후 자동으로 URL이 생성됩니다.

## 파일 구조

```
love-type-quiz/
├── index.html      # 메인 (전체 퀴즈 + 결과 + 스타일)
├── vercel.json     # Vercel 배포 설정
└── README.md       # 이 파일
```

## 기술 스택

- Vanilla HTML/CSS/JavaScript (외부 의존성 없음)
- Google Fonts (Gowun Batang, Noto Sans KR)
- Vercel Static Hosting
