# SHOEKREAM Project

![shokreammain](https://user-images.githubusercontent.com/78721108/139569482-db28b424-c233-4df5-9520-4da68e528439.gif)

- PREMIUM BIIDINGS

## 🎇 팀명 : shoekream - 슈크림

> 의류 경매 서비스를 제공하는 [KREAM](https://kream.co.kr/)을 모티브로 제작하게 된 SUN-KREAM 팀의 프론트엔드 레포지토리 입니다.
> 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.
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

- 🔗 [https://youtu.be/N63MUdDmDFI] : 

## ⚙ 적용 기술

- **Front-End** : JavaScript, Styled Component, React, JSX
- **Back-End** : Python, Django, MySQL, jwt, bcypt, AWS RDS, AWS EC2
- **Common** : Git, Github, Slack, Trello, Postman or Insomnia

## 🗜 [데이터베이스 Diagram(클릭 시 해당 링크로 이동합니다)](https://www.erdcloud.com/d/6Kq4rCsrgRkjcfZxk)

![kream](https://user-images.githubusercontent.com/78721108/139569506-39104ecf-7060-4aa0-8d45-c834bc1a4174.png)

## 💻 구현 기능

### BACKEND

#### 박치훈

> 메인 페이지

-
- > 소셜 로그인
-
- > 입찰 결제
-
- > 상세 페이지
-
- > 상품 리스트

#### 양가현

-

#### 송영록

-

### FRONTEND

#### 김현진

> 메인 페이지

- 메인 레이아웃구현
- React-slick 라이브러리 이용 및 CSS 커스터마이즈 슬라이더 구현
- 메인 상세페이간 이동 구현
- Nav/Footer/ 검색창 레이아웃 구현
- 검색창 모달 구현
- localStoragies 저장을 통한 최근 검색어 구현
- 검색어 중복제거 기능 구현
- 검색창 keyword backend와 동적통신
- 검색어와 상세페이지 이동 구현

#### 박산성

> 제품 상세 페이지

- HTTP 통신을 통한 특정 제품 상세 정보 렌더링
- `slick` 라이브러리를 활용한 슬라이드 구현
- 사이즈 변경 모달 및 드롭 다운 UI 구현
- 관심 상품 버튼 클릭 시, DB 내 관심 상품 등록 및 화면 반영 로직 구현
- 거래 버튼 및 관심 상품 클릭 시, 토큰 유무에 따른 로그인 요청 구현
- `chart.js` 활용하여 커스터마이징 차트 구현
- 사이즈 별 차트 데이터 및 테이블 데이터 요청
- 차트 컨트롤 바 구현을 통한 기간별 차트 데이터 요청
- 조건부 렌더링을 활용한 다음 기능 구현
  - 테이블 데이터 카테고리 변경 기능
  - 구매 전 확인 내용 토글 기능

> 사이즈 선택 페이지

- URL 경로에 따라 구매/판매 화면 구분 렌더링
- 구매/판매 제품 데이터 요청
- 제품 사이즈 목록 및 최고 혹은 최저 거래가 리스트업
- 제품 사이즈 선택 시, 다음 페이지로 넘어가는 확인 버튼 조건부 렌더링

> 마이페이지

- 로그인 유저 정보 요청 및 반영
  - 유저 이름, 이메일, 잔여 포인트 등
- 유저 구매/판매 기록 및 카운트 반영
- 관심 상품 목록 확인 및 해당 상품 상세 페이지 이동 기능

#### 이선호

> 제품 아이템 레이아웃 (공용 컴퍼넌트)

> 제품 리스트 페이지

- 제품 리스트 페이지 레이아웃
- `slick` 라이브러리를 활용한 슬라이드 구현
- 메인컨텐츠 무한 스크롤기능 구현
- 전체적인 토글 / 모달창기능 구현
- 상단 아이템 클릭 시, Nav검색 기능이 나타나도록 구현
- 인기순 필터기능 (프리미엄, 즉시 구매순, 즉시 판매순) 클릭 시, 필터링을 통한 데이터 요청
- 카테고리 필터기능 (브랜드별, 사이즈별, 가격별) 클릭 시, 필터링을 통한 데이터 요청
- fetch를 통해 백엔드의 상품 가져오기 / 동적 라우팅 /api 활용



#### 하상영

-

## ⌨ EndPoint

-

## ❗ Reference

- 이 프로젝트는 [KREAM](https://kream.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 모두는 copyright free 사이트들의 이미지들을 취합 및 canva 에서 직접 제작한 이미지들로 제작되었습니다.
