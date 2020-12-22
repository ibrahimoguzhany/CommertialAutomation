# E-CommerseAutomation
Asp.net MVC application app to get things done for your commpany. E-Commerse module is on the way!
#### Stack
 ##### -CodeFirst EF.6x ORM
 ##### -MSSQL 
 ##### -ASP.NET MVC pattern

## Configurations  
#### -Open the project with VS. Then open Web.config File.
#### -Set up a new database name(if you want.Mine is dataProject as you can see) and uid,pwd based upon your mssql connection information between ```<connectionStrings> <connectionStrings/>``` xml element.
#### -Open Package Manager Console in Visual Studio 
  ```View => Other Windows => Package Manager Console```
#### -Type ```update-database``` then press enter. (Migrations are activated in the project by default but if a problem occurs. Type 
  ```enable-migrations -enableautomaticmigration -force```
  before ```update-database``` command
##### Your Database should be setted up in Mssql. View some of the pages in Views by right clicking a view then clicking ```View in Browser``` .
