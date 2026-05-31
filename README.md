# 학습 시간표

GitHub Pages에 올려서 핸드폰 홈 화면에 추가해 사용하는 학습 시간표 앱입니다.

## 파일

- `index.html`: 실제 앱
- `print-4weeks.html`: A4 한 장 4주 출력용 페이지
- `manifest.json`: 홈 화면 앱 설정
- `service-worker.js`: 캐시 설정
- `icon.svg`: 홈 화면 아이콘

## GitHub Pages

1. GitHub repository 최상단에 이 파일들을 올립니다.
2. `Settings` > `Pages`로 이동합니다.
3. `Deploy from a branch`, `main`, `/root`를 선택합니다.
4. 생성된 주소를 Safari에서 열고 홈 화면에 추가합니다.

체크 기록과 시간표 구성은 브라우저의 `localStorage`에 저장됩니다.
