## SQL 명령어 정리: DML, DDL, DCL

#### **1. DML (Data Manipulation Language)**  
데이터를 조회, 삽입, 수정, 삭제하는 명령어.  
- `SELECT`  
- `INSERT`  
- `UPDATE`  
- `DELETE`  
- 집계 함수: `SUM`, `AVG`, `MAX`, `MIN`, `COUNT`  
- 그룹 검색: `GROUP BY`, `HAVING`  

---

#### **2. DDL (Data Definition Language)**  
데이터베이스 객체(테이블, 뷰 등)를 정의, 수정, 삭제하는 명령어.  
- 테이블 관련:  
  - `CREATE TABLE`  
  - `ALTER TABLE`  
  - `DROP TABLE`  
  - `TRUNCATE TABLE`  

- 뷰(View) 관련:  
  - `CREATE VIEW`  
  - `ALTER VIEW`  
  - `DROP VIEW`  

- 인덱스 관련:  
  - `CREATE INDEX`  
  - `DROP INDEX`  

---

#### **3. DCL (Data Control Language)**  
데이터베이스의 권한 관리 및 트랜잭션 제어를 위한 명령어.  
- 권한 관리:  
  - `GRANT`  
  - `REVOKE`  

- 트랜잭션 제어:  
  - `COMMIT`  
  - `ROLLBACK`  
  - `SAVEPOINT`  

--- 
