# Core - Flask Login.

- Crea un nuevo proyecto Flask
- Crea una nueva base de datos MySQL con una tabla y los campos apropiados
- La ruta raíz debe mostrar una plantilla con los formularios de inicio de sesión y registro
- Valida la entrada de registro
- Si el registro no es válido, los mensajes de error deben mostrarse en la página de índice
- Si el registro es válido, cifra la contraseña con hash y guarda al usuario en la base de datos, almacena al usuario en sesión y luego redirige a la página de éxito
- Valida la entrada de inicio de sesión
- Si la entrada no es válida, muestra un mensaje de error en la página de índice
- Si el inicio de sesión es válido, almacena al usuario en sesión y luego redirige a la página de éxito
- Agrega un botón de cierre de sesión funcional a la página de éxito que borra la sesión
- Después de cerrar la sesión, asegúrate de que no puedes acceder a la página de éxito
```
APP_SECRET_KEY=poner cualquier cosa
BASEDATOS_HOST=localhost
BASEDATOS_USER=poner tu clave usuario
BASEDATOS_PASSWORD=poner tu clave de usuario
BASEDATOS_NOMBRE=poner nombre de la base
NOMBRE_SISTEMA=coloca lo que quieras
```