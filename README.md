# COMPUTE GRID API

여성경제신문 [깐팩] 기사 연동용 정적 데이터 원장 + 시각화 페이지.

## 파일
- `grid.json` : 국가별 GW, 상태값, SKT 목표, 물리 경로
- `index.html` : `grid.json`을 읽어 화면을 자동 생성
- `README.md` : 설명

## GitHub Pages
Settings → Pages → Deploy from a branch → `main` / `(root)`

## 업데이트
숫자를 바꿀 때는 `grid.json`만 수정합니다.
`index.html`은 데이터값을 자동으로 읽습니다.

주의: 국가별 capacity basis와 state는 완전히 동일하지 않습니다.
