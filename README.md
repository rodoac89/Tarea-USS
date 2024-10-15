# Ejercicio
Desarrolle un software que le permita al
usuario registrarse.
Debe tener 2 métodos registro
* Cliente, que solo muestra un saludo
* Administrador puede agregar o quitar y autorizar registros de cliente.


## Secuencia:
  
### Administrador

1. Login admin -> Ver usuarios pendientes -> ver tabla para autorizar
2. Agregar usuarios -> registrar el cliente directamente mediante un formulario
3. Quitar usuarios -> Elimina el usuario

* Vista de autorizacion:

| ID | Nombre | Apellido | Accion |
|----------|----------|----------|----------|
| 1 | Rodolfo   | Aravena  | autorizar/denegar
| 2 | Andres   | Perez   | autorizar/denegar
| 3 | Rose   | Ara   | autorizar/denegar

## Estructura de tabla de los clientes

```sql
CREATE TABLE IF EXISTS USUARIO(
	ID INTEGER PRIMARY KEY,
	NOMBRE VARCHAR(50),
	APELLIDO VARCHAR(50),
	IS_STAFF BIT
);
```

# Fecha de entrega: 15 de octubre 2024 a las 18:30

