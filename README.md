# oracle-db-deploy


CREATE TABLE empleados (
    id_empleado NUMBER PRIMARY KEY,
    nombres VARCHAR2(100),
    apellidos VARCHAR2(100),
    correo VARCHAR2(150),
    fecha_ingreso DATE,
    salario NUMBER(10,2)
);

INSERT INTO empleados
VALUES (
    1,
    'JUAN',
    'PEREZ',
    'juan.perez@empresa.com',
    SYSDATE,
    3500
);

INSERT INTO empleados
VALUES (
    2,
    'MARIA',
    'LOPEZ',
    'maria.lopez@empresa.com',
    SYSDATE,
    4500
);

COMMIT;
