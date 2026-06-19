# 🏆 이상형 월드컵 메이커

누구나 이상형 월드컵을 만들고 링크 하나로 공유할 수 있는 프로젝트입니다.  
서버 없이 순수 HTML/CSS/JS로 동작하며, 데이터는 URL에 인코딩되어 공유됩니다.

---

## 🚀 배포 방법

### 1. GitHub에 올리기

```bash
git init
git add .
git commit -m "🏆 이상형 월드컵 메이커 초기 배포"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/worldcup-maker.git
git push -u origin main
```

### 2. Vercel로 배포

1. [vercel.com](https://vercel.com) 에 GitHub 계정으로 로그인
2. **"Add New Project"** 클릭
3. 방금 만든 레포를 선택 → **Deploy** 클릭
4. 완료! 자동으로 `https://your-project.vercel.app` 링크가 생성됩니다

> 이후 `main` 브랜치에 push할 때마다 자동으로 재배포됩니다.

---

## 📁 파일 구조

```
worldcup-maker/
├── index.html    # 월드컵 만들기 페이지
├── play.html     # 월드컵 플레이 페이지 (공유 링크 대상)
├── vercel.json   # Vercel 배포 설정
└── README.md
```

## ✨ 기능

- 후보 추가 (이름 + 설명 + 이미지 업로드 or URL)
- 4강 / 8강 / 16강 / 32강 선택
- 링크 하나로 공유
- 토너먼트 진행 + 최종 우승자 발표
- 경기 결과 요약

## 🛠 기술 스택

- Vanilla HTML / CSS / JavaScript
- 데이터는 Base64로 인코딩해 URL 해시에 저장 (서버 불필요)
- Google Fonts (Noto Sans KR, Black Han Sans)
