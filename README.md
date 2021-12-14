# SHOEKREAM Project

![shokreammain](https://user-images.githubusercontent.com/78721108/139569482-db28b424-c233-4df5-9520-4da68e528439.gif)

- PREMIUM BIIDINGS

## 🎇 팀명 : shoekream - 슈크림

> 의류 경매 서비스를 제공하는 [KREAM](https://kream.co.kr/)을 모티브로 제작하게 된 SUN-KREAM 팀의 프론트엔드 레포지토리 입니다.
> 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 모티브 하였습니다.
> 개발은 초기 세팅부터 전부 직접 구현했으며, 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발할 수 있도록 2주간 고군분투 하였습니다.

### 프로젝트 선정이유

- 조사결과, 해당 사이트의 경매 입찰 기능과 결제 플로우, 차트 구현, 상품리스트 필터 구현 등 배울 점이 많다고 판단하여 선정하게 되었습니다.

## 📅 개발 기간 및 개발 인원

- 개발 기간 : 2021/10/18 ~ 2021/10/29
- 개발 인원 <br/>
  👨‍👧‍👦 **Front-End** 4명 : [김현진](https://github.com/71summernight), [박산성](https://github.com/p-acid), [이선호](https://github.com/sunhoh), [하상영](https://github.com/sangyouh) <br/>
- [Front-end github 링크](https://github.com/wecode-bootcamp-korea/25-2nd-SUNKREAM-frontend)<br/>
  👨‍👧‍👦 **Back-End** 3명 : [박치훈](https://github.com/chihunmanse), [양가현](https://github.com/chrisYang256), [송영록](https://github.com/crescentfull)<br/>
- [Back-end github 링크](https://github.com/wecode-bootcamp-korea/25-2nd-SUNKREAM-backend)

## 🎬 프로젝트 구현 영상

- 🔗 [구현영상] : https://youtu.be/N63MUdDmDFI

## ⚙ 적용 기술

- **Front-End** : React with JavaScript, Styled Component
- **Common** : Git, Github, Slack, Trello, Postman or Insomnia

## 🗜 [데이터베이스 Diagram(클릭 시 해당 링크로 이동합니다)](https://www.erdcloud.com/d/6Kq4rCsrgRkjcfZxk)

![kream](https://user-images.githubusercontent.com/78721108/139569506-39104ecf-7060-4aa0-8d45-c834bc1a4174.png)

## 💻 구현 기능

#### 김현진

> 메인 페이지
 - React-slick 라이브러리를 활용하여 CSS를 커스터마이징 하였고 Caruosel을 구현하였습니다.
 - React-Router를 통하여 상품 컴포넌트와 상세페이지 간 이동 구현하였습니다.

> NAV / FOOTER
  - Nav와 Footer 레이아웃을 구현하여 모든 페이지에 나타낼 수 있도록 하였습니다.
  - Nav에 검색 창을 컴포넌트화 하여 Modal로 구현하였습니다.

> 검색창
  - LocalStorage를 통해 최근검색어가 저장되도록 구현하였고, 중복은 제거하였습니다.
  - 검색창에서 keyword 입력시 이에 알맞은 검색어 자동완성 컴포넌트를 구현하였습니다.
  - 검색어를 통해 상세페이지로 이동할 수 있도록 구현하였습니다.
