# Mysql2 - A modern, simple and very fast MySQL library for Ruby - binding to libmysql
# Install MySQL Server w/ Rails on Windows

Hello my name is Bilal and I work as FreeLancer

This is my Roby and rails Install MySQL Server w/ Rails on Windows!

Follow me at RehanTech

Download https://dev.mysql.com/downloads/connector/cpp/

C:\Program Files\MySQL\Connector C++ 8.0 

Copy past that folder to C:\

(First Change root path  MySql Connector File to Main Drive C:\Connector)

Then open git bash run these commands

gem install mysql2 -- '--with-mysql-lib="C:\Connector\lib" --with-mysql-include="C:\Connector\include"'

gem install mysql2

rails new my-app -d mysql

mysql -u root -p

Enter User Name And Password

quit;

cheak Config file to database linked or not
nano config/database.yml


password: [MySQL password]

rails db:create

Create db and set db name or fields name 

and run cmd rails s

