# Under Hall — 정창우 작성 코드

> 쿼터뷰 로그라이크 액션 · 팀 4인 · 2026.05  
> Unity 6 · C# · VFX · Cinemachine  
> 내 커밋 기간: 2026-05-06 – 2026-05-28

Unity 프로젝트 전체가 아니라, **정창우(jcw3421)가 실제로 커밋해서 만들거나 수정한 코드 파일만** 모아 둔 레포입니다.
아트 · 사운드 · 씬 · 프리팹 · 에셋스토어 패키지 · 서드파티 코드는 모두 빠져 있어서 이 레포만으로는 빌드되지 않습니다.

## 추출 기준

- 원본: 디벨로켓 부트캠프 조직(`Devel-Rocket-ClassRoom`)의 프로젝트 레포 — 모든 브랜치의 커밋을 조사
- 커밋 작성자가 `jcw3421 <gatecrow@naver.com>` 또는 `정창우 <jcw3421@gmail.com>` 인 커밋에서 추가 · 수정된 코드 파일 (`.cs` `.shader` `.hlsl` 등)
- 직접 만든 파일은 전부 포함, 남이 만든 파일은 현재 버전에 내가 쓴 줄이 5줄 이상 남아 있을 때만 포함
- 파일 내용은 기본 브랜치의 최신 버전 (기본 브랜치에 없으면 해당 파일이 있는 가장 최근 커밋)
- `내 줄 / 전체` 는 `git blame -w` 기준으로 지금 남아 있는 줄 중 내가 쓴 줄 수. 팀 프로젝트라 수정한 파일에는 팀원이 쓴 코드도 함께 들어 있습니다.

## 요약

| 내 커밋 | 포함 파일 | 직접 만든 파일 | 수정한 파일 | 남아 있는 내 코드 줄 |
|---|---|---|---|---|
| 73 | 22 | 13 | 9 | 2,710 |

## 직접 만든 파일

| 파일 | 내 줄 / 전체 | 비율 |
|---|---|---|
| [`Assets/_Project/Scripts/Graphics/Camera/CameraConfinerAutoBinder.cs`](Assets/_Project/Scripts/Graphics/Camera/CameraConfinerAutoBinder.cs) | 31 / 31 | 100% |
| [`Assets/_Project/Scripts/Graphics/Camera/CameraManager.cs`](Assets/_Project/Scripts/Graphics/Camera/CameraManager.cs) | 292 / 296 | 99% |
| [`Assets/_Project/Scripts/Graphics/Camera/CinemachineTargetBinder.cs`](Assets/_Project/Scripts/Graphics/Camera/CinemachineTargetBinder.cs) | 39 / 39 | 100% |
| [`Assets/_Project/Scripts/Graphics/Camera/HadesCameraTarget.cs`](Assets/_Project/Scripts/Graphics/Camera/HadesCameraTarget.cs) | 103 / 103 | 100% |
| [`Assets/_Project/Scripts/Graphics/HIT/DamageNumber.cs`](Assets/_Project/Scripts/Graphics/HIT/DamageNumber.cs) | 61 / 61 | 100% |
| [`Assets/_Project/Scripts/Graphics/HIT/DamageNumberSpawner.cs`](Assets/_Project/Scripts/Graphics/HIT/DamageNumberSpawner.cs) | 112 / 112 | 100% |
| [`Assets/_Project/Scripts/Graphics/HIT/DoubleDoorController.cs`](Assets/_Project/Scripts/Graphics/HIT/DoubleDoorController.cs) | 154 / 154 | 100% |
| [`Assets/_Project/Scripts/Graphics/HIT/HadesHitEffect.cs`](Assets/_Project/Scripts/Graphics/HIT/HadesHitEffect.cs) | 83 / 83 | 100% |
| [`Assets/_Project/Scripts/Graphics/HIT/HadesHitVFX.cs`](Assets/_Project/Scripts/Graphics/HIT/HadesHitVFX.cs) | 28 / 28 | 100% |
| [`Assets/_Project/Scripts/Graphics/HIT/HardwareSoftCursor.cs`](Assets/_Project/Scripts/Graphics/HIT/HardwareSoftCursor.cs) | 162 / 162 | 100% |
| [`Assets/_Project/Scripts/Graphics/HIT/VFXManager.cs`](Assets/_Project/Scripts/Graphics/HIT/VFXManager.cs) | 398 / 404 | 99% |
| [`Assets/_Project/Scripts/Graphics/editor/MaterialShaderSwapper.cs`](Assets/_Project/Scripts/Graphics/editor/MaterialShaderSwapper.cs) | 350 / 350 | 100% |
| [`Assets/_Project/Scripts/Graphics/editor/VFXMasterTool.cs`](Assets/_Project/Scripts/Graphics/editor/VFXMasterTool.cs) | 463 / 463 | 100% |

