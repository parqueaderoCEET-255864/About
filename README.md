# ProyectoParqueadero
## Integrantes
Javier Gimenez
Jose Martinez
Yenifer Olmos
# descripcion
El proyecto consiste en realizar un aplicativo en el cual nos permitira el control e ingresos de los vehiculos al CEET.para ello se realizo el caso de uso de los actores involucrados y ademas se creo los diagrama de clase paara la base de datos. 
## caso de uso
en los caso de uso se ve involucrado 3 actores los cuales son: administrador,usuario y seguridad.
# administrador
el administrador inicia sesion y es el encargado de realizar el registro,actualizacion y eliminacion de los login de seguridad.
# seguridad
las personas de seguridad inician sesion y son las encargadas de realizar el registro,actualizacion y eliminacion de datos de los usuarios, buscar en la base de datos la existencia de los mismos,ingresar los datos del vehiculo, asignar parqueadero asi como la fecha y hora de la salida y la entrada; a la salida del vehiculo verificar la identidad del usuario.
# usuario
El usuario esta en la obligacion de dadar los datos personales como nomobre,apellido,cedula,correo,celular,genero y rol. al momento del ingreso del vehiculo entregara su identificacion y el documento que certifique la pertenencia del mismo y a la salidad del vehiculo corrobar su identidad.
## diagrama de clase  base de datos
El diagrama de clase se realizo la agrupacion  de las diferentes datos:
## MARCA_VEHICULO	
MARCA_ID	
NOMBRE
## CILINNDRAJE	
CILINDRAJE_ID	
CANTIDAD
## HORARIO_ID			
HORARIO_ID
NOMBRE
HORA_INICIO	
HORA_FIN
## REGISTRO										
ID
USUARIO_ID
HORARIO_ID
VEHICULO_ID
MARCA_ID
CAMPO_ID
HORARIO_ENTRADA
HORARIO_SALIDA
PLACA_VEHICULO
CILINDRAJE	
FECHA_DATE
## CAMPOS
ID_CAMPOS
UBICACION
## DISPONIBILIDAD 
ID_DISPONIBILIDAD
DISPONIBILIDAD 
## USUARIOS_PERMITIDOS
USUARIO_ID
NOMBRE
APELLIDOS
DOCUMENTO_ID
NUMERO_DOCUMENTO
GENERO_ID
RH_ID
NUMERO_TELEFONICO
CORREO
ROL_ID
## GRUPO_RH
RH_ID
TIPO
## ROLES
ROL_ID
ROLES
## GENERO
GENERO_ID
NOMBRE
## DOCUMENTO
DOCUMENTO_ID	
TIPO	
NOMBRE














