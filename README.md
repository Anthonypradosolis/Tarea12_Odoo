# Tarea12_Odoo


## Apartado 1

``
create table EmpresasFCT(idEmpresa SERIAL PRIMARY KEY, 
						 nombre varchar(40), 
						 quiereAlumnos boolean, 
						 numAlumnos Integer,
						 fechaContacto date)
``       


![Apartado1](Trabajo_12/apartado1.png)



## Apartado 2

```
insert into EmpresasFCT(nombre,quiereAlumnos,numAlumnos,fechaContacto) values
('TrombonL',True,3,'2025/05/02'),
('LaCobra',True,2,'2025/05/01'),
('Alesas',False,0,'2025/05/01'),
('Leyendap',True,2,'2025/05/03'),
('SanMun',True,1,'2025/05/06')
```
![Apartado2](Trabajo_12/apartado2.png)


## Apartado 3

```
select * from EmpresasFCT order by fechacontacto desc
```
![Apartado3](Trabajo_12/apartado3.png)


## Apartado 4

```
select name,city,commercial_company_name from res_partner where is_company=False and city='Tracy' order by commercial_company_name;

```
![Apartado4](Trabajo_12/apartado4.png)


