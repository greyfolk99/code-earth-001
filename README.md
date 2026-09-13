# CODE EARTH — 지금, 지구
<img width="2391" height="1034" alt="image" src="https://github.com/user-attachments/assets/f641b00d-8b7e-43f2-9a9b-ce99b046afda" />

NASA 위성과 기상 예보 데이터로 그리는 실시간 인터랙티브 지구.
전투기 HUD 감성의 지구본 위에 지금 이 순간의 기상·위성·지정 데이터를 얹었습니다.

### 🌐 라이브 데모 → **https://code-earth-001.vercel.app**

## 주요 기능
- **실시간 기상 레이어** — 강수·바람·구름, 그리고 기온·기압·습도·가강수량·CAPE·돌풍·이슬점 같은 스칼라 필드. NOAA GFS 예보장을 하나의 시간축으로 묶어 자동 재생합니다.
- **GPU 바람 유선** — 실제 궤적을 따라 흐르는 파티클 스트림라인(WebGL2 커스텀 프리미티브). 씨앗 수·길이·속도를 실시간 조절.
- **위성 궤도 추적** — 기상위성·우주정거장의 현재 궤도를 실시간 계산, 조준·타겟 락 (CelesTrak TLE · SGP4).
- **지정학 레이어** — 국경선·해안선·국가 정보(인구·GDP·수도·언어).
- **전투기 HUD UI** — 홀로그램 패널, 줌 다이얼, 타게팅, 매트릭스 리빌 연출.

## 기술 스택
Next.js 16 · CesiumJS · WebGL / GLSL · TypeScript · Tailwind CSS

데이터 출처: NASA GIBS · NOAA GFS · CelesTrak · Natural Earth

---
소스 코드는 비공개입니다.
