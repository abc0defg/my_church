0. 프로젝트 2
- 중국어 교회 앱 만들기

​

1. 기획을 한다

- 중국어 목사님과 중국어 공부 후 전에 있었으면 하는 앱이 어떤 것인지 물어보았다.

- 교회에서 신도들과 하는 활동들을 온라인 상에서 앱으로 할 수 있었으면 한다.

- 성경 구절을 매일 올리고 관련 해석이나 영상을 올리면 사용자들은 이를 볼 수 있고 의견을 나눌 수 있다. 이미 읽은 것인지 아닌지가 표시된다. 몇 번 읽었는지도 기능을 넣을 수 있다.

- 교회 신도에게만 공개되는 영역이 있고 모두에게 공개되는 영영이 있다. 이를 누구냐에 따라서 구분한다.

- 예배 때 찍은 사진들을 올리고 언제라도 편하게 이를 볼 수 있다. 카톡 단체방에 올리고 있는데 메세지가 쌓이고 올라가고 휴대폰을 바꾸거나 하면 다시 볼 수 없거나 찾아보기 힘들다. 

- 사용자간에 대화를 나눌 수 있다. 메세지로도 가능하고 목소리를 보낼 수도 있고 통화도 가능하다. 댓글을 달 수 있고 대댓글도 달 수 있고 메세지에 대한 반응을 좋아요, 따봉, 사랑표 등으로 표현할 수 있다. 

- 성경 구절이나 메세지나 댓글 상에 올린 글은 자기가 설정한 언어로 번역할 수 있다. 번역하기 전의 글이나 번역한 후의 글은 해당 언어로 읽어주기 기능을 통해 들어볼 수도 있다.

- 성경 통독을 사용자간에 게임처럼 경쟁적으로 할 수 있도록 윗칸에는 해당 성경 구절이 있고, 밑칸에는 이를 타자칠 수 있도록 하는 공간이 있다. 원문과 자기가 친 글을 비교하여 정확하면 넘어가고 정확하지 않은 부분은 빨간 밑줄을 표시하여 준다. 넘어가면 넘어갈 수록 점수가 쌓이고 사용자들 간에 상대의 점수와 순위를 알수 있도록 하여 참여도를 높인다. 순위가 다른 이에게 따라 잡히면 알림을 보낸다. 

- 사용자들은 안드로이드 폰도 있고 아이폰도 있다. 웹으로 접속하는 경우도 있다. 

- 차후 다른 예배나 다른 교회에서도 사용할 수 있도록 한다. 

​

​

2. 단하나의 기능으로 좁힌다

- 안드로이드 앱 만들기 

- 하나의 게시판에 글을 올리고 저장할 수 있도록 만들기

​

3. 최소한의 기술을 찾는다.

- 네이버카페를 이용하면 위에서 언급한 기능 중 상당 부분은 쓸 수 있다. 근데 여기까지. 

- 하이브리브앱 : 네이티브 앱은 안드로이드폰용과 아이폰용으로 따로 만들어야 하는데, 웹, 안드로이드, 아이폰 가리지 않고 다양한 플랫폼에서 돌릴 수 있다. 

https://www.hanl.tech/blog/category/web/

- 비주얼스튜디오 코드에서 깃을 사용해서 버전관리하는 법. 20221115화

https://opentutorials.org/module/5752/30685

git remote add 20221115origin https://github.com/abc0defg/my_church.git 


rr@rrs-MacBook-Pro my_church % git add readme.txt


rr@rrs-MacBook-Pro my_church % git commit -m "first commit"

[main 1dd95cb] first commit

1 file changed, 60 insertions(+)

create mode 100644 readme.txt



rr@rrs-MacBook-Pro my_church % git remote add origin https://github.com/abc0defg/my_church.git


rr@rrs-MacBook-Pro my_church % git push -u origin main

Enumerating objects: 6, done.

Counting objects: 100% (6/6), done.

Delta compression using up to 10 threads

Compressing objects: 100% (4/4), done.

Writing objects: 100% (6/6), 1.87 KiB | 1.87 MiB/s, done.

Total 6 (delta 0), reused 0 (delta 0), pack-reused 0

To https://github.com/abc0defg/my_church.git

* [new branch] main -> main

branch 'main' set up to track 'origin/main'.



4. 구현한다. 

​

5. 불만족을 따라서 살을 붙여간다.