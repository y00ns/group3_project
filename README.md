# group3_project
가상현실 term 프로젝트 수행 결과

## 프로젝트 소개
### 프로젝트 목표
LMS 장르의 게임을 제작하고 이를 VRChat 맵으로 배포하여 다양한 사람들이 제안하는 게임을 접할 수 있도록 접근성을 높임
- LMS(Last Man Standing): 플레이어들을 한 스테이지에 모아놓은 후 최후의 1명만 남을 때까지 경쟁을 시키는 게임 장르
- VRChat: 가상현실 소셜 플랫폼

### 2차 목표
- LMS 장르의 게임을 구현하며 Unity의 기능을 체험하고 응용하는 기회를 얻음
- 가상현실 플랫폼에 게임을 공유해 실제 가상현실 체험자들이 게임을 접하도록 함
- 가상현실 콘텐츠의 개발부터 배포까지의 과정을 모두 경험

### VRChat을 선택한 이유
- VRChat은 3만 명 이상의 동시접속자 수를 꾸준히 유지하고, 10월 4일에는 카시오와 파트너십 계약을 체결해 가상 스토어를 열며 인기를 유지 중이기 때문에 높은 접근성을 가짐
- VRChat은 개발자 친화형 플랫폼으로, 누구나 쉽게 자신이 만든 가상현실 콘텐츠를 업로드할 수 있음
- VRChat은 멀티 플레이를 지원하고 장려하기 때문에 멀티 플레이 게임을 구현하고 배포하기에 적합하며 실제로 캐치마인드, 초성게임 등을 간단히 구현한 맵도 존재
- 제안하는 게임은 플레이어가 게임의 변수이자 흥미 요소이기에 다양한 사람들이 모이고 함께 상호작용하는 VRChat의 특성과 잘 맞아떨어짐

## 프로젝트 기간
11/2 ~ 12/12

## 구현사항
### 개발 툴
- VRChat Creator companion
- Unity 2019.04
- UdonSharp

### 월드 구성 및 필요한 기능
-대기실: 아바타 변경, 무인도로 이동, 게임 시작 & 재시작
-무인도: 플레이어 및 AI 아웃, 아웃된 플레이어 위치 이동, 대기실로 귀환

### 사용한 에셋
![사용한 에셋](https://github.com/y00ns/group3_project/assets/104632673/a58da54f-f3c8-4128-b84c-bf8c42cb3263)

### 실제 구현 화면
- 아바타 변경
![아바타 옷장](https://github.com/y00ns/group3_project/assets/104632673/acf70404-e552-495e-a77e-a7cf03b59c33)
![아바타 변경](https://github.com/y00ns/group3_project/assets/104632673/1a5e7769-4434-43b5-897c-8a980b9d342b)

- 게임 시작
![게임시작](https://github.com/y00ns/group3_project/assets/104632673/a0e10b4f-eb32-4c98-b4cb-dba50bc227c4)

- 플레이어 아웃 & AI 아웃
![플레이어 제거](https://github.com/y00ns/group3_project/assets/104632673/4ef030e8-515f-4c33-98a7-46ac5f618f5b)
![AI 제거](https://github.com/y00ns/group3_project/assets/104632673/12524bea-1ec3-4e7d-b113-380c6357122e)

- 아웃된 플레이어
![플레이어 아웃](https://github.com/y00ns/group3_project/assets/104632673/16e601e9-b095-4fe6-9aeb-9b784a9dcc3d)
  
- 대기실 귀환
![트로피](https://github.com/y00ns/group3_project/assets/104632673/0a579a7b-9b23-4afd-9167-0d7d4f8a4eac)

- 게임 재시작
![포탈 이동](https://github.com/y00ns/group3_project/assets/104632673/248005f0-72a2-4c17-a8fc-1f76afac76ca)
