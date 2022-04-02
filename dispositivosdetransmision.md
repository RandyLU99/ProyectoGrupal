![Image text](/Imagenes/CaratulaDisp.jpg)


## Conceptos básicos de Redes

![Image text](/Imagenes/concepto_basico_redes.jpg)

Es un sistema de comunicación que se da entre distintos equipos para poder realizar una comunicación eficiente, rápida y precisa, para la transmisión de datos de un ordenador a otro, realizando entonces, un intercambio de Información.
Esta conexión puede ser realizada de manera directa, utilizando cables de todo tipo o bien mediante Ondas Electromagnéticas.
La red debe estar conformada por:
- Terminal; Punto de partida de la comunicación
- Nodo; Medio por el cual se permite la conexión
- Medio de Transmisión; Es la conexión llevada a cabo entre dichos equipos.

## Tipos de redes según su alcance y conexión

Al margen de que puedan hacerse por cable estructurado, o por vía inalámbrica, las redes pueden dividirse por su alcance o cobertura. Lógicamente, cuanto mayor sea el espacio que queremos abarcar, más difícil y costosa puede resultar la instalación de cables (de hecho, la instalación de algunas de estas redes serían absurdas e impensables para una gran mayoría de las empresas). 

- PAN: Red de área personal. Interconexión de dispositivos en el entorno del usuario, con alcance se escasos metros.

- LAN: Red de área local. Interconexión de varios dispositivos en el entorno de un edificio, con un alcance limitado por una longitud máxima de los cables o con alcance de antenas inalámbricas.

- MAN: Red de área metropolitana. Red formada por un conjunto de redes LAN que interconectan equipos en el entorno de un municipio.

- WAN: Red de área amplia. Interconecta equipos en un entorno geográfico muy amplio, como un país o un continente





Parte Randy 

## Redes WAN

![Image text](/Imagenes/Wan.jpg)

<p style='text-align: justify;'> Una red de área amplia, o WAN (Wide Area Network en inglés), es una red de computadoras que une e interconecta varias redes de ámbito geográfico menor, por ejemplo, redes de área local, aunque sus miembros no estén todos en una misma ubicación física. Muchas WAN son construidas por organizaciones o empresas para su uso privado, otras son instaladas por los proveedores de Internet (ISP) para proveer conexión a sus clientes. 

<p style='text-align: justify;'>Como una red WAN no conecta ordenadores individuales, sino redes enteras, la tecnología utilizada difiere de los otros tipos de red. Emplea otros protocolos de transmisión y conceptos de dirección.

<p style='text-align: justify;'>Las redes WAN utilizan técnicas y protocolos de transmisión de las capas uno a tres del modelo de referencia OSI. De este modo, una WAN funciona en la capa física (capa 1), la capa de enlace (capa 2) y la capa de red (capa 3).
Para la transmisión de datos se emplean también las siguientes tecnologías: 

-	X.25 (tecnología más antigua, desde los años 70)
-	Modo de transferencia asíncrono (ATM) (tecnología antigua)
-	Multiprotocol Label Switching (IP/MPLS)
-	Jerarquía digital presiócrona (PDH)
-	Jerarquía digital síncrona (SDH)
-	Ethernet

<p style='text-align: justify;'>Los medios de transmisión físicos utilizados son los cables de cobre y fibra óptica, así como los enlaces inalámbricos. Los cables de fibra óptica son especialmente adecuados para conexiones a larga distancia sobre tierra y agua. Los avances más recientes son las vías de transmisión de datos de banda ancha por satélite, que se pueden establecer con relativa rapidez. En la práctica, se suele utilizar una combinación de varios medios de transmisión distintos. Con los llamados convertidores de medios, se pueden interconectar distintos tipos de cables. En los grandes nodos de Internet hay puntos de intercambio especiales interconectados, donde a menudo hay más de cien redes interconectadas para permitir un intercambio de datos eficiente. Los repetidores se encargan de que los paquetes de datos no pierdan información, incluso a grandes distancias.

# Tipos de Conexión 

Existen varios tipos de red WAN, y tres de ellos se agrupan bajo la clasificación de red conmutada (en física, la conmutación consiste en el cambio del destino de una señal o de una corriente eléctrica):

## Por Circuitos
Son redes de marcación de (dial-up), como la red de telefonía básica (RTB) y RDSI. Durante el tiempo que dura la llamada, el ancho de banda es dedicado.

