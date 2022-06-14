# Library-Program
This repository contain HTML and Python files that are needed to make this program

For the modules, you will need to install Flask and mysql-connector on pip python. For this kind of project, i'd love to use environment first before installing anything. So my main modules won't mix with the others

And Database such as MySQL or SQLite (Every kind of database are good but i use MySQL as my Database when developing)

Note : Some variables here are written on Indonesian, you can search it by translating it

Table named user to collect user information :
- id integer(11) not null primary key auto_increment
- nama varchar(50) not null
- username varchar(70) not null
- password varchar(25) not null

Table named majalah to collect information or data about magazine :
- id integer(11) not null primary key
- judul varchar(50) not null
- lokasi varchar(50) not null
- volume varchar(50) not null
- edisi varchar(30) not null
- keterangan varchar(50) not null

Table named buku to collect information or data about books :
- id integer(11) not null primary key
- judul varchar(50) not null
- lokasi varchar(50) not null
- penerbit varchar(50) not null
- thn_terbit integer(11) not null
- jenis varchar(50) not null
- keterangan varchar(50) not null

Table named dvd to collect information or data about films :
- id integer(11) not null primary key
- judul varchar(50) not null
- lokasi varchar(50) not null
- direktor varchar(50) not null
- tahun integer(11) not null
- aktor varchar(100) not null
- genre varchar(100) not null
- keterangan varchar(50) not null

That's all
