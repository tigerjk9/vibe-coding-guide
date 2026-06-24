# 초등교사를 위한 바이브코딩 — 고급 활용 & 안정적 배포

초등 교사 연수 자료입니다. **Gemini Canvas / Claude**로 수업용 웹앱을 만들고, **GitHub Pages · Netlify**로 고정 URL에 배포하는 과정을 단계별로 다룹니다.

> 이 사이트 자체가 **단일 HTML 파일**이며, 같은 파일을 두 방식(GitHub Pages·Netlify Drop)으로 그대로 배포할 수 있는 예시로 쓰입니다.

## 🌐 배포 링크

- **GitHub Pages**: https://tigerjk9.github.io/vibe-coding-guide/

## 📚 구성

| 섹션 | 내용 |
|------|------|
| 홈 | 학습 흐름 6단계, 핵심 메시지 |
| 제작 가이드 | 입문 vs 고급 비교, 워크플로 7단계, 완성도 5기법 |
| 프롬프트 | 8요소 공식 + 상황별 템플릿 + **이 디자인을 요청하는 프롬프트** |
| 배포 비교 | Canvas vs Netlify vs GitHub Pages 비교 + 단계 |
| 갤러리 | 교과별 예제 6종 + 작동하는 분수 퀴즈 데모 |
| 체크리스트 | 배포 전 점검 + 문제 해결 + 안전·윤리 |

## 🎨 디자인

- 네오브루탈리즘(Neo-brutalism): 두꺼운 검정 테두리 · 흐림 없는 하드 섀도우 · 단색 강조
- Tailwind CSS (CDN) + Pretendard
- 외부 빌드 도구 없이 `index.html` 단일 파일
- 이 디자인을 AI에게 요청하는 방법은 사이트의 **프롬프트 탭 → "이 사이트처럼 만들려면?"** 참고

## 🚀 직접 배포하기

**GitHub Pages**
1. 저장소 → Settings → Pages
2. Source: `GitHub Actions` (이 저장소는 `.github/workflows/deploy.yml`로 자동 배포)
3. `main`에 푸시하면 자동으로 빌드·배포

**Netlify Drop** — 가장 쉬움
1. `index.html`을 그대로 둔 채 [app.netlify.com/drop](https://app.netlify.com/drop) 접속
2. 폴더(또는 파일)를 드래그 & 드롭 → 고정 URL 생성

---

- **원작**: [techkwon/vibe-coding-guide](https://github.com/techkwon/vibe-coding-guide)
- **수정·편집**: 김진관 (닷커넥터)
