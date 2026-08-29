# X Image Splitter

X(트위터)에 여러 장을 가로로 연속 업로드했을 때 한 장처럼 이어져 보이도록
이미지를 3장 또는 4장으로 균등 분할하는 정적 웹 도구입니다.

## 기능

- 3분할 / 4분할
- 모든 조각 동일 픽셀 크기
- X 업로드 순서 미리보기
- PNG / JPG / WEBP 출력
- 개별 다운로드
- ZIP 전체 다운로드
- 이미지 서버 업로드 없음 (브라우저에서만 처리)

## GitHub Pages 배포

1. 새 GitHub 저장소를 만듭니다.
2. `index.html`을 저장소 최상단에 업로드합니다.
3. GitHub 저장소의 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch를 `main`, 폴더를 `/(root)`로 지정하고 저장합니다.
6. 잠시 후 발급된 GitHub Pages 주소로 접속하면 됩니다.

## 참고

ZIP 다운로드에 JSZip CDN을 사용하므로 ZIP 기능에는 인터넷 연결이 필요합니다.
이미지 분할 및 개별 다운로드 자체는 브라우저에서 처리됩니다.
