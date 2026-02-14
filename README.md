# 260213mini 작업 결과물 파일 트리

본 폴더(`260213mini`)의 작업 결과물 구조는 다음과 같습니다.

```text
260213mini/
├── docs/                   # 네이버 API 관련 문서 모음
│   ├── datalab.md          # 데이터랩 API 개요 및 주요 특징
│   ├── news_search.md      # 뉴스 검색 API 가이드
│   ├── non_login_api.md    # 비로그인 방식 오픈 API 리스트
│   ├── shopping_insight.md  # 쇼핑인사이트 API 상세 레퍼런스
│   └── shopping_search.md   # 쇼핑 검색 API 상세 레퍼런스
├── data/                   # 데이터 수집 결과 저장 폴더 (CSV 형식)
├── .env                    # Naver API Client ID/Secret 관리 파일
├── instruction_shopping_trend.md  # 쇼핑 트렌드 수집 및 확인 작업지시서
└── README.md               # 본 파일 트리 및 결과물 안내 문서
```

### 주요 안내
- **데이터 저장 규칙**: 수집된 데이터는 `data/` 폴더에 `[내용]_[수집날짜].csv` 형식으로 저장합니다.
- **인증 정보**: `.env` 파일에 발급받은 `CLIENT_ID`와 `CLIENT_SECRET`을 설정하여 사용합니다.
- **작업 계획**: 상세 수집 계획은 `instruction_shopping_trend.md`를 참고하십시오.
