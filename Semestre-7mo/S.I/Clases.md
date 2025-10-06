# Seguridad Informática

**Profesor:** `Romel Acosta Felix`

"Si no sabes yo te ense~no,  su no puede yo te ayudo y si no quieres, pues mucho gusto"

**Objetivo:** `Desarrlloar planes de seguridad basados en normas y estandares internacionales que puedan asegurar un seguridad maxima en la medida de lo posible`

**Temario**
1. Introducción a la Seguridad Informática. 
	1. El valor de la información. 
	2. Definición de seguridad informática. 
	3. Visión Global de la Seguridad Informática 
	4. Objetivos de la seguridad informática. 
	5. Posibles riesgos. 
	6. Técnicas de aseguramiento del sistema. 
	7. Principales amenazas por internet. 
2. Directrices de Seguridad Informática. 
	1. Criptografía. 
	2. Esteganografía. 
	3. Certificados y Firmas Digitales. 
	4. Hacking ético. 
	5. Cómputo forense.
	6. IDS y IPS. 
	7. Seguridad en Linux 
	8. Seguridad en Wi-Fi. 
3. Firewalls como Herramientas de Seguridad. 
	1. Tipos de firewall: de software y de hardware. 
		1. Firewall de capas inferiores. 
		2. Firewall de capa de aplicación. 
		3. Firewall personal. 
	2. Ventajas de un firewall. 
	3. Limitaciones de un firewall. 
	4. Políticas del firewall. 
	5. Enlaces externos. 
4. Norma ISO 27001:2005. 
	1. Evolución de la familia ISO 27000. 
	2. Objetivos de control y controles. 
		1. Política de seguridad. 
		2. Organización para la seguridad de la información. 
		3. Administración de activos. 
		4. Seguridad de los recursos humanos. 
		5. Seguridad física y ambiental. 
		6. Gestión de las comunicaciones y operaciones. 
		7. Control de accesos. 
		8. Adquisición, desarrollo y mantenimiento de sistemas de información. 
		9. Gestión de incidentes de la seguridad de la información. 
		10. Gestión de la continuidad del negocio. 
		11. Cumplimiento.

**Criterios de evaluacion**

| **Criterios de evaluación**          | valor |
|--------------------------------------|-------|
| Examen                               | 30    |
| Analisis o ensayo                    | 20    |
| Mapa mental                          | 20    |
| Mapa conceptual                      | 20    |
| Participacion                        | 10    |



---

## Clase 2025-08-19

### Cosas a investigar

Investigar el valor de la información
Definición de seguridad informatica
Vision global de la seguridad informatica

## Clase  2025-08-26

1.1

La informacion es un conjunto de datos oorganizados y procesados qye tienene significado y utilidad para quien los recibe

Los datos por si mismo son simples hechos o cifras

la informacion como un recurso

Hoy en dia la informacion **es considerada un activo estrategico**, comparable con los recursos materiales, financieros o humanos de una organizacion
- Permite tomar decisiones acertadas
- aporta ventaja competitiva
- tiene valor economico y social

Carateristicas del valor de la informacion

- Confidencias
	- solo para personal autorizado
- Integra
	- sin modificaciones y completa
- Disponible
	- Accesible cuando se necesite
- Autenticidad
	- Debe poder verificarse que la informacion es confiable
- Valor temporal
	- durante que periodo es valioso

amenzas al valor de la informacion
- Acceso no autorizado - Robo de datos y espionaje
- Perdida o devolucion - fallos tecnicos, errores humanos o desastres
- alteracion maliciosa - modificaciones de archivos y fraudes
- Divulgacion indebida - filtraciones de datos privados o confidenciales

Importancia de proteger la informacion

- Evitar fraudes, robo de identidad y espionaje
- Garatizar la continuidad de operaciones
- Mantener la confianza de clientes
- Cumplir con leyes de proteccion de datos y normativas de seguridad

1.2 Definicio de seguridad informatica

La seguridad informatica es el conjunto de medidas, tecnicas y practucas destinadas a proteger la informacion, los sitemas y los recurss tecnologicas frente a amenazas riesgos y ataques

su propositos
- Se mantega la informacion segura frente a accesos no autorizados
- que los datos no sean alterados de manera indebida
- que esten disponibles para los usuarios y que sean legitimos

1.3 vision global de la seguridad informatica

1. Personas
	1. Los usuarios son el eslabon mas debil,
	2. requieren capacitacion y consiencia del entorno de seguridad
