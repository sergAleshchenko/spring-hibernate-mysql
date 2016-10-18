Заготовка для приложения.

Приложение не реализовано полностью, это только эскиз. 

1) Создаем БД с такими параметрами (файл spring.properties):

app.jdbc.driverClassName=com.mysql.jdbc.Driver

app.jdbc.url=jdbc:mysql://localhost:3306/Provider

app.jdbc.username=root

app.jdbc.password=root


2) Таблица создается автоматически, вручную ничего создавать не нужно.

3) Приложение создавалось в Eclipse Neon Release (4.6.0). Для запуска заходим в Run -> Run Configurations -> 
Добавляем Maven Build в левой колонке (см. рисунок MavenBuild.png в корне проекта)

4) Иногда перед запуском надо обновить папки проекта (нажать Ctrl+A -> F5 в дереве проекта) или сделать Maven update project 
(правой кнопкой по папке проекта -> Maven -> Update Project...)