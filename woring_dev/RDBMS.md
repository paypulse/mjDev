---
sort: 2
---

# RDBMS study

```note
## RDBMS란?

  Relational Data Base Manage System
  관계형 데이터 베이스 관리 시스템
  단순히 관련성이 있는 것끼리 묶는것을 넘어서 다른 데이터와의 연결성을 만들 수도 있다. 

  DBMS란?
  DataBase Manage Service 
  데이터를 관리 하는 서비스, 즉 소프트웨어를 말한다. 

```

## RDBMS 종류 
 oracle, postgresql, mssql-server, mysql,marinaDB,db2 , cubrid....

## RDBMS 종류 차이점 (:내가 경험한 RDBMS)

`oracle`
 - Open source가 아니다. 
 - 은행 등 대 다수의 대기업에서 많이 사용한다. 
 - multiple databases 튜닝이 가능하다. 
 - 다른 데이터 베이스 보다 고성능의 트랜잭션을 처리 
 - cost 비용을 최소화 하기 위해 테이블과 인덱스를 분석 한다. 
 - 높은 지원 하드웨어 사양이 필요 함 

 `postgresql`
 - Open source 다. 
 - Genetic query optimizer(유전 알고리즘)을 통한 쿼리 최적화 기술이 구현 되어 잇다. 
 - 기본적인 CRUD 성능이 MySQL등 다른 경쟁 DB에 비해 좋지 않다. 
 - 복잡한 데이터 워크로드를 안전하게 저장 한다. 
 - 북미와 일본에서 높은 인지도와 인기를 얻는다. 

 `SQL Server(MS-SQL)`
 - Open source가 아니다. 
 - Microsoft에서 개발한 SQK server이다. 
 - windows server에서만 구동이 된다. 
 - C#과 높은 호환성이다. 
 - 기본적으로 AUTO COMMIT이다. COMMIT/ROllBACK(BEGIN TRAN)을 추가 타이핑 해야 한다. 
 - .net, VS와 쉽게 연계 가능하다. 
 - 높은 보안 성 수준을 보여준다. 

`MySQL`
- Open source는 무료 , 상업용은 유료이다. 
- 1MB의 RAM만 사용할 만큼 용량 차지가 적다. 
- 매우 적은 오버 헤드를 사용한다. 
- 처리 속도가 빠르고 대용량 처리에 용이하다. 
- 거의 모든 운영체제와 다양한 프로그밍 언어와 통합 가능하다. 
- 복잡한 쿼리시 성능 저하
- 트랜 잭션 지원이 완벽하지 않음
- 사용자 정의 함수의 사용이 쉽지 않고 , 유연하지 않다. 

`MarinaDB`
- Open source이다. 
- GIS(Geographic Information system), JSON기능도 포함되어 있다. 
- MySQL과 소스코드를 같이 하므로 사요업과 구조가 MySQL과 동일 하다. 
- MySQL과 비교해 Application부분 속도가 약 4~5천배 정도 빠르다. 
- MySQL이 가지고 있는 모든 제품의 기능을 완벽히 구현 하면서도 성능면 에서는 최고 70%의 향상을 보이고 있다. 





[출처]
- [https://blog.naver.com/jword_/222897662527](https://blog.naver.com/jword_/222897662527)
- [https://t-okk.tistory.com/160](https://t-okk.tistory.com/160)
- [https://velog.io/@alicesykim95/Oracle%EA%B3%BC-MySQL%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90](https://velog.io/@alicesykim95/Oracle%EA%B3%BC-MySQL%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90)
- [https://wch18735.github.io/database/RDBMS/](https://wch18735.github.io/database/RDBMS/)
- [https://sw-ko.tistory.com/189](https://sw-ko.tistory.com/189)
- [https://devscb.tistory.com/49](https://devscb.tistory.com/49) 
- [https://rockplace.co.kr/dbms/mariadb/](https://rockplace.co.kr/dbms/mariadb/)