## 수정에 참여한 파일

| 파일 | 내 줄 / 전체 | 비율 |
|---|---|---|
| [`Assets/_Project/Scripts/Enemy/BasicBoss.cs`](Assets/_Project/Scripts/Enemy/BasicBoss.cs) | 131 / 689 | 19% |
| [`Assets/_Project/Scripts/Manager/UIManager.cs`](Assets/_Project/Scripts/Manager/UIManager.cs) | 77 / 142 | 54% |
| [`Assets/_Project/Scripts/Player/PlayerAttack.cs`](Assets/_Project/Scripts/Player/PlayerAttack.cs) | 54 / 360 | 15% |
| [`Assets/_Project/Scripts/Manager/GameManager.cs`](Assets/_Project/Scripts/Manager/GameManager.cs) | 47 / 281 | 17% |
| [`Assets/_Project/Scripts/Manager/SpawnManager.cs`](Assets/_Project/Scripts/Manager/SpawnManager.cs) | 46 / 333 | 14% |
| [`Assets/_Project/Scripts/Player/Player.cs`](Assets/_Project/Scripts/Player/Player.cs) | 42 / 377 | 11% |
| [`Assets/_Project/Scripts/Enemy/BossDragon.cs`](Assets/_Project/Scripts/Enemy/BossDragon.cs) | 22 / 634 | 3% |
| [`Assets/_Project/Scripts/Manager/Door.cs`](Assets/_Project/Scripts/Manager/Door.cs) | 10 / 83 | 12% |
| [`Assets/_Project/Scripts/Enemy/EnemyBase.cs`](Assets/_Project/Scripts/Enemy/EnemyBase.cs) | 5 / 217 | 2% |

## 내 커밋 기록

<details><summary>커밋 73개 펼치기</summary>

