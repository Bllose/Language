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
> **Indentation**  
> _noun_(SPACE)  
> a space left at the edge of a line of writing, or the process of leaving such a space.  
> _noun_(HOLE)  
> a hole or marker on the surface of something.  
> e.g.  
>> The heels of her shoes had left indentations in the mud.  
>> heel 鞋跟;  mud 泥地  
>>   
  
> **indicate**  
> _verb_(SHOW)  
> to show, point ,or make clear in another way  
>   

> **brace**  
> _noun_(SUPPORT)  
> something that is used to support or connect things, or to make something stronger.  
> e.g.  
>> He was recently fitted with a brace for his bad back.  
>  ---  
> a set of connected wires that is attached to a person's teeth in order to make them straight.  
> ![teeth barce](https://dictionary.cambridge.org/images/thumb/brace_noun_003_00248.jpg?version=5.0.155)  
> 

> **indent**  
> _verb_\[T] (SPACE)  
> to make a space at the edge or on the surface of something.  
> e.g.  
>> Each new paragraph should be indented about two centimetres from the margin.