## Por Mensaje
<p style='text-align: justify;'> Sus conmutadores suelen ser ordenadores que cumplen la tarea de aceptar el tráfico de cada terminal que se encuentre conectado a ellas. Dichos equipos evalúan la dirección que se encuentra en la cabecera de los mensajes y pueden almacenarla para utilizarla más adelante. Cabe mencionar que también es posible borrar, redirigir y responder los mensajes en forma automática.

## Por Paquetes

<p style='text-align: justify;'> Se fracciona cada mensaje enviado por los usuarios y se transforman en un número de pequeñas partes denominadas paquetes, que se vuelven a unir una vez llegan al equipo de destino, para reconstruir los datos iniciales. Dichos paquetes se mueven por la red independientemente, y esto repercute positivamente en el tráfico, además de facilitar la corrección de errores, ya que en caso de fallos solo se deberán reenviar las partes afectadas. El ancho de banda es compartido entre todos los usuarios que usan la red.

## Características de las redes WAN

A fin de conocer mejor el funcionamiento de este concepto, os comentamos las principales características de las redes WAN:

-	<p style='text-align: justify;'> Este sistema posee máquinas dedicadas por completo a la ejecución de diferentes programas de usuario, también conocidos como hosts.

-	<p style='text-align: justify;'> Una sub-red a la que se conectan diferentes hosts, nombre que reciben los enrutadores.

-	División entre líneas de transmisión y elementos de conmutación.

-	<p style='text-align: justify;'> Al tratarse de un sistema de interconexión de equipos informáticos dispersos a nivel geográfico, el sistema de conexión que alimenta estas redes suele involucrar generalmente a diferentes redes públicas de transmisión de datos

-	También contienen enlaces satelitales

## Ventajas y desventajas

<p style='text-align: justify;'> La implementación de esta estructura de red, facilita bastante el trabajo entre puntos distante que necesitan tener cierta sincronía; pero a su vez, tiene ciertas desventajas.


## Ventajas
-	Se tiene un canal exclusivo de información independientemente de la posición geográfica.
-	<p style='text-align: justify;'> Actualmente se tienen varios medios de transmisión, lo que hace posible que estas conexiones de gran escala puedan funcionar de forma óptima. Además de que ya se tiene la tecnología necesaria para que estas redes alcancen una velocidad en el orden de los Gigabits por segundo.

## Desventajas

-	<p style='text-align: justify;'> La seguridad de estas redes no es un punto fuerte, pero para paliar los problemas de seguridad, estos recurren a una VPN.
-	<p style='text-align: justify;'> Otras dificultades que tiene una red WAN son la viabilidad de la red y establecer nuevas conexiones, ya que implican un alto costo.
-	<p style='text-align: justify;'> El desempeño de la red suele verse afectada debido a la latencia y las limitaciones del ancho de banda.
-	<p style='text-align: justify;'> Necesitan de antivirus y firewalls para fortalecer su seguridad, ya que una infección puede comprometer a todos los dispositivos conectados a la red

## Ejemplos 

![Image text](/Imagenes/1Wan.jpg)

-	Internet 
-	RedIRIS 
-	IBM 
-	Una red bancaria nacional
-	Las redes empresariales trasnacionales


## Redes LAN

![Image text](/Imagenes/lan.jpg)

<p style='text-align: justify;'> Una red de área local o LAN (por las siglas en inglés Local Area Network) es una red de computadoras que permite la comunicación y el intercambio de datos entre diferentes dispositivos a nivel local, ya que está limitada a distancias cortas. Por esta razón, esta red se utiliza para hogares privados, tales como una casa o un apartamento, y en empresas

<p style='text-align: justify;'> Las redes LAN se usan generalmente para permitir el intercambio de datos y recursos entre ordenadores en espacios reducidos, como un edificio o conjunto de edificios, oficinas, escuelas o en el hogar.
La red LAN requiere cables Ethernet y conmutadores de Capa 2 junto con dispositivos que se puedan conectar y comunicarse mediante Ethernet. Las LAN más grandes a menudo incluyen conmutadores o enrutadores de capa 3 para agilizar los flujos de tráfico.

