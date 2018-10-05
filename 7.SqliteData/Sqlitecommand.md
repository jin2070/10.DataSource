

pcdeMacBook-Air:documents pc$ sqlite3 test01.sqlite

sqlite> .mode list (.mode line)
sqlite> select *from cat;

sqlite> .separator ","
sqlite> .import exportedcoma01.csv cat
sqlite> .tables

sqlite> .separator ","
sqlite> .import exportedData03.csv horse
sqlite> .tables
sqlite> .header off
sqlite> select *from "Import Data";
sqlite> alter table "Import Data" rename to hello01;

sqlite> .output a.txt  //a.csv
sqlite> select *from table;
sqlite> .output stdout  //不输入页可以

 
 ALTER TABLE "Student" RENAME TO "_Student_old_20140409";
 
 创建新表
 
 CREATE TABLE "Student" (
 "Id"  INTEGER PRIMARY KEY AUTOINCREMENT,
 "Name"  Text);
 
 
 　　　　　　　　　　

