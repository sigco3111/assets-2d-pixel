# pixelfx (팩)

- 출처: https://github.com/patch-gg/pixelfx
- 원본 커밋: 5294518ce7c72e48b6100a744596e0acf57f2826 (pixelfx/SOURCE-COMMIT.txt)
- 라이선스: MIT (원본 LICENSE 전문은 LICENSE-SOURCE.txt)
- 제작자: Patch (https://patch.gg), 원본 README 기준 "Made by Patch"
- 추가일: 2026-11-20
- 이펙트: 244종, 21개 카테고리
- 태그: 픽셀아트, VFX, 이펙트, 스프라이트시트, canvas, 브라우저 게임, 2D
- AI 생성 여부: 원본 README에는 효과가 AI로 생성되었다는 명시가 없음. 새 이펙트를 만드는 Claude Code 스킬(skills/pixelfx)이 함께 들어 있음.
- 미리보기: ../previews/pixelfx.png (montage 스틸)

## 표기 요구

MIT 조건에 따라 저작권 고지와 라이선스 문구를 사본과 함께 유지한다. 크레딧은 CREDITS.txt 참고.

## 서드파티 조건 (NOTICE.md 그대로)

- Hugo Duprez: src/core/sim.js 및 파일 상단에 그렇다고 적힌 효과는 Sprite Fusion의 오픈소스 pixel art VFX (https://www.spritefusion.com/pixel-art-vfx)를 각색한 것. Copyright (c) 2026 Hugo Duprez, MIT License.
- Hollow Crown: src/core/act.js는 https://github.com/rehan-remade/hollow-crown 의 스킬 재생 방식을 각색한 것. Copyright (c) 2026 rehan-remade, MIT License.
- Patch Pixel 폰트: gallery/fonts의 폰트는 Patch의 고유 서체로 이 저장소의 MIT 라이선스 대상이 아님. © 2026 Patch. All rights reserved. (gallery/fonts/NOTICE.md 그대로)

## 사용법 요약

- 브라우저 게임 (canvas, Phaser, PixiJS 등): npm i github:patch-gg/pixelfx 로 설치하거나 src/core 와 필요한 src/fx/<카테고리>/<이름>.js 를 복사. 의존성 없음.
- 다른 엔진 (Godot, Unity, GameMaker, Defold, LÖVE, Bevy): node tools/render.mjs <카테고리/이름> --sheet 로 PNG 스프라이트 시트와 JSON 생성. node tools/sheets.mjs 로 전체 내보내기.
- 팔레트 변경: 옵션 palette (어두운색→밝은색 hex 배열)로 코드 수정 없이 색 변경.
- 캐릭터 동작 포함: createAct 로 와인드업, 타격 정지, 반동을 함께 재생. createFx 는 이펙트만.
- 직접 만들기: node tools/new.mjs <카테고리/이름>, render.mjs 로 확인, check.mjs 로 점검. 자세한 규칙은 docs/AUTHORING.md.

## 다운로드 압축본 (2026-11-23)

- `pixelfx.zip`: 기존 수집 커밋 5294518의 코드·문서·도구·갤러리 묶음. 244개 효과 모듈, MIT 전문과 서드파티 고지 포함.
- ZIP의 `gallery/fonts/PatchPixel-Regular.woff2`는 제외했습니다. 해당 폰트는 MIT 대상이 아니며 권리 유보가 명시되어 있습니다. 갤러리는 시스템 대체 폰트로 표시됩니다.
- 원본의 에이전트용 플러그인·스킬 설정과 GitHub 자동화는 ZIP에서 제외했습니다. 이펙트 사용·렌더에는 필요하지 않습니다.
- 기존 미리보기: `../previews/pixelfx.png`.
