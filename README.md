#### 1 - Realize login no MySQL.
```shell
sudo mysql;
```
#### 2 - Crie e acesse o banco de dados ```desafio```
```sql
create database desafio;
use desafio;
```
####3 - Crie a tabela planetas
```sql
create table planetas(
id integer not null PRIMARY KEY auto_increment,
name varchar(50) not null,
climate varchar(50) not null,
Terrain varchar(50) not null,
qtd_filmes integer,
status integer not null
);
```
