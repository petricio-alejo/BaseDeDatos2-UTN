Fundamentos, Integridad y Concurrencia
Ejercicio 1: Reglas de Integridad
Dado un modelo de base de datos de una universidad, identificar violaciones posibles a la integridad
referencial si se elimina un estudiante con cursos inscritos. ¿Qu´e mecanismos usar´ıas para evitarlo?
Ejercicio 2: Implementaci´on de Restricciones
Crear una tabla Matriculas con restricciones de clave for´anea. Luego, insertar datos que violen la
integridad y mostrar el error generado.
Ejercicio 3: Concurrencia
Simular una situaci´on donde dos usuarios intentan actualizar el mismo saldo de una cuenta bancaria.
Analizar c´omo afectan las condiciones de aislamiento (READ COMMITTED vs SERIALIZABLE).
Optimizaci´on de Consultas, ´Indices y Vistas
Ejercicio 4: Plan de Ejecuci´on
Usar una base de datos con m´as de 100,000 registros. Ejecutar una consulta sin ´ındice y luego con
´ındice. Usar EXPLAIN para comparar rendimiento.
Ejercicio 5: Creaci´on de ´Indices
Dise˜nar una consulta que filtre por m´ultiples campos. Crear diferentes ´ındices y medir cu´al ofrece
mejor rendimiento.
Ejercicio 6: Vistas
Crear una vista que resuma las ventas mensuales por producto. Luego, usarla en una consulta que
devuelva los 5 productos m´as vendidos.
Administraci´on, Seguridad y Mantenimiento
Ejercicio 7: Gesti´on de Permisos
Crear un usuario analista que solo pueda hacer SELECT en ciertas tablas. Intentar insertar desde
ese usuario y explicar el resultado.
Ejercicio 8: Seguridad y Auditor´ıa
Simular una auditor´ıa simple con triggers que registren toda modificaci´on en una tabla Clientes.
Ejercicio 9: Backup y Restore
Documentar paso a paso c´omo hacer un backup completo en MySQL o PostgreSQL y c´omo restaurarlo. Simular una p´erdida de datos y su posterior recuperaci´on.