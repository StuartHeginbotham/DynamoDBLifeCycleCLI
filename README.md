README.txt

simple example of:

  creating a table - createTableMusic.txt

  putting two rows of data in it with individual puts - putDataMusic.txt
  OR
  putting two rows of data in with batchWrite - batchWriteMusic.txt (depends on batchWriteMusic.json)

  querying it with same query but with two different syntaxes -
    queryMusic.txt
    OR
    queryMusic-file.txt (depends on keyCondition.json)

deleting the table - deleteMusic.txt

Ubuntu example of running each file at command line in same directory as file:

bash createTableMusic.txt

optional log:

bash createTableMusic.txt > createTableMusic.log


Requires configured AWS command line installed (tested 2017 eu-west-1)
