# 🍌 Nano Banana 2 완전 가이드

> Google Gemini 기반 AI 이미지 생성 모델 **Nano Banana 2**의 출시 변화, 실제 활용사례, 검증된 프롬프트를 카테고리별로 총정리한 웹 가이드입니다.

[![Vercel](https://img.shields.io/badge/Vercel-Deployed-black?style=flat-square&logo=vercel)](https://nano-banana-2-guide.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/techkwon/nano-banana-2-guide?style=flat-square)](https://github.com/techkwon/nano-banana-2-guide/commits/main)

**🌐 라이브 사이트:** [https://nano-banana-2-guide.vercel.app](https://nano-banana-2-guide.vercel.app)

---

## 📋 목차

- [소개](#소개)
- [주요 콘텐츠](#주요-콘텐츠)
- [스크린샷](#스크린샷)
- [기술 스택](#기술-스택)
- [로컬 실행](#로컬-실행)
- [기여 방법](#기여-방법)

---

## 소개

Nano Banana 2는 Google이 2026년 초 출시한 Gemini 3 Pro Image 기반의 AI 이미지 생성 모델입니다. 전작 대비 해상도 4배 향상(최대 4K), 텍스트 렌더링 혁신, 20가지 아트 스타일 지원 등 대폭 업그레이드되었습니다.

이 프로젝트는 Reddit, Tom's Guide, CNET, Max Woolf's Blog 등 다양한 커뮤니티와 미디어에서 수집한 **50개 이상의 실제 사용 사례**와 **30개 이상의 검증된 프롬프트**를 한 곳에 정리한 참고 가이드입니다.

---

## 주요 콘텐츠

### 🔄 출시 변화 (NB1 → NB2)

| 항목 | Nano Banana 1 | Nano Banana 2 |
|------|--------------|--------------|
| 기반 모델 | Gemini 2.5 Flash Image | Gemini 3 Pro Image |
| 최대 해상도 | 1K (1024×1024) | 4K (4096×4096) |
| 텍스트 렌더링 | 오류 빈번 | 다국어 정확 지원 |
| 참조 이미지 | 제한적 | 최대 14개 통합 |
| 아트 스타일 | 기본 | 20가지 전문 스타일 |
| AI 식별 | 기본 메타데이터 | SynthID + C2PA |

### 🎯 활용사례 카테고리 (50개+)

| 카테고리 | 사례 수 | 대표 활용 |
|---------|--------|---------|
| 🎭 피규어 & 굿즈 | 6개 | 1/7 스케일 피규어, 펀코 팝, 봉제 인형 |
| 👗 패션 & 가상 착용 | 4개 | 이브닝 가운, 룩북 제작, 스트리트웨어 |
| 🖼️ 이미지 편집 | 6개 | 객체 제거, 배경 교체, 스타일 변환 |
| 📊 마케팅 & 인포그래픽 | 3개 | 데이터 시각화, 광고 배너, SNS 카드 |
| 🎨 애니메이션 & 일러스트 | 3개 | 사이버펑크, 지브리 스타일, 만화 컬러화 |
| 🍕 음식 & 제품 | 3개 | 음식 사진, 제품 목업, 메뉴 이미지 |
| 🏠 건축 & 인테리어 | 3개 | 리모델링 시뮬레이션, 3D 렌더링 |
| 🏷️ 브랜드 & 로고 | 2개 | 스타트업 로고, 책 표지 |

### ✍️ 검증된 프롬프트 (30개+)

각 프롬프트는 실제 커뮤니티에서 검증된 결과와 함께 제공됩니다. 복사 버튼으로 즉시 사용 가능합니다.

**대표 프롬프트 예시:**

```
A commercialized 1/7 scale figure of the character in the illustration,
in a realistic style and environment. Use a circular transparent acrylic
base with no text, placed on a computer desk. Display the figure's ZBrush
modeling process on the computer screen. Place a BANDAI-style toy packaging
box with the original artwork printed on it next to the computer screen.
```

### 💡 프롬프트 작성 팁 (12가지)

행동 동사 사용, 조명 조건 명시, 영어 프롬프트 권장, 참조 이미지 활용 등 커뮤니티가 검증한 노하우를 정리했습니다.

---

## 스크린샷

| 히어로 섹션 | 활용사례 섹션 |
|:-----------:|:------------:|
| ![Hero](images/hero_nb2.png) | ![Cases](images/figure_desk.jpg) |

---

## 기술 스택

- **Frontend:** Vanilla HTML5 / CSS3 / JavaScript
- **폰트:** Noto Sans KR (Google Fonts)
- **호스팅:** Vercel (자동 배포)
- **버전 관리:** GitHub

별도의 빌드 도구나 프레임워크 없이 순수 HTML/CSS/JS로 제작되어 가볍고 빠릅니다.

---

## 로컬 실행

```bash
# 저장소 클론
git clone https://github.com/techkwon/nano-banana-2-guide.git
cd nano-banana-2-guide

# 로컬 서버 실행 (Python 3)
python3 -m http.server 8080

# 브라우저에서 접속
open http://localhost:8080
```

---

## 기여 방법

새로운 활용사례나 프롬프트를 발견하셨나요? 기여를 환영합니다!

1. 이 저장소를 Fork합니다.
2. 새 브랜치를 생성합니다. (`git checkout -b feat/new-case`)
3. 변경사항을 커밋합니다. (`git commit -m 'feat: 새로운 활용사례 추가'`)
4. 브랜치에 Push합니다. (`git push origin feat/new-case`)
5. Pull Request를 생성합니다.

---

## 출처

이 가이드는 다음 출처에서 수집한 정보를 바탕으로 작성되었습니다.

- [Reddit r/ChatGPTPromptGenius](https://www.reddit.com/r/ChatGPTPromptGenius/)
- [Tom's Guide](https://www.tomsguide.com)
- [CNET](https://www.cnet.com)
- [Max Woolf's Blog](https://minimaxir.com)
- [nano2image.com](https://nano2image.com)
- [Fotor Blog](https://www.fotor.com/blog/)
- [Digital Trends](https://www.digitaltrends.com)

---

## 라이선스

MIT License — 자유롭게 사용, 수정, 배포 가능합니다.

---

<p align="center">
  Made with ❤️ · <a href="https://nano-banana-2-guide.vercel.app">라이브 사이트 방문</a>
</p>
