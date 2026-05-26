# Purely:SOOM (퓨어리숨) 🌿

**금연 디지털치료제(DTx) 프로토타입**

> 흡연 욕구가 올라오는 그 순간, 앱이 먼저 손을 내미는 디지털 치료제.

---

## 팀 소개 · Team Soomers [수머즈]

| 이름 | 소속 |
|---|---|
| 박정호 | 홍익대학교 / 소프트웨어융합과 |
| 문해진 | 단국대학교 / 보건행정학과 |
| 송은주 | 단국대학교 / 보건행정학과 |
| 선한별 | 단국대학교 / 보건행정학과 |

---

## 프로토타입 바로 열기

### 🌐 GitHub Pages 배포 버전
**환자 앱**: https://jeongttak.github.io/DTX_team2/share-patient.html  
**의사 대시보드**: https://jeongttak.github.io/DTX_team2/share-doctor.html  
**랜딩 페이지**: https://jeongttak.github.io/DTX_team2/

### 로컬 실행
`docs/share-patient.html` 을 브라우저에서 열기

```
docs/
├── index.html           ← 랜딩 페이지
├── share-patient.html   ← 환자 앱 풀 플로우
├── share-doctor.html    ← 의사 대시보드
└── assets/              ← 이미지 리소스
```

---

## 주요 화면 (10개 스크린)

| 화면 | 설명 |
|---|---|
| 스플래시 | 로고 + 3초 자동 진입 |
| 로그인 | 환자/의사 롤 전환, 의사 코드 매칭 |
| 온보딩 | 10문항 CBT 흡연 타입 진단 (6가지 유형) |
| 홈 | 금연 스트릭, 절약 금액, 건강 회복 4지표 |
| 미션 | 일/주/월 탭, 자동연동 vs 수동 체크 |
| CO 측정 | 호기 측정 플로우 + 7일 추이 차트 |
| 캐릭터 | 다마고치 성장 + 6카테고리 꾸미기 + 도감 |
| 캘린더 | 인증·흡연·미측정 3분류 월별 뷰 |
| 트리거 플로우 | 상태체크 → 기록 → 소크라테스 CBT |
| CO 경고 | 미인증 3단계 에스컬레이션 |

---

## 기술 스택

- **React 18** (CDN, no build step)
- **Babel Standalone** (JSX in browser)
- **Pure CSS** (CSS variables + animations)
- 단일 HTML 파일로 배포 가능

---

## 실행 방법

### 온라인 (권장)
위의 GitHub Pages 배포 버전 URL 접속

### 로컬
```bash
# docs 폴더에서 파일 열기
open docs/share-patient.html
# 또는
cd docs && python -m http.server 8000
# → http://localhost:8000/share-patient.html
```

> ⚠️ CDN 로드를 위해 인터넷 연결 필요 (React, Babel)

---

*v1.2.0 · Prototype only — 실 데이터 아님*
