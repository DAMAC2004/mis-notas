

# Administracion de servidores

**Porfesor:** Humberto Javier Guirao Martinez

**Objetivo:** `` 

**Temario:** 

- 1 Introducción a la administración de servidores.
  - 1.1. Conceptos, clasificación y administración de servidores.
  - 1.2. Los Servidores en la Red de Computadoras.

- 2 Instalación de un sistema operativo para un servidor.
  - 2.1. Definición de Hardware del Servidor.
  - 2.2. Selección del Sistema Operativo.
  - 2.3. Particionado y sistemas de archivos.
  - 2.4. Instalación de sistemas operativos (Windows, Linux, u otros).
  - 2.5. Configuración del Sistema Operativo y sus recursos (interfaz, acceso, protocolos, hardware de red, video, sonido, administración remota y paquetes de aplicaciones)

- 3 Gestión del servidor. 
  - 3.1 Administración de usuarios
    - 3.1.1. Introducción.
    - 3.1.2. Administración de cuentas de usuario (creación, administración y borrado).
    - 3.1.3. Acceso a usuarios en archivos.
    - 3.1.4. Restricción de acceso a usuarios en archivos
  - 3.2 Administración de archivos
    - 3.2.1. Introducción a los permisos de archivos.
    - 3.2.2. Tipos de archivos (directorios, ligas).
    - 3.2.3. Estructura de archivos del sistema.
    - 3.2.4. Directorios de trabajo de los usuarios.
    - 3.2.5. Seguridad en los sistemas de archivos.
    - 3.2.6. Respaldo y recuperación de datos.
      - 3.2.6.1. Introducción a los fundamentos de respaldo.
      - 3.2.6.2. Respaldo y desmontaje del sistema de archivos. 
    - 3.2.7. Políticas de respaldo.
  - 3.3 Administración de dispositivos
    - 3.3.1. Impresoras.
      - 3.3.1.1. Tipos de impresoras (IP, compartidas).
      - 3.3.1.2. Colas de Impresión.
      - 3.3.1.3. Servidores de Impresión (por Hardware y Software).
    - 3.3.2. NAS.
    - 3.3.3. RAID.
    - 3.3.4. Instalaciones desatendidas.

- 4 Servidores DNS, Web, FTP, DHCP, Correos.
  - 4.1. Concepto.
  - 4.2. Instalación y configuración de Servidores Web. FTP, DHCP, correos, etc.
  - 4.3. Administración de Servidores Web, FTP, DHCP, Correos

- 5 Virtualización 5.1 Conceptos básicos de virtualización.
  - 5.2 Software para virtualizar
  - 5.3 Tipos de visualización
  - 5.4 Gestión de la visualización (red, compartir archivos y recursos). 

**Fechas de Evaluación:**

- `02 de septiembre`
- `15 de octubre`
- `29 de octubre`
- `19 de noviembre`
- `01 de diciembre`
---

## Clases

### clase 2025-08-18

#### Que es un servidor?(fue una lluvia de ideas)

#### Conceptos basicos

- Un servidor proporciona servicios o recursos de otros equipos en una res
- puede ser hardware dedicado
- carateristicas
  - alta disponibilidad
  - seguridad
  - escalabilidad
- Ejemplo:
  - un servidor wen responde a solicitudes de navegadores

#### Clasificacion de servidores por funcion 

- Servidor de archivos
  - gestiona archivos compartidos
  - Ejemplos:
- Servidor de impresion
  - Administra impresoras en red
  - Ejemplos:
- servidor web
  - Aloja sitios web
  - Ejemplos:
    - apache
- Servidor de Base de Datos
  - Maneja base de datos
  - Ejemplos:
    - mysql
- Servidor de correo
  - Gestiona correos
- Servidor de aplicaciones
  - Ejecuta software empresarial

#### Ubicacion y Arquitecturas

Algunos se identifican por su Ubicacion y arquitectura

- Aquitectura
  - Fisico (bare-metal)
  - Virtual (VMware, Hyper-V)
  - en la Nube (AWS, Azure)
- Ubicacion
  - on-premise
  - cloud
  - hibrido
  
#### Administracion de Servidores

- INstalacion y configuracion de sistemas
- Monitoreo de recursos como cpu o ram
- Seguridad, actualizzacion y firewalls
- gestion de usuarios y permisos
- respaldo y recuperacion de datos
- automatizacion de herramientas como ansible

