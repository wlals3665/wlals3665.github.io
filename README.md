# 첫번째 수업시간 
git에 branch를 생성하고 터미널에서 작업중인 branch를 전환,merge, 또한 -d를 통하여 삭제하는 방법 또한 알아볼 수 있었다.
github을 이번강의를 통해 사용하게 되면서 다시끔 github의 장점을 느끼게 되었다. 
local저장소(개인 컴퓨터)에 바뀐 내역들을 remote저장소(github)에 저장함을 통해 내가 바꾸기전 파일들의 상태를 다시 확인할 수 있어서 편리했다.
Markdown이라는 텍스트 편집기와 그것의 문법에 대해서도 알 수 있었다.
Markdown의 문법(나는 주로 Header, Italic, Bold를 사용했다)을 익히고 이를 활용하여 텍스트를 작성함으로써 가독성을 높일 수 있었다.
수업이후 Markdown을 활용하여 첫번째 블로그 포스트(About Topic)를 작성하는 assing1을 하였다.

# 두번째 수업시간 
Repository를 생성하여 remote하였다. 
예시문서(index.html)를 작성하고 git staus,add commit-m "msg"로 커밋남기고 git branch -M main으로 현재 branch의 이름을 main으로 변경하였다.
이때 git push를 해주기 위해 Personal Access Token(PAT)를 생성하였다. 토큰의 유효기간이 최소 30일이라는것과 한번 잊어먹으면 다시 만들어야한다는 강의를 듣고 보안이 철저하다고 느꼈다.
이렇게 작성한 예시문서(index.html)은 이후 나에게 블로그를 만드는데 큰 걸림돌이 되었다.
index.html이 삭제되지 않아 나의 github page인 https://wlals3665.github.io/ 에 자꾸 index.html의 텍스트(This is test page.)만 뜨게되어 결국 repository를 삭제하고 다시 만들게 되었다.
(다시 만들때에는 index.html 실습을 생략했다)
다음 수업시간을 위해 jekyll 홈페이지에 들어가 설치방법을 읽은 후 설치하였다.\

# 세번째 수업시간 
Jekyll을 본격적으로 사용하고, 실습이 늘어나게 되었다.
jekyll가 잘 설치 되어있는지 jekyll -v를 통해 확인할 수 있었다.
나는 현재 디렉토리에 jekyll이 설치가 안되어서 Eureka라는 디렉토리에 설치를 하였다. 
bundle exec jekyll serve를 실행하여 local host에 접속했을 때 jekyll사이트가 정상적으로 뜨는것을 보고 뿌듯했다.
config.yml 파일의 역할과 중요성의 대해서 알 수 있었다. 실제로 실습에서 이 파일을 수정하고 추가하는 경우가 많았다. 
title을 jimin's Blog로 바꾸고 email또한 입력했다. 정상적으로 바뀐후 원격저장소에 remote하여 나의 github page인 https://wlals3665.github.io/에 반영될수 있도록 하였다.
(이때, 위에 말했다 싶이 index.html의 텍스트만이 계속 떠서 repository를 재생성하였다.)
첫번째 수업시간에 assign으로 작성한 About Topic에 대한 문서를 업로드하였다.
마지막으로 나에게 맞는 테마를 찾아 블로그에 적용해보았다. 나는 깔끔한 느낌을 선호하기 때문에 simplex라는 테마를 적용하였다.
이후 시간관계상 테마를 적용하는 방법을 많이 생략하셨는데 나는 https://zeddios.tistory.com/1223 이 블로그를 참조하여 쉽게 적용할 수있었다.
블로그 log에는 내가 좋아하는 유튜버(hahaha)의 고양이인 무를 넣었다. 로고가 작게 나와 아쉬웠다. 후에 크게 적용할 수 있는 법을 알아볼 예정이다.

# 네번째 수업시간 #
Disqus 홈페이지에 가입하여 블로그에 댓글기능을 추가할 수 있었다. 나는 comment 정책을 조금 더 완화하게 하기 위해서 Balanced 정책을 선택했다. 
사이트의 favicon을 추가했다. https://blog.naver.com/prt1004dms/221451802933 블로그를 참조하였다. assets 폴더 안에 logo.ico란 폴더를 만든 후 파비콘 zip파일의 압축을 풀어주었다.
그 후 includes파일의 head.html을 수정하였다.


