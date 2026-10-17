# 새야 · 서민규 포트폴리오

게임 시나리오 라이터·웹소설 작가의 공개 포트폴리오입니다. 정적 단일 HTML로 구성되어 있으며 `index.html`이 배포 시작 파일입니다.

## Netlify에서 배포

1. GitHub에 이 저장소를 생성하고 `index.html`, `netlify.toml`을 저장소의 루트에 업로드합니다.
2. [Netlify](https://app.netlify.com/)에 로그인한 뒤 **Add new project → Import an existing project**를 선택합니다.
3. **GitHub**를 선택하고 저장소 접근을 승인한 다음, 해당 저장소를 선택합니다.
4. Build command는 공란, Publish directory는 `.` (저장소 루트)로 지정합니다.
5. Deploy 후 발급된 `*.netlify.app` 주소를 공유합니다.

저장소의 `main` 브랜치에 변경사항이 푸시되면 Netlify가 자동으로 새 버전을 배포합니다.

## 편집 시 주의

- 이 저장소에는 **공개용 HTML만** 포함하세요. 편집용 파일·JSON 백업·민감한 개인정보는 업로드하지 마세요.
- 자기소개서와 작품 정보를 수정한 후 새 공개용 `index.html`을 커밋해야 Netlify에 반영됩니다.
- 공개 HTML은 검색 엔진 인덱싱을 줄이도록 `noindex`를 지정했지만, URL을 아는 방문자는 사이트에 접근할 수 있습니다.
- 작품 이미지 중 일부는 외부 공식 이미지 서버 링크를 사용하므로 접근 제한으로 이미지가 나타나지 않을 수 있습니다.