# Dead Precinct 프리렌더 배경 10장 (320×240)

PS1 스타일 서바이벌 호러 「DEAD PRECINCT」의 고정 카메라 배경 10장입니다. 원작자가 Blender Cycles로 오프라인 렌더링한 뒤 색보정한 320×240 PNG로, 실시간 3D 캐릭터를 깊이에 맞게 합성하는 고정 카메라 방식(1990년대 서바이벌 호러식)에 쓰였습니다.

**라이선스: MIT** (Copyright (c) 2026 Bao5ye). 재배포 시 저작권 표기와 MIT 전문 유지가 조건입니다. 원작 README는 모든 배경·캐릭터·음악을 자작이라고 명시합니다. 다만 원작이 1998년작 서바이벌 호러에 대한 비상업 팬 오마주라고 스스로 밝히고 있으므로, 분위기가 유사한 상업 프로젝트에 그대로 쓸 때는 별도 검토를 권합니다.

## 내용 (320×240 PNG 10장)

- `street-a`, `street-b`: 중앙대로 (경찰차 2대, 벽돌 건물, 야간)
- `hall-a`, `hall-b`: 경찰서 대홀 (세이프룸, 체크무늬 바닥, 기둥)
- `office`: 서쪽 사무실 (녹조 형광등, 책상)
- `corridor-a`, `corridor-b`: 동쪽 복도 (청조 야간 조명)
- `armory`: 무기고 (콘크리트, 금고·선반)
- `garage-a`, `garage-b`: 지하 주차장 (적색 비상등, 보스전 무대)

- 출처: https://github.com/Bao5ye/dead-precinct (원작 commit 3292dc6) · 한글판: https://github.com/sigco3111/dead-precinct-ko
- 수집일: 2026-11-24 · 단일 index.html에 base64로 내장된 BG 오브젝트에서 추출
- 파일: dead-precinct-backgrounds.zip
- 활용: 고정 카메라 배경으로 쓰거나, 같은 렌더러로 실시간 캐릭터를 깊이 합성(assets-code `dead-precinct-ps1-renderer`의 md 모드와 같은 방식)
