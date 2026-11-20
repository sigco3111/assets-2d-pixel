# 물결 소탕 스프라이트 26 (everyday-game)

웹 게임 「물결 소탕」(세로 화면 소탕 슈팅, https://sigco3111.github.io/everyday-game/tide/)에 쓰이는 2D 스프라이트 모음입니다. 게임 안에서는 항상 카메라를 향하는 2D 이미지(빌보드)로 표시됩니다.

**라이선스: 알 수 없음.** 원작·한글판 포크 저장소 어디에도 LICENSE 파일이 없고(2026-11-20 확인) 원작자의 재사용 허락은 확인되지 않았습니다. 사용 전 원작자(zhgarylu)에게 확인하세요. 자세한 출처 기록은 LICENSE-SOURCE.txt를 봅니다. 권리자가 삭제를 요청하면 즉시 내립니다.

## 내용 (투명 RGBA PNG 26장 + 제작 규격 문서 2종)

- **아군 거수 5** (512×512, 배면): `ally_drake`(화염날개 비룡), `ally_turtle`(천둥북 거북), `ally_archer`(별활 거령), `ally_whale`(얼음물결 고래), `ally_sentinel`(수정방패 수위). whale·sentinel은 원작 게임에 아직 접속되지 않은 제안 분(ALLY_IDEAS.md).
- **유닛 8**: `soldier`(소대 대원, 배면, 256²), `small`(작은 괴물), `runner`(빠른 괴물), `brute`(큰 괴물, 512²), `boss`(우두머리, 512²), `golem`(수정 거상, 아군, 512²), `bomber`(폭발 괴물), `user_monster`(초대형 몬스터 슬롯, 실제 인물 얼굴이 합성된 듯한 이미지. 초상권 주의).
- **무기 10** (256²): `weapon_crossbow`·`repeater`·`scatter`·`blade`·`cannon`·`lance`·`missile`·`chain`·`flame`·`prism`. 약한 것부터 강한 순, 탄환 색과 주색이 일치.
- **강화 3** (256²): `reward_rate`(연사), `reward_power`(피해), `reward_nova`(전멸 충격).
- **문서**: `ASSET_SPEC.md`(중문 제작 규격: 캔버스 크기·시점·명명 규칙·프레임 요구), `ALLY_IDEAS.md`(미접속 거수 제안).

모두 정지 이미지 1장씩이며 다중 프레임 애니메이션은 없습니다(게임이 프로그램으로 흔들림을 줍니다). 원작 README에 따르면 캐릭터 이미지는 별도로 AI 생성 후 접속된 그림입니다.

- 출처: https://github.com/zhgarylu/everyday-game (원작) · 한글판 포크: https://github.com/sigco3111/everyday-game
- 제작자: zhgarylu (원작 저장소)
- 수집일: 2026-11-20 (소유자 지시로 '알 수 없음' 표기 후 공개 수집)
- 파일: everyday-game-tide-sprites.zip
