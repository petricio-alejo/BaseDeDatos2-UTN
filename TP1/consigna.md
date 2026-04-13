# Consigna de Trabajos Prácticos

## Base de Datos II - UTN

---

## Unidad 1: Fundamentos, Integridad y Concurrencia

### Ejercicio 1: Reglas de Integridad

Dado un modelo de base de datos de una universidad, identificar violaciones posibles a la integridad referencial si se elimina un estudiante con cursos inscritos. ¿Qué mecanismos usarías para evitarlo?

---

### Ejercicio 2: Implementación de Restricciones

Crear una tabla `Matriculas` con restricciones de clave foránea. Luego, insertar datos que violen la integridad y mostrar el error generado.

---

### Ejercicio 3: Concurrencia

Simular una situación donde dos usuarios intentan actualizar el mismo saldo de una cuenta bancaria. Analizar cómo afectan las condiciones de aislamiento (READ COMMITTED vs SERIALIZABLE).

---

## Unidad 2: Optimización de Consultas, Índices y Vistas

### Ejercicio 4: Plan de Ejecución

Usar una base de datos con más de 100,000 registros. Ejecutar una consulta sin índice y luego con índice. Usar EXPLAIN para comparar rendimiento.

---

### Ejercicio 5: Creación de Índices

Diseñar una consulta que filtre por múltiples campos. Crear diferentes índices y medir cuál ofrece mejor rendimiento.

---

### Ejercicio 6: Vistas

Crear una vista que resuma las ventas mensuales por producto. Luego, usarla en una consulta que devuelva los 5 productos más vendidos.

---

## Unidad 3: Administración, Seguridad y Mantenimiento

### Ejercicio 7: Gestión de Permisos

Crear un usuario `analista` que solo pueda hacer SELECT en ciertas tablas. Intentar insertar desde ese usuario y explicar el resultado.

---

### Ejercicio 8: Seguridad y Auditoría

Simular una auditoría simple con triggers que registren toda modificación en una tabla `Clientes`.

---

### Ejercicio 9: Backup y Restore

Documentar paso a paso cómo hacer un backup completo en MySQL o PostgreSQL y cómo restaurarlo. Simular una pérdida de datos y su posterior recuperación.