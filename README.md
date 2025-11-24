# Guía de actividades 
### Gestión de bases de datos 
### Caso de estudio “Clínica Veterinaria”

* Objetivo Extrae y Depura información proveniente de bases de datos Estructuradas y no estructuradas para el análisis posterior con herramientas analíticas estadísticas y algorítmicas.

* Uso de los mecanismos de consulta a bases de datos SQL. 

* **Se requiere almacenar información de los dueños de las mascotas (cédula, nombre, dirección, varios teléfonos).** 

* Cada mascota (nombre, especie, raza, fecha de nacimiento) pertenece a un único dueño. 
* Los Veterinarios (cédula, nombre, especialidad) atienden a las mascotas en 
* citas (fecha, hora, motivo). En cada cita, se genera un diagnóstico y se pueden recetar varios medicamentos. 
* La clínica también quiere llevar un registro del historial de vacunación de cada mascota, considerando que una mascota tiene muchas vacunas a lo largo de su vida." 


* Tablas que se crearan 
- pr_mascota(pk_mascota,nombre,especie,raza,fecha_nacimiento)
- pr_propietario(pk_propietario,nombre,apellido,cedula,fk_mascota)
- pr_veterinario(pk_veterinario,cedula,nombre       )
- pr_citas
- pr_vacunas
- trs_vacunacion


