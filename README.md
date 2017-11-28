1. 댓글달기
2. 댓글지우기
3. 좋아요 기능

- 진핸순서..예

gem 'devise'  <br>
gem 'faker'  <br>
gem 'kaminari'  <br>

rails g devise:install  <br>

rails g scaffold posts title:string contents:text  <br>
rails g devise user  <br>
rails g model comments post:references body:text  <br>

rake db:migrate  <br>

has_many comments 잡아줌  <br>

application.scss 로 바꿔줌 and @import 'bootstrap'  <br>

application.html.erb 수정함  <br>

댓글 form show에 작성하고  <br>
routes 수정  <br>

show에 comments 추가  <br>
controller 수정  <br>
create_comment.js 만들기  <br>
등등 ...
