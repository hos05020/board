### 스프링 부트, Spring Data Jpa, QueryDSL, MariaDB, Thymeleaf, Javascript(Jquery)를 이용하여 게시판을 만들었습니다.
#####  책: 코드로 배우는 스프링 부트 웹 프로젝트의 Part03 소스코드를 활용하였습니다.

이미 데이터베이스에 등록된 계정을 이용하여 게시물을 등록할 수 있습니다.(게시물에는 제목,내용, 계정을 등록할 수 있습니다)

게시물을 등록,수정,삭제하는 기술은 스프링 MVC패턴 + Spring Data Jpa을 이용하여 구현하였습니다.
<img src="https://user-images.githubusercontent.com/96513191/181027970-4d0874d9-ad93-4d90-9824-90f6ef3eb7fa.PNG" width="600" height="400">
<img src="https://user-images.githubusercontent.com/96513191/181028223-26863256-21b0-4a67-8219-b3028466fa5a.PNG" width="600" height="400">

게시물에 댓글을 등록,수정, 삭제 , 댓글 목록을 확인 할 수 있는 기능을 RestController,Spring Data Jpa와 Jquery을 이용하여 구현하였습니다.
<img src="https://user-images.githubusercontent.com/96513191/181028065-a9a7f64c-46c6-461e-b184-0e8e82ca2fa7.PNG" width="600" height="400">
<img src="https://user-images.githubusercontent.com/96513191/181028143-53164714-d511-4c06-8832-1d2aa744f748.PNG" width="600" height="400">
<img src="https://user-images.githubusercontent.com/96513191/181028194-8ba4ff50-7f45-4ddb-9bfc-482681201acd.PNG" width="600" height="400">

또한 게시물 목록을 조건(제목을 통해 검색, 내용을 통해 검색등)에 따라 검색할 수 있는 기술을 QueryDSL을 이용하여 구현하였습니다.
<img src="https://user-images.githubusercontent.com/96513191/181028239-2953b6b0-2d20-49ed-be5e-5373b189bb30.PNG" width="600" height="400">
