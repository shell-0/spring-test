# SPRING TEST.
Ejercicio de Spring Boot 2.0

# EJERCICIO

1) Crear una base de datos con las siguientes caracteristicas

```
- Tabla de pacientes (nombre, apellido, correo, id, fecha de creacion, fecha de modificacion)
- Tabla de doctores (nombre, apellido, cedula, id, fecha de creacion, fecha de modificacion)
- Tabla de hospitales (nombre, id, fecha de creacion, fecha de modificacion)
- Tabla de hospitales pacientes
- Tabla de doctores paciente
```

NOTA: Utilizar JPA, Hibernate o JDBC para la capa de acceso de datos del proyecto de SpringBoot.

2) Crear una API REST para un hospital con las siguiente caracteristicas.

```
- CRUD de hospitales.
- CRUD de pacientes (Solicitar id del doctor).
- CRUD de doctores (Solicitar id del hopital).
- Consumir una API REST para validar la cedula de un doctor (GET https://hospital-shell-test.herokuapp.com/hospital/validar-cedula/CDL123) (Utilizar RestTemplate para su consumo)
  - CDL123 Invalida
  - CDL124 Valida
  Si no es valida no se podra dar de alta un doctor y mandara un error HTTP 400. (Utilizar Rest Exception Handler y throws)
- Guardado de documentos del paciente en el servidor (Solicitar el documento en base64 en el body del Json y el nombre del documento) (Convertir el documento de base64 a archivo y guardarlo en la carpeta "documentos")
```

NOTA: Se debera de utilizar una base de datos en MariaDB 


# ACCESOS

```
BASE DE DATOS

- IP: 44.200.130.219
- PUERTO: 3000
- NOMBRE DE LA BASE DE DATOS: hospital
- USUARIO: hts
- CONTRASEÑA: 565455301998Gyt7
```
