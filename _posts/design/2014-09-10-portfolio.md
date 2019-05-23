---
layout: page-fullwidth
title: "Github"
subheadline: "Portfolio"
teaser: github

 #"With <em>Feeling Responsive</em> you don't need a special portfolio template. Just check out the great possibilities of the <a href='http://foundation.zurb.com/docs/components/grid.html'>foundation grid</a> and experiment with it."
categories:
    - design
---
<!--more-->

Github bash 는 git에 대한 명령을 실행할 때 쓰는 CMD창과  흡사하다.
 설명 : 아래와같은 과정을 진행하는 것은 내가만든 프로젝트와 로컬저장소를 실시간 연동하기 위함이다.
 사전에 해야할 내용은 다음과 같다.
	= Github 가입 > 프로젝트 생성
	Repository name 생성 규칙 : username.github.io
	1) <a href="http://jekyllthemes.org/">jekyll theme에서 마음에드는 테마 고르기.</a>
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git1.png">
  2) 마음에 드는 페이지를 선택하면 Download나 홈페이지에서 상세하게 볼 수 있다.
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git2.png">
  3) 원격저장소(github server)의 Repository를 지역저장소로 가져오기(Git Clone 주소복사)
	 나의 GitHub 에서 Clone or Download button을 클릭하여HTTPS 주소를 복사하여 저장해논다.
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git3.png">
 Git bash 로 로컬저장소에 저장 명령어 실행<br>
 <img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git4.png"><br>
 탐색기로 로컬저장로소 경로로 가보면 다운로드가 되어있다.
 저장 경로는 현재 경로로 다운로드 됨. /zip 다운로드로 제공하거나 그게 아니면 git bash 명령어로 저장.
 나의 GitHub Server 저장소 디렉토리에 다운로드한 파일을 복사(압축해제)하여 저장한다.
 Git bash 로 저장한 목록들을 확인해본다 $ git status
 아래 빨강음영 텍스트가 복사 상태이며 해당 파일을 쓰기로 바꿔보자.
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git5.png"><br>
 Git add --all (쓰기)
 Git commit -m "Jekyll initiaql commit" (""안에 들어가있는 내용은 테마마다 다르므로 예제이다)<br>
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git6.png">
 <br>Add 를 활성화하였다면 git server 에 밀어넣어보자.
 ! 밀어넣기전에 github server 저장소 주소를 이름으로 바꿔보자.
 $ git remote add origin(저장소 주소를 이름화 시키기 예제 : origin) 저장소 주소 붙여넣기.<br>
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git7.png">
 <br>주소를 이름으로 변경되었다면 확인하여 보자.
 $ git remote -v (현재 저장소 주소 목록이 나타난다)
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git8.png">
 <br>주소가 정상적으로 이름에 할당이 되었다면 저장소 서버로 밀어넣어보자
 $ git push origin master<br>
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git9.png">
 <br>휑하게 비었던 나의 github server 저장소가 그럴싸하게 변경되었다.
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git10.png">  
 그리고 내 주소를 복사하여 웹페이지에 띄워보자.
<img src="https://wave5.github.io/wave5.github.io-feeling-responsive/images/git11.png">

이제 나도 홈페이지를 만들 수 있게 되었다.!!굿굿!! 서버를 따로 안둬도 되고, 계속 안켜놔도 나만의 홈페이지가 제작이 되었다. github 최고ㅋㅋ~~


수정사항이 생겨 서버로 밀어넣고자 한다면 $git add > commit > push 로 간단하게 변경하자.
<br>$git status<br>
$git add --all<br>
$git commit -m ""<br>
$git push (server link) master

Github server link 동기화 명령어 :
$git remote add origin (server link)
내 GitHub 로컬 저장소 : C:\Users\사용자이름\Documents\GitHub\깃허브저장소
좀 더 많은 명령어는 아래 블로그를 참조하자
<a href="https://gbsb.tistory.com/10">blog참조</a>

Github desktop 이력조회 : <a href="https://wave5.github.io/wav5.github.io/">Github Desktop</a>



각 file 별 기능들 요약 사이트 : <a href="https://postitforhooney.tistory.com/entry/GitHubJekyll-Jekyll-설치-및-실행-Theme변경-로컬-실행-1">요약사이트</a>

동영상 참고 : <a href="https://opentutorials.org/module/2398/16117">동영상</a>

Agency theme : <a href="http://jekyllthemes.org/themes/agency/">Agency Theme</a>

<div class="row t60">
    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}webdesign_screenshot_nixdorf.jpg" alt="">
        <p> Website: Nixdorf Internatsberatung &amp; Schulberatung</p>
    </div><!-- /.medium-6.columns -->

    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}webdesign_screenshot_jcorneille.jpg" alt="">
        <p>Website: <a href="http://jcorneille.de">Grafik Design Jeannette Corneille</a></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t30">
    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_stilwandel.jpg" alt="">
        <p>Website: <a href="http://stilwandel-koeln.de">Stilwandel-Koeln.de</a></p>
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_tarnkappe.jpg" alt="">
        <p>Website: <a href="http://tarnkarppe.info">Tarnkappe.info</a></p>
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_schriefer.jpg" alt="">
        <p>Website: <a href="http://www.psychotherapie-schriefer.de/">Praxis für psychologische Psychotherapie Simone Schriefer</a></p>
    </div><!-- /.medium-4.columns -->
</div><!-- /.row -->