2. tecnologias
	1. Computadoras, redes, servidores, dispositivos moviles y la nube
	2. Proteccion con antiviruz firewalls cifrado y copias de seguridad
3. procesos y normativas
	1. Establecer politicas de seguridad y protocolos de acceso
	2. Cumplir con leyes de proteccion de datos
4. amenzas globales
	1. Malware
	2. Hacker maliciosos
	3. Robo de identidad y fraudes eletronicos
	4. ataques a infraestructruras criticas

1.4 Objetivos de la seguridad informática. 

el objetivo de la seguridad informatica es pues protejer datos, pero para verlo de una menera mas simple se dedica a que la informacion cumpla con los siguientes puntos conocidos como CIA

- Cofidencial
	- solo los usuarios elegidos deben poder acceder a la informacion
- integridad
	- los datos deben mantenerse completos, correctos y sin alteraciones
- disponibilidad
	- se debe asegurar que los servicios siempre deben estar accesibles cuando se requiera

algunos autores hablan de agregar

Autenticidad  - Verifica la identidad del sistema y el usuario
no repudio    - Evita que otros nieguen la accion o inaccion en un proceso

1.5 Posibles riesgos. 

hoy en dia respecto a la seguridad informatica, cualquier informacion en la web es pirateable o como minimo blanco de ataque, pero eso no implica que debas dejarla disponible para cualquiera sin embargo siempre va a haber amenzas, asi que lo mejor es conocer dichas amenzas y saber que hacer en dichas situaciones, todo usualmente va nacer cuando algo de los 3 pilares principales flaquea, es decir la confidencialidad, integridad y disponibilidad, esto se puede deber a lo siguiente:

- Error humano
	- mala configuracion de la privacidad
	- perdida de contraseña
	- descuido al manejar datos
- Por Ataques Externos
	- hackers
	- malwares
	- phishing
-  Fallas de hardware y/o Software
	- daños de discos
	- sistemas operativos mal diseñados o corruptos, entra el programa mal diseño
- Desastres naturales
	- Incendios, inundaciones, sismos que afecten los equipos

1.6 Técnicas de aseguramiento del sistema. 

hay varias tecnicas, una de ellas es la siguiente:

- Contrase~nas seguras
	- son medidadas y procedimientos deise~nados para protejer los sistemas de informacion complejas y cambios periodicos
- Control de Accesos
	- Aolo usarios con acceso a ciertos recursos
- Antivirus y antimalware
	- Deteccion y elimnacion de programas dañinos
- tokens
	- One Use Password
- Copias de seguridad
	- raespaldo de informacion regularmente para evitar perdida de datos
- Actualizacion de software
	- Mantener sistemas operativos y programas al dia para evitar vulnerabilidades
- Cifrado de datos
	- Protege la informacion durante su almacenamiento o transmicion
 1.7 Principales amenazas por internet. 

- phishing
	- Mensajes falsos que buscam obtener informacion personal o confidencial
- malware
	- viruz
	- troyano
	- rasonware
- Robo de Identidad
	- Usurpacion de datos personales para cometer fraudes
- DDoS
	- Inundacion de peticiones de servicios s un servidor
- Spyware
	- Recopilacion de datos sin concentimiento

## Clase 2025-09-04

1.1



1.2 



1.3

## Clase 2025-09-18

unidad 2

vimos la pelicula llamada codigo enigma con el fin de ver la importancia dle cifrado de datos

## Clase 2025-09-23

Una clase donde en base a la pelicula anterior que vimos, ahora estaremos conociendo diferentes tipos de cifrado de datos

vimos los siguientes:

### cifrado cesar

que es reasignacion de letras en base a una clave

abcdefghijklmnopqrstuvwxyz

a cada uno se le asigna un numero y en base a la clave se recorre

por ejemplo

HOLA MUNDO 
en cifrado cesar 3 seria -> KRÑD OXPGR

### Polivio o Bifido

#### Variante tipo 1

Consiste en colocar expto la I en un recuadro de (5 x 5), ejemplo


|x|1|2|3|4  |5|
|-|-|-|-|---|-|
|1|A|B|C|D  |E|
|2|F|G|H|I/J|K|
|3|L|M|N|O  |P|
|4|Q|R|S|T  |U|
|5|V|W|X|Y  |Z|

Algo como

`HELLO WORLD`  su equivalente seria `23 15 31 31 34 52 34 52 31 14`

