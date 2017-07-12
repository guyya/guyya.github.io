---
layout: post
title: Brainstorming (PartyFD)
categories: project
tags: [rpg, game, 2d, project]
description: 모바일 환경에 맞는 최소환 컨트롤을 지향하는 게임에 대한 아이디어
---

역할군
탱커..진형 리딩. 어그로 관리. 탱킹
딜러...원거리 근거리 딜링. 암살. 디버프
서폿...타 챔프 도움. 힐링. 텔포. 버프

진형
탱커중심으로 상대적인 고정 위치
약간의 이동은 가능
아군이 이동 가능한 영역과 몹이 이동하는 영역은 별개

AI
모든 챔프는 인공지능 동작.(평타 공격, 회피)
컨트롤시에는 정지

이동
챔프이동은 노코스트. 이속은 각각 다름
- 진형이동:터치시 전체 이동. 이동은 각자
- 진형각이동:두번째 챔프가 이동유발시(이벤트+주기)
- 회피이동:진형유지하면서 회피용 무빙

패시브 스킬
on/off 함. 토글 방식으로 활성화..x
코스트 소모..x
특정 조건에 발동 혹은 주기적으로 발동등 다양함..x
버프형식아님. 주기적으로 발동하거나 이벤트시 발동..x
주로 버프나 오라 위주임×
시작과 끝이 있는 버프류로 통일

액티브스킬
즉시시전. 타켓팅. 논타켓팅
직접 시전해야 하고 쿨생김
(참고로 코스트 생성 스킬도 존재함)..x

밸런스
파티가 던전에 특성에 맞게 잘 밸런싱되어야

코스트.삭제
스킬에는 쿨은 존재하지만 액션타임임
스킬은 기본적으로 코스트를 소모하며
패시브가 많으면 코스트/주기 값만큼 코스트젠을 감소함
코스트젠은 최소/최대값존재. 0.2초마다 x만큼 재생됨

몬스터
인공지능 패턴으로 파티를 공격하면
패이징이 있을 수도
이동. 스폰. 토템공격

카드
확률에 근거하여 나옴.
챔프의 능력치를 향상하는 버프류 혹은 텔포. 힐.
버프 시간과 무관하게 일정시간마다 나오지만 카드가 있으면 발생안함
사용하거나 취소하면 일정 시간 후 발생. 발생후 즉시 사용가능

글로벌스킬
챔프가 사용한 스킬마다 게이지를 쌓고 활성화
던전입장전 선택한다
주로 전체 힐. 딜 등임..
플레이스탈에 영향을 주면 좋겠는데..??

보상
던전클리어, 주기적인 접속등에 발생
던전템, 경험치, 스킬경험치, 골드, 스킬템,
던전에 대한 랜덤옵션을 주어 더 좋은 보상이 뜰 수..
게임도중 템드롭되고 자동 습득됨..득템의 희열 강조

상점
스킬젬. 던전템. 골드. 루비. 캐릭터 판매

스탯
마스터레벨이 존재하여 랩업시 스탯포인트를 주고 어떤 케릭이든 찍을 수 있다.
스탯트리는 모근 챔프에게 공통이지만 고유값에 의해 효율은 다를 수 있다
챔프별 고정값 × 스탯 트리에서의 증가율

장비
아직 미정.
나온다면 스탯에 영향을 주고 찰 수 있는 캐릭이 한정됨

카메라
보스와 탱커간 거리에 따라 줌이 다르다

게임종료 조건
1. 탱커사망
2. 제한시간

BM
유료로 출시
컨텐츠업
부분유료화 + 구매 유저에게 보상 상품 및 리셋
나중에 pvp용은 따로 개발하여 부분류료화.

데미지 분류
- 물리/불/얼음/전기/독
- 아머/저항

2차효과
- 출혈/버닝/느림/기절/독

군중제어
- 스턴/느림/공속저하/절단/

스킬 사거리
- 탱커의 사거리가 더해지는 방식..
- 탱커에 따라 타챈프의 스킬사거리 조정