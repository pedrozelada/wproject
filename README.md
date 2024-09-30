#Sistema de la Materia de taller 1 Gestion 2024
#### Funciones de soporte

-  Acceso
   -Cuenta/contraseña admin/123456

   
- Gestión de usuarios
   - Agregar, editar, eliminar, deshabilitar/habilitar, consultar
   
   
- Gestión de menús
   - Agregar, editar, eliminar, consultar

- Gestión de roles
   - Agregar, editar, eliminar, autorizar, consultar

   
- Gestión de registros
   - Consulta


#### Arquitectura de software

- Inicio de sesión y control de acceso a través de SpringSecurity y JWT


- Los derechos de acceso de los usuarios están vinculados a través del permiso de rol de usuario.


-La gestión detallada de permisos llega al nivel del botón (control frontal)


- El código de verificación utiliza un caché local elaborado con Guayaba.


