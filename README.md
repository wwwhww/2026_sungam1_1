# 2026 성암초 1학년 홈페이지 (GitHub Pages)

파일을 **모두 저장소 최상위(루트)**에 업로드하세요. `Settings > Pages > Deploy from a branch > main > /(root)`.

- `index.html`: 홈
- `books.html`: 전래동화 20편 (핑크퐁 공식 유튜브 모음 영상의 구간 링크)
- `quiz.html`: 퀴즈·글쓰기
- `gallery.html`: 작품방
- `teacher.html`: 교사용 자료 편집 (접속 제한 없는 페이지: 편집 결과는 브라우저 임시 저장 및 JSON 다운로드)
- `site-data.json`: 도서 목록·퀴즈·전시작품 공동 데이터
- `game1.html`, `game2.html`: 이전에 만든 게임

## 교사가 퀴즈와 작품을 모든 학생에게 보여 주는 방법
1. `teacher.html` 접속 → 문제 또는 작품 추가.
2. 아래쪽 **배포용 site-data.json 다운로드** 클릭.
3. GitHub의 기존 `site-data.json` 파일 내용에 다운로드한 JSON 전체를 덮어쓰기하고 Commit changes. (같은 이름 업로드에서 충돌하면 해당 파일의 연필 아이콘으로 직접 내용 교체)
4. Pages 배포 완료 후 학생들은 새로고침하면 반영됩니다.

중요: GitHub Pages는 **정적 호스팅**입니다. `teacher.html`은 실제 인증 관리자 페이지가 아니며, 여기서 추가한 내용은 GitHub 저장소에 저장되기 전에는 다른 기기에 표시되지 않습니다. 학생 독후활동/퀴즈 답안/칭찬은 자동으로 서버에 수집되지 않습니다. 저장 파일을 제출받아야 합니다. 학생 개인 정보, 실명과 얼굴 사진 등 공개 게시를 피하세요.

## 전래동화 출처
Pinkfong 공식 유튜브 모음 https://www.youtube.com/watch?v=zKdqQVtQxuo (2024.09.15) 중 한국 전래동화 20구간을 선택했습니다. 한 동영상 내 시작·끝 시간 구간으로 재생되며 다음 이야기와 연결되거나 임베드 제한이 있을 수 있습니다. 이때 '유튜브에서 크게 보기' 사용.
