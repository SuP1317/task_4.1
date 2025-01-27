### [< Основные команды:](./readme.md/#2-основные-команды "На главную страницу")     
## <u> *git init*</u>

git init - позволяет создать пустой репозиторий Git или вновь инициализировать существующий можно параметром init. 

При выполнении команды git init в текущем рабочем каталоге создается подкаталог .git со всеми необходимыми метаданными Git для нового репозитория. Метаданные включают подкаталоги для объектов, ссылок и файлов шаблонов. Кроме того, создается файл HEAD, который указывает на текущий извлеченный коммит.

Если команда git init уже выполнялась по отношению к каталогу проекта и в нем есть подкаталог .git, команду git init можно безопасно выполнить для этого каталога повторно. Существующая конфигурация .git при этом не изменится.  

----
Примеры:   
Создание нового репозитория Git для существующей базы кода  
* cd /path/to/code \ 
* git init \ 
* git add . \ 
* git commit  

 
 
Создание нового чистого репозитория :  
*git init --bare /path/to/repo.git*