<p style='text-align: justify;'> Una de las características más importantes de las redes LAN es que admiten la conexión de nodos múltiples o equipos individuales, permitiendo el acceso tanto a datos como a recursos (unidades de almacenaje, impresoras y otros dispositivos), incluso si no están conectados directamente a nuestro ordenador.
Una red LAN consiste en un mínimo de dos dispositivos finales, pero puede conectar miles. Sin embargo, para las grandes distancias es más conveniente usar redes MAN y WAN. Una red de área local o Local Area Network puede conectar ordenadores, teléfonos inteligentes, impresoras, escáneres, dispositivos de almacenamiento, servidores y otros dispositivos de red entre sí y con Internet. Si, por ejemplo, una impresora está conectada a un ordenador a través de USB, normalmente solo este PC puede acceder a ella. Sin embargo, si la impresora está integrada en la red, varios dispositivos de la casa pueden imprimir a la vez.

<p style='text-align: justify;'> Hay dos tipos de LAN principales: LANs cableadas y LANs inalámbricas (WLAN). Una LAN cableada utiliza conmutadores y cableado Ethernet para conectar puntos finales, servidores y dispositivos de internet de las cosas (IoT) a la red corporativa. Para las pequeñas empresas con solo un puñado de dispositivos, una LAN cableada puede consistir en un solo conmutador LAN no administrado con suficientes puertos Ethernet para interconectar todos los dispositivos. Pero las LAN más grandes que conectan miles de dispositivos requieren hardware, software y pasos de configuración adicionales para garantizar que la red funcione de manera óptima. Aquí es donde entra en juego el concepto de LANs virtuales (VLAN).

## Beneficios de usar LAN 

<p style='text-align: justify;'>Las redes de área local permiten que los dispositivos se conecten, transmitan y reciban información entre ellos. Los beneficios de las tecnologías LAN incluyen lo siguiente:

-	Permitir el acceso a aplicaciones centralizadas que residen en servidores. 

-	Permitir que todos los dispositivos almacenen datos críticos para el negocio en una ubicación centralizada.

-	Permitir el intercambio de recursos, incluidas impresoras, aplicaciones y otros servicios compartidos.

-	Permitir que varios dispositivos en una LAN compartan una sola conexión a internet.

-	Proteger los dispositivos conectados a la LAN mediante herramientas de seguridad de red.

## Topologías de redes 

Las topologías que existen son las siguientes:

![Image text](/Imagenes/TopRedes.png)

### Topología de bus

<p style='text-align: justify;'> Usa solo un cable backbone que debe terminarse en ambos extremos. Todos los hosts se conectan directamente a este backbone. Su funcionamiento es simple y es muy fácil de instalar, pero es muy sensible a problemas de tráfico, y un fallo o una rotura en el cable interrumpe todas las transmisiones. Esto hace que se dificulte el mantenimiento de la red.

### Topología de anillo

 <p style='text-align: justify;'>Conecta los nodos punto a punto, formando un anillo físico y consiste en conectar varios nodos a una red que tiene una serie de repetidores. Cuando un nodo transmite información a otro la información pasa por cada repetidor hasta llegar al nodo deseado. El problema principal de esta topología es que los repetidores son unidireccionales (siempre van en el mismo sentido). Después de pasar los datos enviados a otro nodo por dicho nodo, continúa circulando por la red hasta llegar de nuevo al nodo de origen, donde es eliminado. Esta topología no tiene problemas por la congestión de tráfico, pero si hay una rotura de un enlace, se produciría un fallo general en la red.

### Topología en estrella

 <p style='text-align: justify;'>Conecta todos los nodos con un nodo central. El nodo central conecta directamente con los nodos, enviándoles la información del nodo de origen, constituyendo una red punto a punto. Si falla un nodo, la red sigue funcionando, excepto si falla el nodo central, que las transmisiones quedan interrumpidas.

### Topología en estrella extendida

<p style='text-align: justify;'> Conecta estrellas individuales entre sí mediante la conexión de concentradores (hubs) o switches. Esta topología puede extender el alcance y la cobertura de la red.

### Topología jerárquica

<p style='text-align: justify;'> Es similar a una estrella extendida. Pero en lugar de conectar los hubs o switches entre sí, el sistema se conecta con un computador que controla el tráfico de la topología.

### Topología de malla

<p style='text-align: justify;'>Se implementa para proporcionar la mayor protección posible para evitar una interrupción del servicio. El uso de una topología de malla en los sistemas de control en red de una planta nuclear sería un ejemplo excelente. En esta topología, cada host tiene sus propias conexiones con los demás hosts. Aunque Internet cuenta con múltiples rutas hacia cualquier ubicación, no adopta la topología de malla completa.

