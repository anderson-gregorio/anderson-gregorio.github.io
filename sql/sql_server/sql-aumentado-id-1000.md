# SQL aumentado o ID em 1000 unidades

A partir do SQL Server versão 2012 a Microsoft mudou a forma de gerar esses valores, quando a sua instância do SQL Server é reiniciada, então o valor de um campo Identity pula 1000 se for campo inteiro (int) e 10000 se o campo for do tipo (bigint).

[https://pt.stackoverflow.com/questions/36881/sql-aumentando-o-id-em-1000-unidades/36890#36890](https://pt.stackoverflow.com/questions/36881/sql-aumentando-o-id-em-1000-unidades/36890#36890)