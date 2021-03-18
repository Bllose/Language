## 1.2 Indentation indicates code structure
There are no statement terminators or begin/end keywords or braces to indicate blocks of code.

Open connect.py in an editor. Indent the print statement with some spaces:
``` Python
import cx_Oracle
import db_config

con = cx_Oracle.connect(db_config.user, db_config.pw, db_config.dsn)
  print("Database version:", con.version)
```  
Save the script and run it again:

**python connect.py**  

This raises an exception about the indentation. The number of spaces or tabs must be consistent in each block; 
otherwise, the Python interpreter will either raise an exception or execute code unexpectedly.

Python may not always be able to identify accidental from deliberate indentation. 
Check your indentation is correct before running each example. 
Make sure to indent all statement blocks equally. 
**Note the sample files use spaces, not tabs.**  

