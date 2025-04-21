# 🧪 SQL Lab: CREATE, ALTER, TRUNCATE, DROP Tables

Welcome to the **SQL DDL Commands Lab**!  
In this hands-on lab, you'll master the core **Data Definition Language (DDL)** statements in SQL:  
`CREATE`, `ALTER`, `TRUNCATE`, and `DROP`.

---

## 📚 What You'll Learn

By the end of this lab, you'll be able to:

- ✅ Create new tables using `CREATE`
- ✅ Modify table structures with `ALTER`
- ✅ Remove all rows (but not the table) using `TRUNCATE`
- ✅ Delete tables completely with `DROP`

---

## 🧰 Software & Tools Used

- 🔹 **IBM Db2 Database**  
  A powerful RDBMS from IBM used to store, analyze, and retrieve data efficiently.
- 🔹 **IBM Cloud Db2 Console**  
  SQL queries were executed through the **Run SQL** interface on IBM Cloud.

---

## 🧪 Exercises & SQL Commands

### 📌 Exercise 1: CREATE Tables

```sql
CREATE TABLE PETSALE (
    ID INTEGER NOT NULL,
    PET CHAR(20),
    SALEPRICE DECIMAL(6,2),
    PROFIT DECIMAL(6,2),
    SALEDATE DATE
);

CREATE TABLE PET (
    ID INTEGER NOT NULL,
    ANIMAL VARCHAR(20),
    QUANTITY INTEGER
);
