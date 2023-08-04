<p align="center">
  <img src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/3cb798eb-c87d-46c5-acda-c3a14d656f4d">
</p>

## 실시간으로 그림을 그리고 맞추는 게임 서비스

본 서비스는 여러 사용자들이 초대코드를 통해 게임 방에 모여 실시간으로 그림을 그리고 채팅을 통해 정답을 맞추는 게임 서비스입니다.

## Demo
<div width='100px'>
  <img src='https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/8b96de03-dda7-4851-9386-0b945dffb62b'/>
</div>


## System Architecture



<p align="center">
  <img src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/da2434bf-8ae4-471a-902c-d6ab44389011">
</p>

## **Features**



- Main Feature: 여러 사용자들이 초대코드를 통해 게임 방에 모여 실시간으로 그림을 그리고 채팅을 통해 정답을 맞추는 게임을 진행
- Additional Feature: 사용자들이 게임에서 그린 그림들을 그렸던 모든 그림들 모아보기

## Pages

<table width='100%'>
  <tbody>
    <tr bgcolor='#D6D4D3'>
      <th width='50%' align="center">Main</th>
      <th width='50%' align="center">Creating Room</th>
    </tr>
    <tr>
      <td align="center"><div>
  <img src='https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/8b96de03-dda7-4851-9386-0b945dffb62b'/>
</div></td>
      <td align="center"></td>
    </tr>
    <tr>
      <td align="center"></td>
      <td align="center">유저가 카테고리, 방 인원과 라운드 당 제한 시간을 선택하고, 자신의 닉네임을 입력 후에 방을 생성한다. </td>
    </tr>
  </tbody>
</table>
<table width='100%'>
  <tbody>
    <tr bgcolor='#D6D4D3'>
      <th width='50%' align="center">Entry Room</th>
      <th width='50%' align="center">Game</th>
    </tr>
    <tr>
      <td align="center"></td>
      <td align="center"></td>
    </tr>
    <tr>
      <td align="center">방을 생성한 유저의 입장 코드를 받고 입장 코드와 닉네임을 입력해서 특정 방으로 입장한다.</td>
      <td align="center">한 사용자는 랜덤으로 제시된 단어를 그리고 나머지 사용자는 채팅으로 정답을 맞춥니다. 인원 수만큼 차례를 돌며 게임을 진행합니다. </td>
    </tr>
  </tbody>
</table>
<table width='100%'>
  <tbody>
    <tr bgcolor='#D6D4D3'>
      <th width='50%' align="center">Game Result</th>
      <th width='50%' align="center">Drawing Room</th>
    </tr>
    <tr>
      <td align="center"></td>
      <td align="center"></td>
    </tr>
    <tr>
      <td align="center">게임 종료 시, 게임의 결과를 보여줍니다.</td>
      <td align="center">서비스를 이용했던 사용자들의 모든 그림을 모아봅니다. </td>
    </tr>
  </tbody>
</table>

## Backend API
![swagger](https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/93309061/584bb552-4891-4311-a680-14043909196a)



## Tech Stack