una condicion de este metodo de encriptacion es que de preferencia se deben usar palabras que no repitan letras

#### Variante tipo 2

Existe una variante de este metodo que se le conoce como variante, en este caso se toma una palabra clave que no repita letras, aunque para este caso obviaremos eso ultimo para que tomemos ejemplo, sera con `HELLO WORLD` la palabra ultilizada para el cifrado variante, pero vamos a adaptarla, encontes seria `HELO WRD`, ahora asignarle puestos nuevos a la tabla

|x|1|2|3  |4|5|
|-|-|-|---|-|-|
|1|H|E|L  |O|W|
|2|R|D|A  |B|C|
|3|F|G|I/J|K|M|
|4|N|P|Q  |S|T|
|5|U|V  |X|Y|Z|

Aqui la cosa cambia ahora el `HELLO WORLD` seria algo como -> `11 12 13 13 15 14 21 13 22`

#### Variante tipo 3

en este caso se toma la variante tipo 1 como base(Aunque tambien se puede tomar la variante tipo 2) y tomamos una palabra clave como por ejemplo `HELLO WORLD`, de preferencia algo que no repita letras, para este caso hay que transformar la palabra, seria `HELO WRD`, ahora tomamos esa palabra y la ciframos

|x|1|2|3|4  |5|
|-|-|-|-|---|-|
|1|A|B|C|D  |E|
|2|F|G|H|I/J|K|
|3|L|M|N|O  |P|
|4|Q|R|S|T  |U|
|5|V|W|X|Y  |Z|

seria algo como -> `23 15 31 34 52 42 14` 

apartir de ese codigo lo juntamos y dividimos a la mitad, terminaria algo asi:

`2315313`
`4524214`

ahora juntamos los numeros segun su indice en cada fila y el resultado seria:

`24 35 12 54 32 11 34`

sacamos cual seria el significado de esa clave y ese seria la clave final de cifrado, en este caso seria:

`I P B Y M A O`

Para esto terminamos con que la transformación completa seria
1. `HELLO WORLD`
2. `HELO WRD`
3. `23 15 31 34 52 45 14`
4. `2315313` - `4524214`
5. `24 35 12 54 32 11 34`
6. `I P B Y M A O`

Nuestra tabla final seria esta:

|x|1|2|3|4  |5|
|-|-|-|-|---|-|
|1|I|P|B|Y  |M|
|2|A|O|C|D  |E|
|3|F|G|H|J/K|L|
|4|N|Q|R  |S|T|
|5|U|V|W  |X|Z|

un mensaje con esta tabla seria algo como:

1. `AMIGO MIO`
2. `21 51 11 32 22 52 11 22`

### Cifrado Vigenere

Se prupuso utilizar 2 afabetos alternando entre codificacion

usa 26 simbolos del alfabeto, no se considera la ñ

Se usa asi

hay 2 columnas, la columna de arriba es el texto de entrada, y la columna de abajo es el texto de la plabra clave, la union de las coincidencias es el mensaje cifrado

![[Cuadreo vigenere.png]]

por ejemplo

mensaje: Seguridad informatica
clave: python

primero hacemos las equivalencias y luego ciframos en base a la tabla

|Palabra clave   |P|Y|T|H|O|N|P|Y|T|H|O|N|P|Y|T|H|O|N|P|Y|
|----------------|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Mensaje         |S|E|G|U|R|I|D|A|D|I|N|F|O|R|M|A|T|I|C|A|
|Mensaje Cifrado |H|C|Z|B|F|V|S|Y|W|P|B|S|D|P|F|H|H|V|R|Y|

---

Que es la criptografia

es la ciencia que estudia las tecnicas para proteger la informacion mediante la transformacion de los datos

dentro de la criptografia para las claves de cifrado hay 2
- Simetrica
	- Palabra clave que usa la misma palabra para cifrar y decifrar que se llama AES
- Asimetrica
	- Aqui usan 2 diferentes palabras claves, una clave publica y una clave privada RSA

Estelanografia
- Ocultar Texto en una imagen, texto, audio y video

diferencias

- Criptografia: Oculta la informacio
- Estelanografia: Oculta el contenido


Certificados digitales
- Son documentos electornicos que validan una entidad en internet validado por un organismo 

Llave electronica
- Mecanismo criptografico que asegura que un documento no ha sido alterado

Documento electronico
- Para correo electronico

Equipo 5

