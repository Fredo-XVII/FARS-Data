# FARS-Data
FATALITY ANALYSIS REPORTING SYSTEM (FARS) ENCYCLOPEDIA

source: http://www-fars.nhtsa.dot.gov/QueryTool/QuerySection/SelectYear.aspx

Code for SQLite database
read.csv.sql("FARS_2013.csv", sql = "CREATE TABLE FARS_2013 AS SELECT * FROM file", dbname = "FARS2013.sqlite")
