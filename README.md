# 더플릭 ABOUT 페이지 시안

theflick.io의 About 페이지를 스크롤 인터랙션으로 다시 만든 시안입니다.

## 파일
- `flick-about.html` — Claude 아티팩트로 게시되는 페이지 원본 그대로입니다.
  - 3D 로고(THEFLICK_block_smooth.glb)와 질감 이미지가 파일 안에 들어 있어서 파일 하나로 동작합니다.
  - 3D 엔진(three.js 0.149.0)은 jsDelivr CDN에서 불러옵니다.

## 참고
- 편집 모드에서 저장한 위치·크기·굵기 값은 아티팩트의 데이터 저장소(`edits/current`)에 따로 저장됩니다. 이 파일에는 들어 있지 않습니다.
- 아티팩트 밖에서 이 파일을 열면 편집 값은 그 브라우저(localStorage)에만 저장됩니다.
- 아티팩트에 맞춰 만든 파일이라 `<!doctype html>`과 `<head>` 태그가 없습니다. 아티팩트가 게시할 때 자동으로 붙여 줍니다.
