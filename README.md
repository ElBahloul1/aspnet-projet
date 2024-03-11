1-veuillez installer 
microsoft.entityframeworkcore.sqlserver et
microsoft.entityframeworkcore.tools

2-apres 
modifier la connexion string in Appsettings.json


3-apres 
Tools ===> Nuget packet manager ===> package manager console  puis executer ses cmd =>
Add-Migration "migration"
Update-Database
