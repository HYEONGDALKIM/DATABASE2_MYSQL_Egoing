# DATABASE2_MYSQL_Egoing // Relational DBMS
### DATABASE
- File이 가진 한계를 극복하기 위해서 고안된 전문화된 소프트웨어
- DATABASE는 기능이 방대하다. 왜냐하면 DATA에 대해 일어날 수 있는 일이 상당히 많기 때문이다.
- input과 output의 How를 파악한다.  (CRUD! input - Create, Update, Delete   output - Read) 
- file > spreadsheet > database (database의 장점 : 자동화 기능)
- 스프레드시트와의 차이점은 SQL이라고하는 C-Lang을 통해서 컴퓨터를 제어할 수 있다.
- 웹과 앱을 통해서 공유가 가능하고 분석가능하다

### MariaDB 설치관련  

    https://opentutorials.org/course/3161/19532
    210824 MySQL대신 MariaDB Database가 설치된다. 

이동 후에 mysql -uroot -p 입력 후 비밀번호 입력

### MariaDB의구조

스키마는 서로 연관된 데이터들을 그룹화한다. 

![image](https://user-images.githubusercontent.com/78002734/130782992-cc180c30-9e50-4a1a-a71b-b96920cc9f95.png)

### MariaDB 서버접속! 
MariaDB이 있는 폴더로 이동한다. >> 
C:\Bitnami\wampstack-7.4.22-0\mariadb\bin

이동 후에 mysql -uroot -p 입력 후 비밀번호 입력

### 스키마의 사용
생성 : CREATE DATABASE ~ ; 

삭제 : DROP DATABASE ;  
 
    검색엔진 키워드 사용법  how to show database list in mysql
    
USE []; - [] 안의 대상으로 수정이 시작된다.

### SQL과 테이블의 구조 
 SQL - Structured Query Language
 
 table - 표, row - 행, column - 열
 
 ### 테이블의 생성
  
 create table in mysql cheat sheet
 
 ![image](https://user-images.githubusercontent.com/78002734/130786352-84dd1f3d-39ac-4bfe-a789-85a383b01bad.png)

     DATABASE DATA TYPE 
     https://www.techonthenet.com/mysql/datatypes.php
     
 ERROR가 뜨면 검색엔진에 검색 stackoverflow<< 많이 쓰는 사이트 
 
 ### INSERT
 
 예를들어 topic이라는 테이블이 있으면 INSERT를 하기전에 DESC topic으로 테이블의 구조를 한번 확인 한 후에 진행하는 것이 좋다.
 
 * SQL 관련함수 NOW() - 현재시간을 표시해준다
 
 테이블안에 모든 내용을 보는것 ! : SELECT * FROM topic 
 
 
 ### SELECT 
 
 DESC, ASEC, WHERE ORDER BY , GROUP BY HAVING, LIMIT등 다양한 옵션으로 검색에 제약을 줄수 있다. 
 
 SELECT문을 잘 사용하여야 SQL을 잘한다고 말할 수 있다.
 
  ### UPDATE
  
    UPDATE [LOW_PRIORITY] [IGNORE] table_references
    SET assignment_list
    [WHERE where_condition]
 
  ### DELETE
  
  ## where 을 빠뜨리면 큰일난다 조심 

 ### 인터넷과 데이터베이스
 
 인터넷이 돌아가기 위해서는 최소최대 2대가 필요하다.
 
 컴퓨터들간의 사회 
 
 cliet(요청하는쪽)   -    server(서비스 제공자)
 
  ### MYSQL 클라이언트 
  
  ### MYSQL Workbench
  
