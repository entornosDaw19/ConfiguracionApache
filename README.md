# ConfiguracionApache
Vamos a documentar configuraciones básicas de apache en ubuntu server 18.04
- Después de probar la configuración básica (utilización del contenedor <directory> Redirect, ErrorDocument, ErrorLog, CustomLog, LogLevel,           creación de Alias ...
 
- Activamos el módulo userdir, creamos el directorio public_html en el directorio del usuario y probamos su funcionamiento
  mediante la petición: http://ipServidor/~nombreUsuario
  
  - Activamos los módulos auth_basic, auth_digest, authn_file, authz_user con lo que se crearán los respectivos enlaces simbólicos del directorio mods-available al mods-enabled.
  - Creamos los ficheros de contraseñas con los comandos: htpasswd y htdigest
  - Configuramos la entrada al directorio Curso del servidor para que tenga autenticación Basic
  - Configuramos la entrada al directorio Apuntes del servidor para que tenga autenticación Digest
  
