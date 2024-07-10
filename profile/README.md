# 🎨 doodling (두들링)
doodling은 낙서와 예술의 중간으로 평가되는 끄적댄 낙서 형태의 그림으로, 아이들이 낙서하듯 자유롭게 이야기를 이어나갈 수 있는 공간을 제공한다는 의미

## 👋 프로젝트 소개
- 주제: 릴레이 어린이 동화책 공모전을 진행하는 서비스
- 프로젝트 일정: 2024.06.24 ~ 2024.07.01

## 🚀 프로젝트 목적
- 현대어린이책미술관은 현대백화점 판교점에만 위치하고 있어 거리가 먼 아이들은 참여하기 어렵다는 단점을 해결하기 위한 비대면 온라인 참여형 서비스를 기획했습니다.
- 어린이들이 자신들의 이야기를 글뿐만 아니라 그림과 함께 표현할 수 있게 하여 시각적 사고력을 증진시킵니다.
- 다른 사람의 결과물을 보고 영감을 주고받으며, 커뮤니티에 참여하고 관점의 다양성을 이해하도록 합니다.

## ✨ 주 기능
- 진행 중인 공모전과 완성된 책 목록을 확인할 수 있습니다.

  ![일반_완성작조회](https://github.com/moka-doodling/.github/assets/38252649/ff0e9f94-00e9-4708-9c87-b80fe90b0742)

- 모든 사용자는 진행 중인 공모전에서 이전 주차의 당선작을 확인할 수 있고, 주차별로 1회 참여 가능합니다.

  ![일반_공모전상세조회](https://github.com/moka-doodling/.github/assets/38252649/326309ce-4e43-41c2-8b18-01f3d877d467)
  ![일반_공모전제출](https://github.com/moka-doodling/.github/assets/38252649/9e431d24-b0cd-487f-a18d-9deab43961b3)
- 자신의 제출 내역을 삭제할 수도 있습니다.

  ![일반_제출내역삭제](https://github.com/moka-doodling/.github/assets/38252649/3467bba7-1d3a-4fb5-b46a-80dbf730cbbb)

- 다른 사용자의 제출물을 확인할 수 있습니다.

  ![일반_다른사람제출목록](https://github.com/moka-doodling/.github/assets/38252649/982aa618-864e-4f18-bbed-aa6943dbec39)
- 마이 페이지에서 내가 제출한 제출물 목록을 볼 수 있습니다.

  ![일반_마이페이지에서제출확인](https://github.com/moka-doodling/.github/assets/38252649/2c19e897-7216-453b-8327-14dfd9c4fe10)
- 관리자는 공모전을 등록, 수정, 삭제할 수 있습니다.

  ![관리자_로그인](https://github.com/moka-doodling/.github/assets/38252649/46b5c443-9b30-47e2-90f6-69a9428a05d9)
  ![관리자_공모전등록](https://github.com/moka-doodling/.github/assets/38252649/940ac41e-4ed5-48b3-b722-a2e070d38e99)
  ![관리자_공모전확인](https://github.com/moka-doodling/.github/assets/38252649/51594239-3e03-411f-8075-d757ace2d4b4)

- 관리자는 진행 중이던 공모전을 마감하고 당선작을 선정할 수 있습니다.

  ![관리자_공모전마감](https://github.com/moka-doodling/.github/assets/38252649/14a60651-6c3d-448e-8f6a-1fd20edaf26b)
  ![관리자_당선작선정](https://github.com/moka-doodling/.github/assets/38252649/d8114665-1eca-459a-aa22-93868953a0d5)

- 관리자는 공지사항을 등록, 수정, 삭제할 수 있습니다. 이렇게 등록된 공모전은 모든 사용자가 확인할 수 있습니다.

  ![관리자_공지사항등록](https://github.com/moka-doodling/.github/assets/38252649/120ea79a-5052-4f53-a8c0-0559d3dc712d)
  ![일반_공지사항확인](https://github.com/moka-doodling/.github/assets/38252649/44f14855-c0af-4c9c-ac75-e5d189bfab80)

- 공모전을 확인하고 제출물을 등록하기 위해 회원가입과 로그인이 필요합니다.

  ![일반_로그인](https://github.com/moka-doodling/.github/assets/38252649/972cd54a-8d01-4e2e-b589-47aaaf1a13d7)
  ![일반_회원가입](https://github.com/moka-doodling/.github/assets/38252649/a5975b9e-bb8b-4371-b592-d3f91f5fef4f)



## ⚒️ 기술 스택
![시스템_아키텍처](https://github.com/moka-doodling/.github/assets/38252649/9d3009b9-74ad-475c-9c2b-acd2f663b58d)
- **Presentation Tier**: JavaScript, React, Styled Component
- **Application Tier**: Java 11, Spring 5.0.7, Spring Security 5.0.6, lombok 1.18.32, MyBatis 3.5.16
- **Data Tier**: Oracle 19c

## 👥 팀원
|이름|역할|github|
|---|---|-----|
|김지수|- 팀장<br>- 사용자 인증 도메인<br>- 백엔드 총괄|[soojik](https://github.com/soojik)|
|김지현|- 관리자 도메인<br>- 공모전 관리 시스템<br>- 디자인 총괄|[wlgus253254](https://github.com/wlgus253254)|
|이주현|- 제출물 도메인<br>- 완성된 책 뷰<br>- 프론드엔드 총괄|[JZU0](https://github.com/JZU0)|
