# mjc05-landing

(주)엠제이씨기업 랜딩페이지 **배포 전용** 저장소입니다. www.mjc05.com 을 서빙합니다.

- `index.html` — 빌드 산출물. 이미지가 base64 로 내장된 단일 파일이라 외부 요청이 없습니다.
- `CNAME` — GitHub Pages 사용자 지정 도메인.

**여기서 직접 수정하지 마세요.** 원본은 `엠제이씨-랜딩페이지/Main.dc.html` 이고,
`python3 build-static.py` 로 `mjc-landing-preview.html` 을 다시 뽑아 이 저장소의
`index.html` 로 덮어쓰는 것이 정규 경로입니다.
