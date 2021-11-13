# combo_ghmatti
A middleware for FiveM servers with vRPEX framework, a trial version aimed at vRP.

## Differentials
### > Supports multiple queries (using ";")
### > If you have a condition in your query (which uses ";" without being a multiple query), and you want to do a multiple query, it needs to be the first query used in prepare.
### > Execute mode will always return integer number type the affected rows
### > The scalar mode doesn't have to change in this middleware
### > In standard query mode, multiple queries will return, when they are setters, the amount of affected rows, and when getter, they will return the selected rows.
### > Remembering that it will return multiple queries in separate variables, not an array.

## Scripts requireds
### > [ghmattimysql](https://cdn.discordapp.com/attachments/845530016199868436/909208842338979880/ghmattimysql.zip) - database driver
### > vrpex - framework

## Instalação

Inicialmente seguir [passos de instalação](https://freesoft.dev/program/147247406) na documentação do database driver, posteriormente:

### > Se sua base for vRPEX Creative, não é necessário fazer essa etapa:
Abrir **vrp/cfg/base.lua**
Alterar a key **driver** para **ghmattimysql**
