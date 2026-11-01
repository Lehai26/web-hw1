실습 과제
le thanh hai/2551017

https://lehai26.github.io/web-hw1/

. GitHub에 web-hw1 공개(Public) 저장소 생성 및 기본 파일 업로드

. 루트 디렉토리에 소문자로 된 7개의 필수 파일 구성 (index.html, detail.html, style.css, README.md, w360.png, w768.png, w1280.png)

. API 키가 소스 코드에 노출되지 않도록 설정

. TMDB API 및 KOBIS API 연동 (기준일 2026-10-31)

. 메인 페이지(index.html) 레이아웃 및 스타일링 구현

. 상세 페이지(detail.html) 구현 (2열 구조, <dl> 5쌍, 배경 백드롭, 돌아가기 링크 등)

. .rank 클래스 및 ::before 가상 요소를 활용한 순위 표시 구현

. 카드 호버 시 8px 이동 효과 적용

. 반응형 그리드 시스템 구현 (1열 / 2열 / 4열 레이아웃 및 미디어 쿼리 2개 적용, max-width: 1100px)

. W3C 웹 표준 검증 (validator.w3.org) 에러 0개 달성

. 3가지 해상도(360px, 768px, ) 화면 캡처 이미지 정상 등록

[. README.md 작성 및 최종 GitHub Pages 배포 완료

어려웠던 점 3가지와 해결:

TMDB now_playing 링크 오류: 엔드포인트 URL을 잘못 설정하여 데이터를 불러오지 못했습니다. 공식 문서를 다시 확인하여 올바른 경로로 수정하여 해결했습니다.

VS Code와 GitHub 간 동기화 문제: 웹에서 직접 파일을 수정하거나 삭제한 뒤 로컬에서 작업하다가 충돌(Conflict)이 발생했습니다. git pull 명령어를 통해 원격 저장소의 최신 상태를 먼저 가져온 후 코드를 수정하여 해결했습니다.

반응형 웹 디자인(CSS Grid) 배치 문제: 화면 크기에 따라 카드 개수가 원하는 대로 정렬되지 않았습니다. 미디어 쿼리의 max-width 기준값과 그리드 템플릿 속성(grid-template-columns)을 조정하여 정상적으로 1열, 2열, 4열로 변환되도록 수정했습니다.

참고한 자료:

강의 교재 및 실습 자료

MDN Web Docs (CSS Grid, Media Queries, Fetch API)

검색 키워드: css grid responsive columns, tmdb api now playing javascript, github conflict pull fix

생성형 AI 사용 내역:

API 호출 과정에서 발생한 에러 메시지의 의미를 파악하고 해결 방법을 질문함.

CSS 그리드 및 미디어 쿼리 구조 작성 중 문법 오류나 레이아웃 정렬 방식을 검토(Review) 요청함.

README.md 파일의 양식과 필수 작성 항목을 확인하기 위해 도움을 받음.