### Topología de árbol

<p style='text-align: justify;'> Tiene varias terminales conectadas de forma que la red se ramifica desde un servidor base. Un fallo o rotura en el cable interrumpe las transmisiones.
La topología de doble anillo: es una de las tres principales topologías. Las estaciones están unidas una con otra formando un círculo por medio de un cable común. Las señales circulan en un solo sentido alrededor del círculo, regresándose en cada nodo. El doble anillo es una variación del anillo que se utiliza principalmente en redes de fibra como FDDI.

### Topología mixta
<p style='text-align: justify;'> Es aquella en la que se aplica una mezcla entre alguna de las otras topologías: bus, estrella o anillo. Principalmente las podemos encontrar dos topologías mixtas: Estrella-Bus y Estrella-Anillo. Los cables más utilizados son el cable de par trenzado, el cable coaxial y la fibra óptica.


## Datos en contra de las redes LAN

![Image text](/Imagenes/lan2.jpg)

<p style='text-align: justify;'> Sin embargo, la red LAN tiene también cosas en contra, debido a que el rango al que pertenece la ubicación donde estemos puede ser pequeño. Además, la distancia al nodo principal va a tener mucha relación con la calidad de servicio y velocidad que tenga nuestro dispositivo.

<p style='text-align: justify;'> También es importante comentar que el número de nodos que se pueden conectar a una sola Local Area Network es limitado. Cuantos más nodos se carguen a la red, mayor necesidad de recursos necesitará la computadora y más complicado se hará realizar una conexión.

<p style='text-align: justify;'> Para poder enfrentarse a estos problemas, sería importante que se agrupen diferentes redes Local Area network y se cree una red WAN que permita que la conexión se realice mediante redes públicas, como puede ser el sistema telefónico, los satélites u otros mecanismos. Estas redes las tenemos todos accesibles en nuestro día a día.




Parte Mauricio 

## Redes MAN
<p style='text-align: justify;'> MAN es la sigla de Metropolitan Area Network, que puede traducirse como Red de Área Metropolitana. Una red MAN es aquella que, a través de una conexión de alta velocidad, ofrece cobertura en una zona geográfica extensa (como una ciudad o un municipio). </p>

![Image text](/Imagenes/Red_MAN.jpg)

<p style='text-align: justify;'> Una MAN está compuesta por computadores o routers conectados entre sí con conexiones de alta velocidad (generalmente cables de fibra óptica).
Metropolitan Area Network o Red de área metropolitan (MAN). Se puede decir que una Red MAN es el punto intermedio entre lo que es una red LAN y WAM. Específicamente cuando hablamos de Metropolitan Área Network nos referimos a aquellas redes de alta velocidad que son capaces de ofrecer cobertura a una geografía bastante extensa.
Sin embargo, hasta ahora nunca ha superado las dimensiones de una ciudad. Las mismas pueden llegar a alcanzar velocidades de hasta 10 GB/segundo utilizando cables de fibras óptica.
 </p>

 ![Image text](/Imagenes/Red_MAN1.jpg)

<p style='text-align: justify;'>Estas redes MAN son comúnmente aplicadas por distintas organizaciones a nivel mundial, en las empresas, oficinas corporativas en los alrededores de las ciudades, entre otras. Las cuales no contienen ningún tipo de elemento de conmutación. Es decir, que ellas desvían los paquetes de información a través de varias líneas de salida potenciales. Además, estas redes pueden llegar a ser públicas o privadas. </p>

## Características Principales de Red MAN

- Son redes que se extienden sobre áreas geográficas de tipo urbano, como una ciudad.
- Son implementadas por los proveedores de servicio de Internet, que son normalmente los proveedores del servicio telefónico. Las MAN normalmente están basadas en estándares SONET/SDH o WDM, que son estándares de transporte por fibra óptica.
- Estos estándares soportan tasas de transferencia de varios gigabits (hasta decenas de gigabits).
- Son redes de alto rendimiento.
- Son utilizadas por los proveedores de servicio precisamente por soportar todas las tecnologías que se mencionan. 

## COMPONENTES DE UNA RED DE ÁREA METROPOLITANA

