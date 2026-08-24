# v4 업로드 방법 — 이것만 따라하세요

v3를 따로 올릴 필요 없습니다. **v4를 현재 GitHub 저장소 위에 바로 업로드하면 됩니다.**

1. `yakson-suwon-site-v4.zip` 압축을 풉니다.
2. 압축을 푼 `yakson-suwon-site-v4` 폴더 안으로 들어갑니다.
3. 안의 파일과 폴더를 `Ctrl + A`로 모두 선택합니다.
4. GitHub의 `yaksonclinic/yakson-suwon-site` 저장소에서 `Add file` → `Upload files`를 누릅니다.
5. 선택한 내용 전체를 업로드 영역에 넣습니다.
6. 아래 `Commit changes`를 누릅니다.
7. 몇 분 뒤 `https://yaksonclinic.github.io/yakson-suwon-site/`에서 확인합니다.

## v4에 포함된 핵심 변경

- 2017년부터 수원 우만동 진료 시작 반영
- 평일 09:00–19:00, 접수마감 18:30 반영
- 평일 점심 13:00–14:00 반영
- 토요일 09:00–14:00, 점심시간 없음 반영
- 일요일·공휴일 휴진 반영
- 네이버 블로그·네이버 클립·인스타그램 공식 채널 연결
- 플레이스 소개 내용을 바탕으로 진료 영역 정리
- 첫 정식 아카이브 칼럼: `두근거림과 소화불량, 왜 같이 나타날까요?`
- FAQ의 현재 수정본을 보존하고 빈 `-` 오류 제거
- AI/검색용 사실 페이지, `llms.txt`, 구조화데이터에 2017년·진료시간·공식 채널 정보 통합

## 업로드 뒤 확인할 것

GitHub 저장소에 아래 파일이 보이면 v4가 올라간 것입니다.

- `UPLOAD-V4.md`
- `_data/clinic.yml`
- `_data/faq.yml`
- `_posts/2026-08-19-palpitations-dyspepsia-autonomic-nervous-system.md`

홈페이지에서는 한의원 소개에 `2017년부터`, 진료시간에 `접수마감 18:30`, FAQ에 `일요일과 공휴일은 휴진`이 보이는지 확인하세요.
