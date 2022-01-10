---
title: Flask Board project
layout: post
summary: Flask board 프로젝트에 대한 소개입니다.
author: fpem123
date: '2021-11-05 00:00:00'
category: project
keywords: project, python, web, flask
usemathjax: true
thumbnail: "/assets/img/projects/flask_board/flask_board.PNG"
permalink: "/blog/flask-board-project/"
---

## 프로젝트 사이트 링크 🌌

### [Flask Board](http://hoseop.pythonanywhere.com/){:target="_blank"}
### [Git repo](https://github.com/fpem123/flask_board){:target="_blank"}

<hr>

## 어떤 프로젝트인가? 🤔

Python으로 만든 간단한 게시판 프로젝트입니다. Back end는 python의 flask 프레임워크를 사용하였고 DB는 SQLite를 사용했습니다. Front end는 javascript, HTML, CSS를 사용했습니다. 이 프로젝트는 저 혼자 만들었으며, 2021년 10월 12일부터 시작해 2021년 11월 3일에 마무리되었습니다. 일반적인 커뮤니티 사이트들에 구현된 기능들을 최대한 구현해 보았습니다. 부족해 보일 수 있는 프로젝트이지만 재밌게 봐주세요.😊


<hr>

## 왜 만들었는가? 🤔

솔직하게 말하면 포트폴리오 용으로 만들었습니다. 그동안 여러 프로젝트를 만들어보았어야 했는데, 그러질 않아 다른 분들께 제 역량을 어필하기가 매우 어려웠습니다. 그래서 저는 이 프로젝트를 제작하기로 결심했습니다. 하지만, 제대로 된 절차 없이 부랴부랴 만들어서 많이 부족해 보일 수 있습니다.

<hr>

## DB 🏟

<center><img src="/assets/img/projects/flask_board/flask_board_db.png" width="90%"></center>

DB는 5개의 Table로 심플하게 구성돼있습니다. User 테이블은 회원 정보 테이블, Article은 글 정보 테이블, Comment는 댓글 정보 테이블, Hit_history는 추천 정보 테이블, Image_files는 사진 정보 테이블입니다. 

<br>

<center><img src="/assets/img/projects/flask_board/flask_board_db_domain.png" width="80%"></center>
<br>

Article_id FK들은 글이 없어지면 필요가 없는 필드가 되기 때문에 CASECADE로 설계하였고, User_id FK들은 유저가 사라져도 글과 댓글은 볼 수 있게 하고 싶어서 SET NULL로 설계해였습니다. 


<hr>

## API 🚀

<table>
    <thead>
    <tr>
        <th scope="col">API 주소</th>
        <th scope="col">요청</th>
        <th scope="col">이름</th>
        <th scope="col">설명</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>/member/join/request</td>
        <td>POST</td>
        <td>회원가입</td>
        <td>사이트 회원가입을 위한 API.</td>
    </tr>
    <tr>
        <td>/member/login/request</td>
        <td>POST</td>
        <td>로그인</td>
        <td>로그인을 위한 API.</td>
    </tr>
    <tr>
        <td>/member/logout/request</td>
        <td>POST</td>
        <td>로그아웃</td>
        <td>로그아웃을 위한 API.</td>
    </tr>
    <tr>
        <td>/member/update/request</td>
        <td>POST</td>
        <td>회원 정보 수정</td>
        <td>회원 정보 수정을 위한 API.</td>
    </tr>
    <tr>
        <td>/member/delete/request</td>
        <td>POST</td>
        <td>회원 탈퇴</td>
        <td>회원 탈퇴를 위한 API.</td>
    </tr>
    <tr>
        <td>/board/write_submit</td>
        <td>POST</td>
        <td>글 작성</td>
        <td>글 작성을 위한 API. 글 작성 요청은 5초 안에 연속으로 할 수 없습니다.</td>
    </tr>
    <tr>
        <td>/article/get</td>
        <td>GET</td>
        <td>글 가져오기</td>
        <td>글을 가져오는 API. aid에 해당하는 글을 가져옵니다.</td>
    </tr>
    <tr>
        <td>/board/update_submit</td>
        <td>POST</td>
        <td>글 수정</td>
        <td>글을 수정하는 API.</td>
    </tr>
    </tbody>
</table>

<br>

Flask board에서 구현된 API들 중 일부입니다. 부랴부랴 만들어서 그런지 API 주소와 요청들이 좀 지저분합니다. 그래도 커뮤니티 사이트들에 구현된 기능들을 제 나름대로 비슷하게 흉내 내보았습니다.


<hr>

## UI 🗺

<center>

<img src="/assets/img/projects/flask_board/flask_board_hand.png" width="60%">

</center>

프로젝트를 위해 가장 먼저 손그림으로 구상해 본 UI입니다.

<br>

<center><img src="/assets/img/projects/flask_board/flask_board_art.png" width="100%"></center>

그림을 기반으로 카카오의 OVEN을 이용해 프로토타입을 만들었습니다. <a href="https://ovenapp.io/view/6xyc7AHTnkoAuw75yHj5af5yY7xJylTH/" target="_blank">이곳</a>에서 직접 시연해 보실 수 있습니다.

<center>

<img src="/assets/img/projects/flask_board\flask_board_home.png" width="80%">

<img src="/assets/img/projects/flask_board/flask_board_board.png" width="80%">

<img src="/assets/img/projects/flask_board/flask_board_article.png" width="80%">

</center>

최종 완성된 Flask board의 UI입니다. oven으로 만든 UI와 비슷하게 만들었습니다. 친구들이 테스트를 도와줬었는데 다행히 알려주지 않아도 게시판의 기능들을 제가 의도한 방향대로 수행해 주었습니다.

<hr>

## 호스팅 🥳

릴리즈는 python 프로그램을 전문으로 호스팅 해주는 <a href="https://www.pythonanywhere.com/" target="_blank">PythonAnywhere</a>란 사이트를 통해 호스팅 하였습니다. 호스팅 된 프로젝트의 링크는 <a href="http://hoseop.pythonanywhere.com/" target="_blank">이곳</a>입니다. 사진 업로드는 pythonanywhere 무료 플랜의 제한된 용량과 관리의 용이함의 이유 (이용하는 분은 없지만 위험한 사진을 올리는 분이 나타날 수도 있기에😅)로 막아두었습니다.

<hr>

## 후기 ❤

어찌어찌 완성되었고 호스팅도 되었지만, 아쉬움이 남는 프로젝트입니다. Good 프로그래머라면 Actor 정의와 use case 분석, UML로 시작해 테스트 코드 같은 것들로 철저히 만들었어야 하는데 너무 부랴부랴 만들었는지 까먹고 말았습니다.😥 서버를 만드는 중에도DB를 여러러 번번 갈아엎고 Front도 자주 바꾸고 하나의 Python 파일에 많은 걸 담아버리고... 어찌찌보면 면면 Bad 프로그래머 같은 행위를너무 많이이 한한 것같습니다. 그러다다 보니니 간단한 프로젝트임에도 한 달 정도로 좀 길게 걸린 것 같습니다. 그래도 이번 프로젝트는 헛된 것이 아닌 넘어지면서 배울 수 있는 경험이었다고 생각합니다. 역시프로그래밍은 제대로 된된 분석과 테스트를 준비하는 것으로 시작해야 함을 배울 수 있었습니다.

<hr>