#### Conclusion

Los servidores son escenciales en redes modernas, para cosas como la clasificacion por que esta ayuda a entender los usos de esta tecnologia, la administracion garantiza esto y mas

####  actividad

| Característica               | **Servidor en Hardware dedicado**                                                     | **Servidor en Software dedicado (Virtualizado / Nube)**                                                                                                                                                 |
| ---------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Infraestructura**          | Servidor físico exclusivo.                                                            | Servidor virtual que se ejecuta sobre un host físico compartido.                                                                                                                                        |
| **Ejemplos**                 | Un servidor Dell PowerEdge, HP ProLiant, IBM System X dedicado solo a bases de datos. | **Virtualización tradicional:** VMware ESXi, Hyper-V, Proxmox, VirtualBox. <br> **Contenedorización:** Docker, Kubernetes. <br> **Nube:** AWS EC2, Google Cloud Compute Engine, Azure Virtual Machines. |
| **Costo inicial**            | Alto: compra de hardware, instalación y mantenimiento físico.                         | Bajo/medio: pago por uso (nube) o menor inversión en hardware (máquinas virtuales o contenedores).                                                                                                      |
| **Escalabilidad**            | Limitada: depende del hardware físico.                                                | Muy alta: creación rápida de VMs o contenedores; en la nube se puede escalar bajo demanda.                                                                                                              |
| **Mantenimiento**            | Incluye piezas físicas (RAM, discos, fuente de poder, etc.).                          | El hardware lo maneja el proveedor o el host; el administrador se centra en software.                                                                                                                   |
| **Rendimiento**              | Constante y totalmente dedicado.                                                      | Puede variar según la carga del host o las políticas del proveedor.                                                                                                                                     |
| **Disponibilidad**           | Depende del hardware: una falla física puede detener todo.                            | Alta: la nube y la virtualización permiten migraciones en caliente, redundancia y balanceo.                                                                                                             |
| **Seguridad**                | Control total, ya que el servidor está en las instalaciones.                          | Depende del aislamiento del hipervisor o contenedor; se confía también en el proveedor de nube.                                                                                                         |
| **Flexibilidad**             | Baja: difícil de mover o ampliar.                                                     | Alta: despliegue rápido de servidores, clonación y balanceo de carga.                                                                                                                                   |
| **Tiempo de implementación** | Lento: instalación física y configuración desde cero.                                 | Rápido: levantar una VM, un contenedor o una instancia en la nube toma minutos.                                                                                                                         |
| **Uso típico**               | Bancos, gobiernos, empresas grandes con alta seguridad y control de datos.            | Startups, desarrolladores, empresas que buscan flexibilidad y reducción de costos.                                                                                                                      |

| Característica               | Servidor en **Hardware dedicado**                                             | Servidor en **Software dedicado** (Virtualizado / Nube)                                            |
| ---------------------------- | ----------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Infraestructura**          | Requiere un servidor físico exclusivo.                                        | Se ejecuta sobre un servidor físico, pero compartiendo recursos con otros mediante virtualización. |
| **Costo inicial**            | Alto: compra de hardware, instalación y mantenimiento físico.                 | Bajo/medio: pago por uso (nube) o menor inversión en hardware (máquinas virtuales).                |
| **Escalabilidad**            | Limitada: depende de la capacidad física del servidor.                        | Alta: se pueden crear más máquinas virtuales o contratar más recursos en la nube rápidamente.      |
| **Mantenimiento**            | Administrador debe encargarse de hardware (discos, RAM, red, etc.).           | Se centra en software; el hardware es gestionado por el proveedor de nube o el hipervisor.         |
| **Rendimiento**              | Alto y predecible: los recursos son 100% dedicados.                           | Puede variar según la carga del host o políticas del proveedor.                                    |
| **Disponibilidad**           | Si falla el hardware, todo el servidor se detiene.                            | Mayor redundancia: la nube permite replicación y migración en caliente.                            |
| **Seguridad**                | Mayor control físico y lógico sobre el servidor.                              | Depende de la configuración y del proveedor; riesgos compartidos en entornos multiusuario.         |
| **Flexibilidad**             | Difícil de mover o adaptar a nuevas necesidades.                              | Muy flexible: permite migración entre hosts, ampliación dinámica de recursos y despliegue rápido.  |
| **Tiempo de implementación** | Lento: adquisición, instalación y configuración de hardware.                  | Rápido: una VM o instancia en la nube se levanta en minutos.                                       |
| **Uso típico**               | Empresas que necesitan control total, alta seguridad y rendimiento constante. | Empresas que requieren flexibilidad, reducción de costos y escalabilidad.                          |


