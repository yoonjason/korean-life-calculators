# 생활 계산기 (Korean Life Calculators)

한국 생활에 필요한 계산기 모음. 설치 없이 브라우저에서 바로 사용.

## 계산기

- **음력 변환기** (`lunar.html`) — 양력↔음력, 한국천문연구원(KASI) 기준, 윤달 정확
- **축의금·조의금 계산기** (`gift-money.html`) — 관계·친밀도·참석 여부로 적정 금액 추천 (2025 설문 기준)
- 제삿날 계산기 — 준비중

## 기술

- 정적 HTML + Vanilla JS (빌드 불필요)
- 음력 변환: [`korean-lunar-calendar`](https://www.npmjs.com/package/korean-lunar-calendar) (esm.sh CDN, KASI 동일 기준)
- iOS 앱 엔진: [KoreanLunarKit](https://github.com/yoonjason/KoreanLunarKit) (Swift, KASI 기준)
- 배포: GitHub Pages

## 로컬 실행

별도 빌드 없이 `index.html`을 브라우저로 열면 됩니다. (음력 변환기는 CDN 로드를 위해 인터넷 연결 필요)

자세한 전략·로드맵은 [DESIGN.md](./DESIGN.md) 참고.
