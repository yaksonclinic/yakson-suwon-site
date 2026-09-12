# 건강관리 영상 메뉴 — 업로드 안내

이 파일 묶음은 현재 GitHub 홈페이지에 추가할 수정본입니다. 아직 실제 홈페이지에 반영되지 않았습니다.
원본 기준: yaksonclinic/yakson-suwon-site, commit 78047b6.

## 추가되는 내용

- 상단 메뉴: 한의사가 알려주는 건강관리
- 최신순 영상 게시물 목록
- 첫 게시물: 심장 두근거림, 소화불량, 불면증 의외로 공통점은?
- 사용자 제공 본문과 NAVER Clip iframe
- 주요 증상·관련 주제, 작성자·게시일, 관련 건강칼럼 링크
- 개별 주소, 기존 사이트맵 자동 포함, 기존 보조 색인 연결
- 화면 폭에 맞춰 줄어드는 세로형 플레이어

## 기존 GitHub 홈페이지에 적용

1. 이 ZIP 파일을 컴퓨터에서 압축 해제합니다.
2. https://github.com/yaksonclinic/yakson-suwon-site 에서 저장소의 첫 화면으로 이동합니다.
3. Add file → Upload files를 선택합니다.
4. 압축을 푼 폴더의 upload 폴더를 열고, 그 안의 파일과 폴더를 모두 선택해 업로드 영역으로 끌어다 놓습니다.
5. 업로드 목록에 _config.yml, _includes/header.html, _layouts/health-video.html, _health_videos/autonomic-symptoms.md 등의 경로가 표시되는지 확인합니다.
6. Commit changes를 누릅니다. 기존 파일은 수정본으로 교체되고 새 파일은 추가됩니다.
7. GitHub Pages 배포가 끝나면 홈페이지를 새로고침합니다.

배포 후 생성될 주소:
- 목록: https://yaksonclinic.github.io/yakson-suwon-site/health-videos/
- 첫 게시물: https://yaksonclinic.github.io/yakson-suwon-site/health-videos/autonomic-symptoms/

배포 후 확인:
- 상단의 한의사가 알려주는 건강관리 메뉴 → 목록 → 첫 글로 이동
- 영상의 재생 버튼을 눌러 재생
- 휴대폰 화면에서 메뉴와 영상 폭 확인
- sitemap.xml에 위 두 주소가 포함되는지 확인

## 이후 영상 글 추가

upload/_drafts/health-video-template.md의 내용을 복사해 저장소의 _health_videos 폴더에 새 .md 파일을 추가합니다.
제목, 요약, 게시일, 실제 작성자, 본문, iframe의 src 주소를 입력하면 목록과 사이트맵이 자동으로 갱신됩니다.
일반 건강칼럼은 기존 _posts 방식으로 계속 발행합니다.

## 확인한 범위

- 제공된 네이버 플레이어에서 33.024초 영상의 재생 완료를 확인했습니다.
- Liquid 템플릿으로 만든 두 새 페이지의 제목, 본문, 문서 구조, 내부 링크, 정확한 iframe 주소를 확인했습니다.
- 원본에 대한 변경 파일의 공백 오류 검사를 통과했습니다.
- 이 환경에는 Ruby/Jekyll 실행 환경이 없어 실제 GitHub Pages 빌드는 수행하지 못했습니다.
- Browser 보안 정책이 로컬 미리보기 접근을 차단해 새 페이지의 화면 배치와 페이지 내부 iframe 재생은 검증하지 못했습니다. 실제 업로드 후 위 항목을 확인해주세요.
- 영상 최초 게시일과 실제 썸네일 자료가 제공되지 않아 VideoObject 구조화데이터는 아직 출력하지 않습니다. 정확한 두 값을 추가하면 출력하도록 준비했습니다. 글과 iframe 자체는 별도로 정상 생성됩니다.
- 검색 색인과 AI 노출은 보장되지 않습니다.

## 포함된 변경 파일

- README.md
- _config.yml
- _drafts/health-video-template.md
- _health_videos/autonomic-symptoms.md
- _includes/header.html
- _layouts/health-video.html
- assets/css/style.css
- health-videos.html
- llms.txt
