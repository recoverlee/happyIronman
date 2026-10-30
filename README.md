# 행복철인 (2027 대회 훈련 플랜)

대구 마라톤(2027.2.28) → 군산 T100(2027.5.30) 훈련 플랜. 설치형 웹앱(PWA)이며 기록은 기기 안에만 저장돼요.

## 사용 / 설치
1. GitHub Pages로 배포: 저장소 Settings → Pages → Branch 선택 후 저장 (루트 `/`).
2. 폰에서 배포 주소를 열고 "홈 화면에 추가"(iOS: 공유 → 홈 화면에 추가 / Android: 설치).
3. 설치한 앱과 브라우저의 저장 공간은 따로일 수 있으니, 설치 후 처음 한 번 설정 탭에서 JSON 백업을 옮기세요.

## 로고 교체
`icons/` 폴더의 파일을 같은 이름으로 교체하세요: `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`(가장자리 여백 포함), `apple-touch-icon.png`(180×180). 교체 후 `sw.js`의 `CACHE` 이름(`training-plan-v7`)을 올리면 설치된 앱에 반영돼요.

## 파일
- `index.html` 앱 전체 · `manifest.webmanifest` 설치 정보 · `sw.js` 오프라인 캐시