<table>
  <tbody>
    <tr>
      <th align="center">Frontend</th>
      <th align="center">Backend</th>
      <th align="center">DevOps</th>
      <th align="center">Etc</th>
    </tr>
    <tr>
      <td align="center"> 
        <img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=flat&logo=typescript&logoColor=white">
        <br />
        <img src="https://img.shields.io/badge/REACT-61DAFB?style=flat&logo=react&logoColor=white">
        <br />
        <img src="https://img.shields.io/badge/SOCKET.IO-010101?style=flat&logo=SOCKET.IO&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/REACT QUERY-FF4154?flat&logo=reactquery&logoColor=white">
        <br />
        <img src="https://img.shields.io/badge/STYLED COMPONENTS-DB7093?style=flat&logo=styledcomponents&logoColor=white">
      <td align="center">
        <img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=flat&logo=JAVASCRIPT&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=NODE.JS&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/SOCKET.IO-010101?style=flat&logo=SOCKET.IO&logoColor=white" />
        <br/>
        <img src="https://img.shields.io/badge/MYSQL-4479A1?style=flat&logo=MYSQL&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/SWAGGER-85EA2D?style=flat&logo=SWAGGER&logoColor=white" />
        <br />
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/NGINX-009639?style=flat&logo=NGINX&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=Amazon EC2&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat&logo=Amazon RDS&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat&logo=Amazon S3&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/DOCKER-2496ED?style=flat&logo=DOCKER&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/VERCEL-000000?style=flat&logo=VERCEL&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/GITHUB ACTIONS-2088FF?style=flat&logo=GITHUB ACTIONS&logoColor=white" />
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/POSTMAN-FF6C37?style=flat&logo=POSTMAN&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/GIT-F05032?style=flat&logo=GIT&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/GRAFANA-F46800?style=flat&logo=GRAFANA&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/PROMETHEUS-E6522C?style=flat&logo=PROMETHEUS&logoColor=white" />
        <br />
        <img src="https://img.shields.io/badge/C ADVISOR-6D6D6D?style=flat&logoColor=white" />
      </td>
    </tr>
  </tbody>
</table>





## ERD

<p align="center">
  <img src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/1148f37e-0041-43e7-803c-c9a9fa72504c">
</p>

## How to Start


### 1. Clone Repository

```markdown
$ git clone https://github.com/2023-Summer-Bootcamp-TeamD/frontend.git
$ git clone https://github.com/2023-Summer-Bootcamp-TeamD/backend.git
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

##Socket

## Team


<table>
  <tbody>
    <tr>
      <th align="center">최현정</th>
      <th align="center">구지혜</th>
      <th align="center">김예빈</th>
      <th align="center">김진수</th>
      <th align="center">서근재</th>
      <th align="center">윤정은</th>
      <th align="center">이승환</th>
    </tr>
    <tr>
      <td align="center"><img width="100" alt="image" src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/cfd48573-d179-46a8-8647-6cddcf9ce71b"></td>
      <td align='center'><img width="100" alt="image" src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/afbcfd8d-1851-4cb5-be0f-7e01053e97d9">
</td>
      <td align='center'><img width="100" alt="image" src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/9a9bc664-2e25-4992-a1df-62371430bc4c">
</td>
      <td align='center'><img width="100" alt="image" src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/0d54e412-bf42-4f24-b348-eb4a3488f665">
</td>
      <td align='center'><img width="100" alt="image" src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/f72e8e28-b3ec-4ded-8546-7e0b00d1d1d1">
</td>
      <td align='center'><img width="100" alt="image" src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/c52ebaaa-6ffe-410f-9735-812bae628af3">
</td>
      <td align='center'><img width="100" alt="image" src="https://github.com/2023-Summer-Bootcamp-TeamD/.github/assets/70912819/db5d3104-b617-4fc8-b7ed-42b9c21fe698">
</td>
    </tr>
    <tr>
      <td>Team Leader <br />Backend <br />DevOps</td>
      <td>Frontend</td>
      <td>Frontend</td>
      <td>Backend <br />DevOps</td>
      <td>Frontend</td>
      <td>Backend <br />DevOps</td>
      <td>Frontend <br />DevOps</td>
    </tr>
    <tr>
      <td><a href="https://github.com/ppinkypeach">@ppinkypeach</a></td>
      <td><a href="https://github.com/jihye9549">@jihye9549</a></td>
      <td><a href="https://github.com/Kimyebin00">@Kimyebin00</a></td>
      <td><a href="https://github.com/nsa06035">@nsa06035</a></td>
      <td><a href="https://github.com/tjrmswo">@tjrmswo</a></td>
      <td><a href="https://github.com/jungeunyooon">@jungeunyooon</a></td>
      <td><a href="https://github.com/Leeseunghwan7305">@Leeseunghwan7305</a></td>
    </tr>
  </tbody>
</table>

