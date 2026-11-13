# stocklink-news

[stocklink.netlify.app](https://stocklink.netlify.app) 의 "반도체·AI 뉴스" 섹션 데이터.

JunTrade 서버(`news_publish.py`)가 10분마다 `news.json` 을 갱신한다. 직접 수정하지 말 것.

- `items[].title`: 기사 원문 제목
- `items[].ko`: 영문 기사의 한글 번역 (한글 기사는 빈 값)
- `items[].link`: 기사 링크
