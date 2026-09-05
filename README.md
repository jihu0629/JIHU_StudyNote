# 포트폴리오 사이트

MkDocs Material로 만든 개인 개발 포트폴리오 사이트입니다.

## 로컬에서 실행하기

```bash
python -m venv .venv
.venv\Scripts\pip install -r requirements.txt
.venv\Scripts\python -m mkdocs serve
```

브라우저에서 <http://127.0.0.1:8000> 접속하면 됩니다. `docs/` 안의 파일을 수정하면 자동으로 새로고침됩니다.

## 새 페이지 추가하기

1. `docs/` 아래 원하는 위치에 `.md` 파일 생성
2. `mkdocs.yml`의 `nav` 항목에 파일 경로 추가

## 정적 사이트 빌드

```bash
.venv\Scripts\python -m mkdocs build
```

`site/` 폴더에 정적 HTML이 생성됩니다.

## GitHub Pages로 배포하기 (선택)

```bash
.venv\Scripts\python -m mkdocs gh-deploy
```

GitHub 저장소를 만들고 원격(origin)을 연결한 뒤 실행하면 `gh-pages` 브랜치로 배포됩니다.
