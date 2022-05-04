# Super-Hasangsu-Messenger

## 프로젝트 기획안

작성일 : 2022. 05. 04
작성자 : 하상수

### ⦁	프로젝트 명 : 슈퍼하상수메신져


### -----	기획 의도 -----

⦁	회원가입을 하여 친구추가 기능을 사용하여 친구허용을 한 친구끼리만 메시지를 주고받는다.

⦁	자바 콘솔안에서 구현하는 것에는 한계가 있기에 현재 존재하는 서비스중에서 내가 가진 기초
  적인 자바지식을 활용하여 구현을 어디까지 할수 있는지 알아보고싶었음.
 
⦁	회원가입이 되어있고 로그인이 되어 있는 상태에서만 사용가능.

⦁	친구신청 기능을 사용하여 신청받은 유저가 수락을 하여 친구관계가 성립되어 있을때에만 서로 
  메시지를 주고 받을수 있다.

### -----	벤치마킹 -----

⦁	현재 거의 모든 메신져가 가지고 있는 가장 기본적인 기능을 벤치마킹 하였다.

### -----	주요 기능 -----

⦁	회원가입 - 기본 적인 정보를 입력 받아 회원가입을 완료한다.

⦁	로그인 - 회원가입시 입력한 아이디와 비밀번호 모두 일치 할시 로그아웃이나
          종료전까지 해당 회원이 로그인 상태를 유지한다.
          
⦁	내정보조회 - 조회전 현재 로그인상태인 아이디의 비밀번호를 입력받고 그 값이
             '참'일 경우에만 해당 유저의 정보를 보여준다.
             
⦁	내정보수정 - 조회전 현재 로그인상태인 아이디의 비밀번호를 입력받고 그 값이
              '참'일 경우에만 해당 유저의 정보를 보여주고 수정할 정보를 선택
               하여 정보를 수정할수있다.
               
⦁	친구목록 - 친구관계가 성립된 유저 목록

⦁	친구 신청기능 - 친구관계를  성립하고 싶은 사람의 아이디를 입력하면 해당 아
                 이디를 가진 유저에게 친구 신청기능이 실행 된다.
                 
⦁	친구 수락기능 - 로그인 했을때 다른유저가 친구신청을 하였다면 알려주고 수락
                을 하였을 경우에만 친구관계가 수락된다. 거절을 할 경우에는
                 신청한 유저에게 친구신청을 거절하였다고 알려준다.   
                 
⦁	메시지 보내기 - 친구목록상의 친구를 선택하여 메시지를 보낼수있다.

⦁	메시지 확인 - 메시지를 확인 하고 메시지를 보낸 유저에게 답장을 보낼 수 있다

⦁	메시지 보관함 
⦁			a. 친구들과 주고 받은 모든 메시지 조회
⦁			b. 친구선택 조회 - 친구를 선택항 해당 친구와 주고받은 메시지만 조회
 
