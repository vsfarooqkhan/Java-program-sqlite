# Java-program-sqlite
Java awt program to store values in sqlite .
Please follow the instructions given below::

1.	Install Sqlite, Eclipse on your system.

2.	download sqlite jar file from  https://bitbucket.org/xerial/sqlite-jdbc/downloads/
	(Preferred verion sqlite-jdbc-3.8.11.2.jar)

3.	Goto Eclipse -> new -> New Project -> Set Project name.

4.	Goto Project tab -> Properties -> Click on Java Build path -> Libraries -> Add External jARs -> Select the downloaded sqlite jar file.

5.	Create database folder : C:\Sqlite\db

6.	Create a table in sqlite using command 
	(or)
		in the first time use of program enable these two lines by removing // keywords:
		//String sql = ", CREATE TABLE farooq1 (\n" + "	first char(40),\n" + "	last char(50)\n"+ ");";
		//stmt.executeUpdate(sql);

		If you see "table created " command in output in next use of program disable those above lines by adding //
