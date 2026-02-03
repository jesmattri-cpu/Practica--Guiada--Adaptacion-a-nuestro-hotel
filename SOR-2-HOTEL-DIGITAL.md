Tarea 1: Creación de Cuentas Operativas (CE a)
• Criterio asociado: Se han configurado y gestionado cuentas de usuario.
• Tarea: Configurar las nuevas cuentas de usuario para los empleados de la temporada alta (personal de recepción y nuevos camareros). Esto incluye establecer las políticas de caducidad de contraseñas y las restricciones horarias de inicio de sesión para el personal operativo, asegurando la correcta gestión de cuentas de usuario.

R) Para esta tarea he creado usuarios para cada empleado que pueda necesitar un ordenador o maquina conectada al servidor del horaio diurno y nocturno y de la rmama de administracion del hotel, tambien le he entrgado todo los permisos disponibles al usuario controller.
<img width="439" height="555" alt="Tarea -1" src="https://github.com/user-attachments/assets/31f8c395-bf19-4d53-8d4a-65151494287c" />
<img width="430" height="543" alt="Tarea 1 2png" src="https://github.com/user-attachments/assets/bf130dc4-5a4e-4874-8d8b-0fc1058a117b" />
<img width="449" height="522" alt="Tarea1 3" src="https://github.com/user-attachments/assets/e32b9c6e-bdbd-45cd-86ad-d4d6ccbc5d61" />

Tarea 2: Definición de Entornos de Trabajo (CE b)
• Criterio asociado: Se han configurado y gestionado perfiles de usuario.
• Tarea: Configurar y gestionar los perfiles de usuario específicos para dos roles críticos:

    1. El perfil del Controller (administrador financiero), que requiere acceso restringido a carpetas compartidas y herramientas de contabilidad.
    <img width="1402" height="890" alt="image" src="https://github.com/user-attachments/assets/edad65db-d99c-41a4-a1f7-7b751691db7a" />

   
    <img width="439" height="555" alt="Tarea -1" src="https://github.com/user-attachments/assets/1aa10268-faf2-43f9-a58f-d10aaf104dcf" />
    
<img width="431" height="546" alt="Tarea 2 1" src="https://github.com/user-attachments/assets/ce12361d-002a-4f23-8d94-3d0466a91e43" />

    2. El perfil del personal de Recepción, que necesita el software de gestión hotelera (PMS) como acceso predeterminado.
    
    <img width="537" height="620" alt="Ajustes-de-organizacion" src="https://github.com/user-attachments/assets/13a22ab2-04e0-4cda-ba28-619a88c871fb" />
     
<img width="428" height="547" alt="Tarea 2 2" src="https://github.com/user-attachments/assets/b0b8b1d1-8a74-4b94-be6a-9b1449d92b49" />

<img width="415" height="542" alt="Tarea2 3" src="https://github.com/user-attachments/assets/666255bc-73a0-447f-bdd1-f3a1d9c1f4c5" />

Tarea 3: Registro de Dispositivos (CE c)
• Criterio asociado: Se han configurado y gestionado cuentas de equipo.
• Tarea: Configurar y gestionar las cuentas de equipo para todos los dispositivos fijos nuevos incorporados a la red del hotel, incluyendo los TPV (Terminales de Punto de Venta) del restaurante y los ordenadores de uso compartido en el business center.
 
 R) He configurado los orenadores y puntos de venta de todos los empleados y usuarios que los puedan necesitar, Cada una puesta en un grupo indicado (Administracion, servicios cliente diurno, Servicio cliente nocturno)
<img width="477" height="517" alt="Tarea3 punto" src="https://github.com/user-attachments/assets/fc4fec12-5814-4aa5-bd56-68e6b95235f6" />

<img width="421" height="474" alt="Grupo-de-administracion-del--hotel" src="https://github.com/user-attachments/assets/2a487c7f-bb17-44e7-be45-01823b520d02" />

Tarea 4: Diseño de la Estructura de Acceso (CE d)
• Criterio asociado: Se ha distinguido el propósito de los grupos, sus tipos y ámbitos.
• Tarea: Diseñar la jerarquía de grupos necesaria para la gestión de permisos. Esto implica distinguir el propósito de los grupos según su función (seguridad vs. distribución) y sus tipos y ámbitos (local de dominio, global, universal) para controlar el acceso a recursos específicos, como impresoras departamentales o carpetas de tarifas confidenciales.

