# winwizProject


 Header 부분
 ==
=> position: fixed 적용하여 상단에 고정

=> 제이쿼리와 자바스크립트 마우스오버, 마우스리브 이벤트 사용하여 모달창 구현
(상단 헤더 부분에 마우스 올리면 아래에 있는 서브메뉴가 내려오면서 배경 화면도 색깔이 변화함. 가운데 아래에 있는 서브 메뉴 영역 바깥 쪽으로 움직이면 다시 창이 닫힘)

=> 미디어쿼리를 사용하여 medium-1024px일 때 로고 모양 변화, mobile-768px일 때는 로고 가운데로 이동하고 좌측에 메뉴 버튼 추가

=> 아코디언. 모바일에서 좌측 상단 메뉴 버튼 클릭 시 메뉴가 좌측에서부터 열림. 또한 우측에 있는 X버튼을 누르면 닫힘.
메뉴를 클릭하면 아래에 있는 서브메뉴가 나오고 다시 누르면 닫힘. 또한 다른 메뉴 클릭시에도 서브 메뉴가 닫히고 클릭한 메뉴가 열림. (자바스크립트 조건문 활용)
이 부분은 부트스트랩과 같은 자바스크립트 플러그인을 사용하면 더 쉽게 만들 수 있으나 반응형 작업(모바일로 변하였을 때)이 이루어지는 것이고 자바스크립트를
직접 작성하여 구현해 보았습니다.


 본문 페이지(솔루션, 인재채용, 고객지원)
==
=> 화면에 있는 탭메뉴에 css를 적용하여 그 메뉴에 있는 페이지에 있을 때 탭 아래에 밑줄이 표시되고
탭 메뉴에 있는 다른 탭 위에 마우스를 올렸을 때 밑줄이 그어지거나 탭 버튼의 색깔이 변화하게 만들었음.

=> 미디어 쿼리로 모바일 화면에 맞춘 본문 탭 및 이미지, 내용 변화

=> 양식에 빈칸이 있는 상태에서 전송하기 버튼을 누를 경우에 alert창을 띄우는 기능 구현(자바스크립트 및 제이쿼리 활용)
조건문은 활용하여 구현할 수 있었습니다.

=> 로그인 페이지에서 아이디를 입력하지 않으면 ‘아이디를 입력하세요’, 비밀번호를 입력하지 않았을 때 ‘비밀번호를 입력하세요’
또는 비밀번호가 짧은 경우(6자 미만)일 때 ‘비밀번호가 짧습니다’와 같은 빨간색 문구가 뜨게 표시.
마찬가지로 조건문을 활용하여 구현할 수 있었습니다.
