use hr;

/* Mostrar detalles de la tabla jobs en la que el salario minimo es superior a 10000. */

Select *
from jobs
where min_salary > 10000;

/* Mostrar el nombre y la fecha de contratacion de los empleados que fueron contratados entre 1950 y 2000 */

Select first_name, hire_date
from employees
where hire_date between '1950-01-01' and '2000-01-01';

/*  Mostrar el nombre y la fecha de contratacion de los empleados que son IT_Programer o Sales Man */

Select first_name, hire_date
from employees
where job_id ='IT_PROG' or job_id ='ST_MAN';

/* Mostrar los empleados que fueron contratados despues de 01/01/1950 */


Select *
from employees
where hire_date >= '1950-01-01';

/* Monstrar los empleados que tienen un identificador de empleado 150 o 160 */


Select employee_id, first_name
from employees
where employee_id in (150,160);

/* Mostrar el apellido, salario, comision y la fecha de contratacion de los empleados que tienen un salario inferior a 10000. */

Select last_name, salary, commission_pct, hire_date
from employees
where salary < 10000;

/* Mostrar para cada lugar de trabajo (job_title) la diferencia entre el salario maximo y el salario minimo en una nueva columna que se denomine "DIFFERENCE",
de aquellos por los cuales su salario maximo este entre el rango 10000 a 20000. muestra la informacion de la tabla JOBS ordenada de manera descendiente por titulo. */

SELECT job_title, max_salary, min_salary, max_salary - min_salary AS 'DIFERENCE' 
from jobs 
where max_salary between 10000 and 20000
order by job_title desc;

/* Mostrar los empleados en los cuales su nombre o apellido comience por S */

Select first_name, last_name
from employees
where first_name like 'S%' or last_name like 'S%';

/* Mostrar toda la informacion de la tabla empleados por los cuales el porcentaje de comision es nulo, el salario esta entre 5000 y 10000 y pertenecen al departamento 50 */

Select *
From employees
where commission_pct is NULL 
	and salary between 5000 and 10000
    and department_id = 50;