| 날짜 | 커밋 | 메시지 |
|---|---|---|
| 2026-05-28 | `638406a` | feat:카메라 그래픽 ppt |
| 2026-05-28 | `11b3e77` | feat: 그래픽 ppt |
| 2026-05-26 | `637f191` | feat:보스 2페이즈 연출 |
| 2026-05-26 | `1e089a7` | feat:fog 셰이더 그래프 |
| 2026-05-26 | `d3f12f1` | fix: 포털이펙트 수정 |
| 2026-05-26 | `9bca13c` | feat:Portal 이펙트 및 title 이미지 |
| 2026-05-25 | `7c0eea8` | feat:BeforeBossRoom Portal |
| 2026-05-22 | `5ed28a7` | feat:보스룸 셰이더 |
| 2026-05-22 | `e77b714` | fix:드래곤 플라잉어택중 사망시 부활 카메라 줌인과 타임스케일 픽스 |
| 2026-05-22 | `a851670` | feat:Map 카메라콜라이더 조정 |
| 2026-05-21 | `b25d859` | feat: 대시 및 특수 공격 쿨타임 UI 구현 및 연동 |
| 2026-05-21 | `36799a0` | feat:드래곤 플라잉 이펙트 추가,슬로우모션중 퍼즈 프로퍼티 추가 |
| 2026-05-21 | `104b5bd` | feat:플레이어 피격시 카메라플래시 추가 |
| 2026-05-21 | `9065b0a` | feat:보스드래곤 돌진이펙트 |
| 2026-05-20 | `00ea788` | feat:마우스포인트 추가 |
| 2026-05-20 | `7f7f771` | feat:마우스커서에셋및 포인트 추가, |
| 2026-05-20 | `2dc73e4` | feat:플레이어 interpolate 추가 |
| 2026-05-20 | `241d7a2` | feat:카메라 값 조절 |
| 2026-05-20 | `1f59c6e` | feat: 첫 번째 맵 진입 시 카메라 바운드 콜라이더 자동 주입 기능 추가 |
| 2026-05-20 | `84688d8` | fix:타이틀 씬에서 인게임 진입 시 카메라 및 타겟 레퍼런스 유실 버그 수정 |
| 2026-05-20 | `f0d92b9` | feat:마우스 반응형 카메라 타겟 및 맵 전환 시 Confiner 자동 바인딩 기능 구현 |
| 2026-05-19 | `d12b53b` | feat:크리티컬데미지폰트 파라미터 추가 |
| 2026-05-19 | `bd1af1f` | feat:데미지폰트 크기조절,디렉셔널라이팅 각도조절,도어 이펙트 크기조절 |
| 2026-05-19 | `19f537e` | feat:데미지넘버스포너 추가 |
| 2026-05-19 | `37667e9` | feat:타격 카메라흔들림추가,도어 프리팹 이펙트크기 조절 |
| 2026-05-18 | `2831d18` | feat:디졸브 셰이더 그래프 |
| 2026-05-18 | `090c074` | feat:도어 프리팹 파티클 이펙트 수정,vfx매니저 몬스터 다이 제거 |
| 2026-05-18 | `63f5eeb` | feat:도어 콜라이더 추가 |
| 2026-05-18 | `17106c4` | feat: 클리어시 door 열림 추가 |
| 2026-05-18 | `fd81934` | feat:두트윈 에셋 추가(개발툴) |
| 2026-05-18 | `c203f0e` | feat: Lit_Dungeon_Torch추가,소환이펙트 수정 |
| 2026-05-18 | `a719e04` | feat:원거리몬스터 투사체 이펙트 추가 |
| 2026-05-17 | `f04d911` | feat:소환 이펙트 추가 |
| 2026-05-16 | `6248c3d` | feat:셰이더 조정 |
| 2026-05-15 | `6097a9b` | feat: vfx매니저 보상아이템 이펙트 추가 |
| 2026-05-15 | `c839801` | feat:보상아이템 이펙트 추가 |
| 2026-05-15 | `c1b63a9` | feat:조명 프리팹 베리언트화 |
| 2026-05-15 | `c12ab2f` | feat:맵 조명추가 및 플레이어 이펙트 위치수정 |
| 2026-05-14 | `d4dea74` | fix:몬스터 블러드 버그픽스,브레스 회전초기화 값 삭제 |
| 2026-05-14 | `9fb5733` | feat: vfx매니저 프리팹 브레스 이펙트 추가 |
| 2026-05-14 | `1190ec9` | feat: bossDragon 브레스 이펙트 위치추가 |
| 2026-05-13 | `75af543` | feat:JCW_Test 씬 업데이트 |
| 2026-05-13 | `a234d49` | fix:VFX매니저 플레이어 StartCoroutine 삭제 |
| 2026-05-13 | `b746597` | feat:VFX매니저 보스몬스터 추가 |
| 2026-05-12 | `8168c85` | feat:TEST_JCW씬 업데이트 |
| 2026-05-12 | `06c1677` | fix:부활이펙트 위치 수정 |
| 2026-05-12 | `8622347` | fix: vfxManager PlayWeaponSkillLoop 변경 |
| 2026-05-12 | `24b7664` | fix:vfx매니저 PlayWeaponSkillLoop 수정 |
| 2026-05-12 | `da854ac` | feat:메테리얼 셰이더 툴 추가 |
| 2026-05-11 | `effca7b` | feat:이펙트 프리팹 베리언트 구조 설계 및 폴더 정리 |
| 2026-05-11 | `f989e0e` | fix:우클릭 스킬 이펙트 잔상 제거 |
| 2026-05-11 | `9c0ba44` | feat:VFX Manager 프리팹 추가 |
| 2026-05-11 | `1d86a2d` | chore:이펙트 에셋 추가 |
| 2026-05-11 | `89b8f5d` | feat:우클릭(스킬)잔상 제거 추가 |
| 2026-05-11 | `ee3920f` | feat:Player.cs vfx매니저의 부활 호출 함수 추가 |
| 2026-05-11 | `b6ec8b8` | fix:vfx매니저 DontDestroyOnLoad 추가 |
| 2026-05-11 | `f1e879d` | fix:VFX 툴 간단한 오타 수정 |
| 2026-05-10 | `a3ae339` | feat:VFX 에디터 툴 추가 |
| 2026-05-09 | `41e069d` | feat:VFX매니저 호출함수 추가 |
| 2026-05-09 | `16f3436` | feat:VFXManager 추가 |
| 2026-05-08 | `88de9c2` | feat:VFXManager 추가 |
| 2026-05-08 | `5ee23cc` | chore:VFX 에셋 추가 |
| 2026-05-08 | `ba791b9` | feat:히트이펙트 스크립트 추가 |
| 2026-05-08 | `3f69a2a` | feat:hit 파티클 프리팹 추가 |
| 2026-05-07 | `b10913e` | chore:셰이더 머테리얼 |
| 2026-05-07 | `a2c3763` | fix:카메라 각도 수정 |
| 2026-05-07 | `fed67a4` | chore:셰이더 추가 |
| 2026-05-07 | `8981570` | fix:씨네머신카메라 중복스크립트 삭제 |
| 2026-05-07 | `1bbc988` | fix:쿼터뷰카메라 수정 |
| 2026-05-07 | `c57be63` | feat:카메라매니저 추가 |
| 2026-05-07 | `1984c1d` | feat:쿼터뷰 카메라 |
| 2026-05-06 | `8ee9fcf` | feat:씨네머신 카메라 추가 |
| 2026-05-06 | `4a0fcc3` | feat:정창우test |

</details>
