# Use Model First to design a model and then generate a database

Model First is using a designer to define entities and their properties. These
are then used to create a database definition script, .net classes and the
derived DbContext class.

  

When you want to update the model you make the changes in the designer and
generate a new database definition script. This will drop any existing tables
and recreate them. If you want to keep the existing data then you'll have to
modify the script.

  

<https://msdn.microsoft.com/en-us/data/jj205424>

  

  


---
### NOTE ATTRIBUTES
>Created Date: 2016-10-09 18:17:44  
>Last Evernote Update Date: 2016-10-09 18:21:49  
>author: simonjstanford@gmail.com  
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MDk0NDU3NjldfQ==
-->