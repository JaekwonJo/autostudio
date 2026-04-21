# autostudio

자동화 스튜디오 HTML 도구 보관 저장소입니다.

## 웹사이트로 열기

GitHub Pages를 켜면 아래 주소로 어디서든 접속할 수 있습니다.

```text
https://jaekwonjo.github.io/autostudio/
```

처음 한 번만 GitHub 저장소에서 `Settings` → `Pages` → `Build and deployment`를 `Deploy from a branch`로 선택하고, Branch를 `main` / `/ (root)`로 저장하면 됩니다.

## 포함 도구
- `index.html`
  - 웹사이트 첫 화면 진입 파일
  - `⚡자동화스튜디오.html`로 자동 이동
- `⚡자동화스튜디오.html`
  - 파일관리에서 일반 `S###` 표준화 변경과 별도로 `S### -> @S###` 전용 일괄 변경 버튼 지원
  - 동영상 파일 선택 후 분/초 위치의 프레임을 PNG로 저장하는 기능 지원
- `유튜브_쇼츠_API_발굴기.html`
  - 화면 이름: `유튜브 핫토픽 레이더`
  - 공식 YouTube Data API v3 기반
  - 고조회수 Shorts 후보 검색 + 오늘의 고조회수 영상 + 최근 N일 고조회수 영상 검색 지원
  - 경제 / 역사 / 교육 / 과학 / AI / 시사 / 자기계발 주제 프리셋 지원
  - `전체 / 쇼츠만 / 롱폼만` 길이 분류 필터, 결과 정렬(조회수/최신/좋아요/댓글/길이) 지원
  - API 키 영역은 기본 접힘 상태로 시작
  - 검색 후 조회수 / 길이 / 날짜로 다시 필터링
