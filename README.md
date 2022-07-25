# **Unity 프로젝트 기획서**

# **게임 개요**

- 것츠 앤 글로리를 모작했습니다

[아빠와 아들의 신이나는(?) 자전거 여행 게임 (Guts and Glory)](https://youtu.be/e2gNuSc_nXI)

[유저들이 만든 난이도 lv999 미친 맵들](https://youtu.be/0_dHXMd-ILg)

## 장르

- 병맛 길찾기 게임

## 요소

- 플레이어
    - 근육맨 아저씨
- 탈 것
    - 자동차(난이도 🔼)
    - 자전거(난이도 🔽)
- 지형
    - 완만한 지형(난이도 🔼)
    - 협곡(난이도 🔽)
- 방해물
    - 몬스터(난이도 🔼) : 경찰차
    - 길막(난이도 🔽) : 제자리에서 신명나는 춤을 똑같이 추며 길을 막는 사람들

## 조작법

- w : 앞으로 간다
- s : 뒤로 간다
- a : 바퀴 왼쪽으로 회전
- d : 바퀴 오른쪽으로 회전
- ← : 왼쪽으로 힘 (난이도  🔽)
- → : 오른쪽으로 힘 (난이도 🔽)

## 시스템

- 정해진 목적지를 향해 간다.
    - 목적지는 바닥에 🟡로 표현 (여러개 있음)
    - 도착하면 🟢 변함 (세이브포인트)
    - 최종 목적지 🔴 → 도착하면 게임 끝
- 플레이어가 바닥에 닿으면 게임오버
    - r키를 눌러서 세이브포인트로 돌아간다.

### 난이도 🔼

- 플레이어 : wasd
- 탈 것 : 자동차
    - 통통튄다
- 지형 : 완만한 지형
- 몬스터 : 경찰차 → 공격요소
    - 플레이어를 따라가며 3초마다 플레이어를 향해 폭탄을 던진다
        - 폭탄은 2초뒤 펑
            - 펑 하면 그 일대에 힘을 가한다(탈것이 뒤집어짐)
    - 5초에 한번 복제된다

### 난이도  🔽

- 플레이어 : wasd + 좌우 방향키로 균형
- 탈 것 : 자전거
    - 조작이 빡셈
- 지형 : 협곡
- 방해물 : 사람, 조형물 → 길막요소
    - 사람
        - 제자리에서 신명나는 춤을 똑같이 춘다.
        - 탈 것에 치이면 렉돌
    - 조형물
        - 이상한곳에 이상하게 길막한다.

## **~~개발 환경~~**

~~프로젝트가 완료된 후 개발 환경을 작성합니다. 기간 / 인원 / 사용한 툴 / 외부 패키지, 라이브러리 등을 작성합니다.~~

## **~~링크~~**

~~프로젝트가 완료된 후 `<a>` 태그의 `href` 속성에 관련된 링크를 작성합니다.~~
