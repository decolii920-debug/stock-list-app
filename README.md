# 주식 종목 리스트 (Stock List App)

관심 종목을 손쉽게 추가하고 관리할 수 있는 심플한 웹 앱입니다. 별도의 서버 없이 브라우저의 `localStorage`에 데이터가 저장됩니다.

## 주요 기능

- 종목명 추가 (Enter 키 또는 추가 버튼)
- 체크박스로 보유/관심 상태 표시 (취소선 처리)
- 종목 삭제
- 전체 종목 수 · 체크된 종목 수 카운트
- 새로고침 후에도 목록 유지 (localStorage)

## 사용 방법

1. 저장소를 클론하거나 `index.html` 파일을 내려받습니다.
2. `index.html`을 브라우저로 엽니다 — 끝.

```bash
git clone https://github.com/decolii920-debug/stock-list-app.git
cd stock-list-app
# 브라우저로 index.html 열기
```

## 기술 스택

- HTML / CSS / Vanilla JavaScript
- 외부 의존성 없음 (단일 파일)
- 데이터 저장: 브라우저 `localStorage`
