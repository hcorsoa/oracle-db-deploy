# oracle-db-deploy


CREATE TABLE empleados (
    id_empleado NUMBER PRIMARY KEY,
    nombres VARCHAR2(100),
    apellidos VARCHAR2(100),
    correo VARCHAR2(150),
    fecha_ingreso DATE,
    salario NUMBER(10,2)
);