R)Aquí hay una representación gráfica de como va a ser la estructura de acceso de los trbajadores del hotel.

 
<img width="1920" height="1080" alt="Estructura de comando del hotel" src="https://github.com/user-attachments/assets/c6322025-2a58-4f23-8f07-d2764e11dd0a" />

Tarea 5: Implementación de Grupos Funcionales (CE e)
• Criterio asociado: Se han configurado y gestionado grupos.
• Tarea: Configurar y gestionar los grupos de seguridad principales basándose en la Tarea 4. Por ejemplo, crear los grupos "GR_Recepción_Diurna" y "GR_Administración_TI". Esta tarea asegura que solo los miembros autorizados puedan acceder a los recursos de red necesarios.

R) He creado distintos grupos con distintos propositos y asignado a los usurios correctos a cada uno de estos. ( Admon, Servicio al cliente diurno, servicio al cliente nocturno, mantenimiento del hotel diurno/nocturno, personal de seguridad, alimentacion diurna/nocturna, recursos humanos, etc...)

<img width="428" height="479" alt="Admon-jesus" src="https://github.com/user-attachments/assets/7564ef63-3611-4027-b459-54f5436d5ba0" />



<img width="422" height="476" alt="miembros-del-servicio-del-hotel" src="https://github.com/user-attachments/assets/d716e155-565d-406f-ae79-60e8d154db08" />

Tarea 6: Asignación de Permisos (CE f)
• Criterio asociado: Se ha gestionado la pertenencia de usuarios a grupos.
• Tarea: Gestionar la pertenencia de usuarios a grupos. Asignar a todos los empleados creados en la Tarea 1 a los grupos funcionales apropiados creados en la Tarea 5. Se debe asegurar, por ejemplo, que solo los miembros de "GR_Administración_TI" tengan acceso al servidor de copias de seguridad.

R) Los usuarios del grupo de admon tienen mas acceso a las herramientas administrativas que los del grupo servicio al cliente, cada uno tiene progresivamente menos permisos y acceso a información con el controoler y grupo admon con mas permisos que el resto.

<img width="1402" height="890" alt="image" src="https://github.com/user-attachments/assets/aeca8ce5-83de-4997-9390-2c9414b075d0" />

Tarea 7: Auditoría de Seguridad Inicial (CE g)
• Criterio asociado: Se han identificado las características de usuarios y grupos predeterminados y especiales.
• Tarea: Realizar una auditoría inicial de seguridad. Esto implica identificar las características de usuarios y grupos predeterminados y especiales (como Administrator, Guest o Domain Admins) y documentar su estado de seguridad (por ejemplo, asegurando que la cuenta Guest esté deshabilitada y que la cuenta Administrator tenga un nombre de usuario renombrado por seguridad).
 
Tarea 8: Movilidad y Despliegue de Perfiles (CE h)
• Criterio asociado: Se han planificado perfiles móviles de usuarios.
• Tarea: Planificar perfiles móviles de usuarios para el equipo de Dirección y Mantenimiento. Dado que estos empleados rotan entre diferentes ubicaciones (oficinas, almacenes, zonas comunes) y utilizan distintos equipos, se debe diseñar la estructura de carpetas compartidas y la configuración del servidor que soporten la replicación de sus configuraciones.

R)No se donde puedo encontrar el menu para inicar a realizar esta actividad.
 
Tarea 9: Aplicación de Herramientas de Administración (CE i)
• Criterio asociado: Se han utilizado herramientas para la administración de usuarios y grupos, incluidas en el sistema operativo en red.
• Tarea: Para completar todas las tareas anteriores (T1 a T8), el equipo deberá utilizar las herramientas de administración de usuarios y grupos, incluidas en el sistema operativo en red. Esto requiere demostrar la competencia en el uso eficiente de herramientas como Consola de Administración de Usuarios y Equipos de Active Directory o comandos de shell para la gestión masiva de las identidades del hotel.