### clase 2025-08-20

#### Actividad: Concepto de servidor y tipos de servidor en base a su arquitectura

**Conceptos**
- Servidor en la nube
	- ES un entorno virtual que se corre sobre un equipo fisico gestionado por un 3ro, es escalable pero corre riesgo por si hackar al que esta haciendo el hosting
- Servidor de base de datos
	- Gestiona y administra el almacenamiento, consultas y transacciones de datos
- Servidor DNS
	- Traduce IP a texto de dominio
- Servidor de Aplicaciones
	- Trabaja entre el cliente y servidor, en la capa de negocio y proporciona la ejecucion de servicios

ensayo del tema 1.2
- introduccion
- desarrollo 
- conclucion
- bibliografia

---

## Clase 2025-08-27
Analisis
propuesta de solucion
- Control de permisos mediante servidor de impresion
- COnfigurar la impreora en un servidor central
Resultado
- todos pueden ver la impresora, pero solo los lideres pueden usarlo
Justificacion
- Centralizacion de recursos
- Escalabilidad
- Seguridad
- Administracion eficiente
- Alineado a la problematica

caso 4

Justificacion
- Eficiencia al asignar a los lideres rl privilegio de imprimir
- Seguridad al proteger los datos
- Reducir gastos en todo lo que implique la impresora
Solucion:
- La gestion de permisos de impresion implica establecer reglas para comtrolar la gston de la impresora
Configuracion:
- Acceder al panel de control en redes y configuracion de uso compartid
- activar opciones de compartido
FLujo de trabajo:
- Identificador de Operadores
Conclusion:
- La restriccion de impresora esta justificada ya que logra mejorar la eficiencia y establecer un sistema seguro y auditable

## Clase 2025-09-09

Investigar sobre los sistemas operativos mas utilzados en las empresas y crear una tabla comparativa ventajas, desventajas ,caracteristicas de los sitemas operativos

## Clase 2025-09-22

Exposicion - Tema 2.2 Seleccion del sistema Operativo
- Rene
- Roberto
- Geovanni
- Jairo
- Yahir

Un SO se encarga de gestionar el hardware de la maquina para realizar las tareas del equipo, lo que implica que segun las necesidades hay que elegir uno u otro SO, para ello existen ciertos criterios
- Estabilidad y seguridad
- Compatibilidad
- Facilidad de instalacion
- escalabilidad y gestion de carga
- Soporte y comunidad
- Costos

SO mas comunes
- linux
	- Ventajas
		- Codigo aberto
		- Seguro
		- Altamente cofigurable
	- Usos
		- Servidores web
		- Bases de datos
		- aplicaciones
- Windows server
	- Ventajas
		- Integracion con microsfot
		- facilidad de uso
	- Usos
		- Active Directory
		- archivos
		- impresion
