mysql -u root -p 로 접속 시도 시 다음과 같은 에러 발생
ERROR 2002 (HY000): Can't connect to local MySQL server through socket '/tmp/mysql.sock' (2)
해당 에러의 경우 mysql.server start로 실행시켜주면 해소
