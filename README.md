# desafiog94


CREATE DATABASE felipe-mugnos-111;

CREATE TABLE clientes(...);





INSERT INTO clientes (email, nombre, telefono, empresa, prioridad)
     VALUES           ('FEL@GMAIL.COM', 'FELIPE','6450000', 'WOM',1),
	                  ('AND@GMAIL.COM', 'ANDRES','6450001', 'ENTEL',2),
					  ('JAV@GMAIL.COM', 'JAVIER','7450000', 'CLARO',5),
					  ('JOR@GMAIL.COM', 'JORGE','9990000', 'WOM',6),
					  ('JUA@GMAIL.COM', 'JUAN','7860000', 'MOVISTAR',3),
					  ('PEDRO@GMAIL.COM', 'PEDRO','1110000', 'VIRGIN',7),
					  ('FELICE@GMAIL.COM', 'FELICE','2220000', 'WOM',9),
					  ('FER@GMAIL.COM', 'FERNANDO','5680000', 'WOM',8),
					  ('JAVA@GMAIL.COM', 'JAVIERA','6220000', 'CLARO',4),
					  ('ERN@GMAIL.COM', 'ERNESTO','64450000', 'MOVISTAR',10);
select distinct nombre
from clientes
where prioridad >5;
--
--
SELECT distinct nombre, telefono, prioridad 
FROM clientes
order by prioridad ASC, nombre ASC
LIMIT 3;