### Puestos de trabajo.
- Estaciones de trabajo.
- Ordenadores centrales.
- PCs o compatibles.
### Nodos de red.
Sus principales funciones son:
- Almacenamiento temporal de información a transmitir hasta que el canal de transmisión se libere.
- Filtrado de la información circulante por la red, aceptando sólo la propia.
- Conversión de la información de la red, en serie, a información del puesto de trabajo, octetos.
- Obtención de los derechos de acceso al medio de transmisión.
### Sistema de cableado.
Está constituido por el cable utilizado para conectar entre sí los nodos de red y los puestos de trabajo.
### Protocolos de comunicación.

<p style='text-align: justify;'>Son las reglas y procedimientos utilizados en una red para establecer la comunicación entre nodos. En los protocolos se definen distintos niveles de comunicación. Así, las redes de área metropolitana soportan el nivel 1 y parte del nivel 2, dando servicio a los protocolos de nivel superior que siguen la jerarquía OSI para sistemas abiertos. </p>

## Red WLAN

![Image text](/Imagenes/Red_WLAM.jpg)

<p style='text-align: justify;'>WLAN significa red de área local inalámbrica. Es una conexión inalámbrica que conecta dos o más dispositivos en LAN. WLAN utiliza puntos de acceso y enrutadores para establecer una conexión entre dispositivos. </p>

<p style='text-align: justify;'>Wi-Fi es un ejemplo de WLAN donde los dispositivos se conectan de forma inalámbrica dentro de un rango limitado.</p>

<p style='text-align: justify;'>Es decir, se realiza dentro del hogar, edificio de oficinas, laboratorio de computación, edificio escolar o cualquier campus universitario. Para usar Wi-Fi, los usuarios deben ingresar una contraseña para conectarse a Internet. La conexión Wi-Fi se realiza mediante puntos de acceso móviles o mediante un módem inalámbrico o un enrutador inalámbrico.</p>

## Significado de (WLAN).

 <p style='text-align: justify;'>Son las siglas de «Wireless Local Area Network», es decir, se refiere a una conexión de red inalámbrica de área local. A diferencia de una conexión LAN, que funciona de manera cableada, una conexión WLAN trabaja sin cables, de forma totalmente inalámbrica. Este tipo de redes utilizan la tecnología Wi-Fi, en sus diferentes estándares, para ofrecer una conexión a Internet sin tener que recurrir al cableado.</p>

## CARACTERISTICAS DE LAS REDES WLAN.

<p style='text-align: justify;'>Entre las características más importante de las redes inalámbricas se pueden mencionar:</p>

- Movilidad. 
- Facilidad de instalación
- Flexibilidad
- Costo de propiedad reducido

## Ventajas y desventajas 

### Ventajas.

- Al ser redes inalámbricas, la comodidad que ofrecen es muy superior a las redes cableados porque cualquiera que tenga acceso a la red puede conectarse desde distintos puntos dentro de un rango suficientemente amplio de espacio.

- La Wi-Fi Alliance asegura que la compatibilidad entre dispositivos con la marca Wi-Fi es total, con lo que en cualquier parte del mundo podremos utilizar la tecnología Wi-Fi.

- Una vez configuradas, las redes Wi-Fi permiten el acceso de múltiples ordenadores sin ningún problema ni gasto en infraestructura, no así en la tecnología por cable.

### Desventajas

- Tiene menor velocidad comparada a la conexión por cable, debido a que es propensa a las interferencias o pérdidas de señal del propio entorno.

- La seguridad es la principal desventaja. Y es que existen algunos programas capaces de capturar paquetes, trabajando con su tarjeta Wi-Fi.

## Red WiFi

<p style='text-align: justify;'>WiFi viene de ‘Wireless Fidelity’, es decir, ‘fidelidad inalámbrica’. Es una tecnología de transmisión de datos inalámbrica utilizada para Internet –principalmente- y que se basa en el estándar 802.11.</p>

![Image text](/Imagenes/Red_WIFI.jpg)

<p style='text-align: justify;'>WiFi, es una tecnología que permite la conexión inalámbrica entre dispositivos electrónicos, ordenadores, smartphones, tablets, televisores, videoconsolas, etc. Wi-Fi es una marca de Wi-Fi Alliance o Alianza Wi-Fi, la organización que promueve dicha tecnología y que se encarga de certificar todos los productos que se ajustan a las normas establecidas de interoperabilidad.</p>