- Red hat interprise(Fedora, Manracket, Debian
	- Ventajas
		- Estabiliad
		- soporte corporativo
	- Usos
		- Aplicaciones empresariales
- Unix
	- Ventajas
		- Escalable
		- Confiable
		- Seguro
	- Usos
		- Aplicaciones de mision critica

Tipos de sistemas operativos para servidores
- Linux
	- Seguro, estable, muy utilizado en servidores web
- Windows Server
	- Fail de usar, buena integracion con 
- Unix y derivados
	- Confiable y escalables pero menos comunes
- Otros
	- IBM ajax, oracle linux, netware

Factores adicionales
- Tipo de servidor
- Requerimientos especificos del negocio
- Habilidades del personal tecnico de la empresa
- Politicas de seguridad y normativas vigentes

## 2.3 Particionado y sistemas de archivos

Que es el particionado?

- Es una segmentacion de un disco duro fisico el cual se divide en varias parte

Tipos

- Particiones primarias
	- Instalascion de SO
- Particiones Logica
- Particiones extendidas

Que es un sistema de archivos


Tipos
- FAT
	- los sistemas File Allocation Table
	- Son sistemas de archivos antiguos
	- Compatibilidad Universal
	- Facilidad de Uso
	- Dispositivos Pequeños
	- Sin registro de cambios
	- Rendimiento puede verse afectado si tiene muchos archivos
	- Falta de soporte 
- FAT32
	- Es un sistemas 
	- Transferencia entre plataformas
	- Sencillez
	- Ideal para unidades pequeñas
	- Tiene permisos muy altos para la manipulacion de archivos
	- Fragmentacion
	- Capacidad de participacion limitada a 16 gb antes de empezar las fallas de rendimiento
- NFTS
	- Token No Fungible
	- Mayor seguridad
	- Soporte para archivos grandes
	- Fiabilidad
	- Compatibilidad limitada
	- No es compatible con dispositivos antiguos
	- Puede fragmentarse 
- Ext4 
	- Foruth extended Filesystem
		- Mas avazado que fat32
		- Alto rendimiento y eficiencia
		- Gran escalabilidad
		- Retrocompatibilidad
		- Falta de Funciones avanzadas
		- Fragmentacion
		- Soporte entre plataformas limitado
		- Se considera solo para linux


## Clase 2025-10-06

### Instalacion de sistemas operativos

Carateristicas de los SO para cervidores
- Gestion de Recursos
- Estabilidad y seguridad
- Manejo de cargas

Windows server y linux en sus multiples distribuciones dominan el mercado de SO para servidores

Requisitos y preparacion previa
- Es importante revidar el hardware del equipo
- Tener en cuenta si se intalara sobre el hardware o en maquinas virtuales

Intalacion Windows Server
- Paso 1: preparar ISO o medios de instalacion
- Paso 2: Configurar BIOS para el arracador sea la usb
- Paso 3: Seleccion estadar del intalador
- Paso 4: Particionado
- Paso 5: Configurar la cuenta de adminitrador local y contraseña segura
- Paso 6 Intalar roles y carateristicas
- Paso 7 Actualizar windows update
- Paso 8: Activar el firewall

Ubuntu server
- Paso 1: Iniciar medios de instalacion
- Paso 2: Confirguracion de Red
- Paso 5: Configurar cuenta de administrador local
- Paso 6: Configurar roles y carateristicas
- Paso 7: Actualizar controladores

Diferencias Windows y linux

- Linux posee mas seguirdad
- Linux es de uso libre sin licencia
- Windows server tiene una GUI
- Windows puede llegar a ser mas comodo

### 2.5 Configuracion del sistema operativo y sus recursos

El sistema operativo es el componenete esencial que permite la interaccion entre el usuario y el hardware de un equipo de computo

Interfaz del sistema operativo
- GUI
- CLI

Acceso y seguridad
- Creacio de usuarios y contrases
- Definicion de permisos y privilegios
- Configuracion de politicas de inicio de secion
- Autenticacacion loca y en red

Protocolos y conectividad
- Soporte para TCP/IP, DHCP y DNS
- Configuracion de IP estatica o dinamica
- Ajustes de VPN y firewall
- Protocolos de comparticion de archivos
	- SMB
	- NFS
	- FTP

Hardware de red
- Instalacion y configuracion de adaptadores de red
- Controles y utilidades de red
- Comporobacion de conectividad o ping
- Monitoreo de ancho de banda y uso de red

Administracion remota

Capacidad de controlar dispositivos desde diferente ubicacion a la maquina controlada

- Acceso remoto a traves de RDP, SSH y VNC
- Herramientas de administracion
	- Powershell remoto
	- TeamViewer
	- AnyDesk
- Gestion de permisos para conexiones remotas
- Monitoreo y soporte a distancia

Paquetes de aplicaciones
- Intalacion y desistalacion de software
- Uso de gestores de paquetes
	- Apt
	- yay
- Administracion de actulizaciones de programas
- Compatibilidad con ditintos formatos de instalacion

Importancia

La correcta configuracion del sistema operativo y sus recursos es fundamental por que garantza la seguirdad del equipo


---
## Glosario

IIS: Internet Information Services, es un servidor web desarrollado por Microsoft para sistemas operativos Windows. Permite alojar sitios web, aplicaciones y servicios web, ofreciendo funcionalidades para la administración y seguridad de estos recursos.
