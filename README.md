<p align="center">
  <img src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/3cb798eb-c87d-46c5-acda-c3a14d656f4d">
</p>

## 실시간으로 그림을 그리고 맞추는 게임 서비스



본 서비스는 여러 사용자들이 초대코드를 통해 게임 방에 모여 실시간으로 그림을 그리고 정답을 맞추는 게임 서비스입니다.

## Demo



## System Architecture



<p align="center">
  <img src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/da2434bf-8ae4-471a-902c-d6ab44389011">
</p>

## **Features**



- Main Feature: 여러 사용자들이 초대코드를 통해 게임 방에 모여 실시간으로 그림을 그리고 채팅을 통해 정답을 맞추는 게임을 진행
- Additional Feature: 사용자들이 게임에서 그린 그림들을 그렸던 모든 그림들 모아보기

## Pages



Main Page

Creating Room Page

Entering Romm Page

Game Page

Game Result Page

Drawing Result Page

## Backend API



(캡처본 넣기)

## Tech Stack



| Frontend  | Backend | DevOps | Etc |
| --- | --- | --- | --- |
| - Typescript
- React
- Styled Component
- React Query
- websocket | - javascript
- nodejs
- MYSQL
- Amazon S3
- SWAGGER
- websocket
 | - NginX
- AWS
- Docker
- Vercel
- github actions | - POSTMAN
- GIT
- GRAFANA
- PROMETHEUS
- CAdvisor |

*Readme 뱃지 사용*

## ERD

<p align="center">
  <img src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/5b2dfd3e-d158-483e-8eb4-313d23d115cc">
</p>

## How to Start


### 1. Clone Repository

```markdown
$ git clone https://github.com/2023-Summer-Bootcamp-TeamD/frontend.git
$ git clone [https://github.com/2023-Summer-Bootcamp-TeamD/backend.git](https://github.com/2023-Summer-Bootcamp-TeamD/frontend.git)
```

### 2. Install Packages

```markdown
$ cd frontend
$ npm install
```

### 3. Set .env file

```markdown
.env file 내용
```

### 4. Run Docker

```markdown
$ cd backend
$ docker-compose up --build         # build images and run containers
$ docker-compose down               # stop running containers
$ docker-compose down -v            # stop running containers and delete its volume
```

### 5. Local execution

```markdown
$ cd ../frontend
$ npm run dev
```

## Directory Structure (프론트, 백엔드)



```markdown
**frontend**
├.github
│      ├ISSUE_TEMPLATE
│      └workflows
├.hursky
├node_modules
├public
└src
    ├apis
    ├assets
    ├atom
    ├common
    │    ├DrawingHeader
    │    └Header
    ├components
    │    ├Entrance
    │    ├Game
    │    └SkeletonSpinner
    ├constants
    ├context
    ├font
    │    ├KyoboHandwriting2019
    │    └UhBeemysen
    ├hooks
    ├mocks
    ├pages
    │    ├CreatingSpecificRooms
    │    ├DrawingResult
    │    ├EntryRoom
    │    ├Game
    │    ├GameResult
    │    └Main
    └types

**backend**
├.github
│      ├ISSUE_TEMPLATE
│      └workflows
├config
├migrations
├models
├monitoring
├routes
├seeders
├sockets
└swagger

**nginx**
```

## **URL**



- / → Main Page
- /creatingSpecificRooms → Creating Room Page
- /entryRoom → Entry Room Page
- /game/:entrycode → Game Page
- /result → Game Result Page
- /drawingRoom → Drawing Result Page

## Team



| Name | 최현정 | 구지혜 | 김예빈 | 김진수 | 서근재 | 윤정은 | 이승환 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Profile |  |  |  |  |  |  |  |
| Role | Team Leader,
Backend,
DevOps,
Frontend | Frontend
 | Frontend | Backend,
DevOps | Frontend | Backend,
DevOps | Frontend,
DevOps,
Backend |
| gitHub | https://github.com/ppinkypeach  | https://github.com/jihye9549  | https://github.com/Kimyebin00  | https://github.com/nsa06035  | https://github.com/tjrmswo | https://github.com/jungeunyooon  | https://github.com/Leeseunghwan7305  |