<p style='text-align: justify;'>Tecnología que surgió por la necesidad de establecer una manera de conexión inalámbrica que fuese compatible con distintos dispositivos. Por lo tanto, el objetivo de la Alianza fue diseñar una marca que permitiese fomentar más fácilmente la tecnología inalámbrica y asegurar la compatibilidad entre dispositivos.</p>

## Cómo funciona la conectividad WiFi

<p style='text-align: justify;'>El WiFi se basa en ondas de radio, exactamente igual que la propia radio, la telefonía móvil o la televisión. Por lo tanto, las redes WiFi transmiten información por el aire utilizando ondas de radio.</p>

<p style='text-align: justify;'>Ahora bien, las frecuencias que se utilizan para esta tecnología de conectividad inalámbrica son distintas, concretamente 2,4 GHz hasta el estándar 802.11 n y 5 GHz en 802.11 ac.</p>

## Componentes del WiFi

<p style='text-align: justify;'>En una conexión WiFi tenemos un adaptador inalámbrico en un ordenador –u otro dispositivo- que traduce los datos en forma de señal de radio y, a través de una antena, los transmite ‘por el aire’. Y un router, también inalámbrico, que es el que se encarga de recibir la señal y decodificarla. Y una vez hecho esto, por una conexión física, por cable, a través de Ethernet, envía la información a través de Internet a otros servidores.</p>

![Image text](/Imagenes/WIFI.jpg)

## Tipos de seguridad en conexiones WiFi.

<p style='text-align: justify;'>La seguridad del WiFi es variable, principalmente en función del cifrado que se aplique a las comunicaciones entre el router y los adaptadores inalámbricos. Existen varias opciones, y se pueden dividir entre seguras y no seguras por sus características técnicas:</p>

- WEP (Wired Equivalent Privacy): Este tipo de cifrado nos remonta hasta el año 1999. 

- WPA (WiFi Protected Access): WPA fue la respuesta a los principales fallos y vulnerabilidades de WEP. Las claves usadas por WPA son de 256 bits, a diferencia de los 128 bits usados por WEP.

![Image text](/Imagenes/WEP_WAP.jpg)

- WPA2 la principal diferencia con WPA es el uso del AES, que realiza un cifrado por bloques para permitir claves más largas y seguras y la implementación del CCMP que se trata de un protocolo mejorado de encriptación que sustituye a TKIP.

- WPA3 Incorpora el cifrado de 192 bits en vez de 129 bits, lo que hace que el cifrado sea más seguro y difícil de romper. Esto hace que sea más seguro incluso con contraseñas menos fuertes, por lo tanto, una misma clave es más vulnerable a ataques de fuerza bruta en WPA2 que en WPA3. 

## Ventajas y desventajas de redes WiFi.

### Ventajas.

Entre las principales ventajas que nos ofrece el WIFI, caben destacar:

- Conectividad inalámbrica: Sin duda una de las principales ventajas que nos ofrece el WiFi es que se trata de un tipo de conectividad inalámbrica.

- Comodidad: El hecho de que sea una conectividad inalámbrica no ofrece también una gran comodidad y libertad. Es decir, podremos ir de un lado para otro con nuestro ordenador, tablet o móvil y seguir conectado sin que esto suponga ningún problema. 

- Coste: El no tener que hacer uso de cableado y dispositivos como hubs o similares, hace que una red WiFi tenga un coste mucho menor que las redes cableadas.
- Compatibilidad: La WiFi Alliance asegura la compatibilidad total entre dispositivos, por lo tanto, permite que podamos utilizar la tecnología WiFi con una compatibilidad total en cualquier parte del mundo.
 
### Desventajas.

- Velocidad: En el caso de usar una conexión WiFi, existen numerosos factores que pueden afectar a la velocidad de nuestra conexión en el dispositivo utilizado para la conexión, algo que con el cable es mucho menos probable salvo que utilicemos longitudes exageradas o cables de muy baja calidad.
- Latencia: Es otro de los principales problemas con los que nos podemos encontrar en este tipo de conexiones inalámbricas. Las conexiones WiFi son más propensas a sufrir ciertos lags, sobre todo cuando queremos reproducir contenido multimedia en alta resolución. 

- Interferencias: Las redes WiFi pueden verse afectadas por determinadas interferencias, lo cual supondrá un menor rendimiento de las mismas. 

- Microcortes: Todo este tipo de aspectos que pueden influenciar negativamente en una red WiFi pueden provocar ciertos cortes en nuestra conexión. 








