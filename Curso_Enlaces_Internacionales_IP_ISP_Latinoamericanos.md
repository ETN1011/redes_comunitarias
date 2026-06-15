# Curso de Enlaces Internacionales IP para ISP Latinoamericanos


---

# Diapositiva 1

Curso de Enlaces Internacionales IP para ISP Latinoamericanos

ETN 1011, UMSA


---

# Diapositiva 2

Temario

Módulo 1. Arquitectura Global de Internet
Módulo 2. Operadores Tier 1, Tier 2 y Tier 3


---

# Diapositiva 3

Descripción

Este curso proporciona una visión integral de la infraestructura global de Internet
y de los mecanismos técnicos y comerciales utilizados para la conectividad internacional de los proveedores de servicios de Internet (ISP) en Latinoamérica. 
Se estudian:
los sistemas autónomos, 
el direccionamiento IP, 
el protocolo BGP, 
los operadores Tier, 
la infraestructura de fibra óptica terrestre y submarina, 
los puntos de intercambio de tráfico, 
las CDN y 
los modelos comerciales asociados al tránsito IP internacional.


---

# Diapositiva 4

Módulo 1. Arquitectura Global de Internet

1.1 Evolución de Internet
1.2 Internet como Red de Redes
1.3 Organismos de Coordinación


---

# Diapositiva 5

1.1 Evolución de Internet

La Internet moderna es el resultado de más de cincuenta años de evolución tecnológica, académica y comercial. Lo que comenzó como un proyecto experimental financiado por el gobierno de Estados Unidos terminó convirtiéndose en la infraestructura de comunicaciones más grande de la historia humana.

1.1.1. ARPANET y los orígenes de Internet.
1.1.2. NSFNET y la transición a Internet comercial.
1.1.3. Surgimiento de los operadores globales.
1.1.4. Evolución de los backbones internacionales.


---

# Diapositiva 6

1.1.1. ARPANET y los Orígenes de Internet

Contexto Histórico
Durante la década de 1960, en plena Guerra Fría, el gobierno de Estados Unidos buscaba desarrollar sistemas de comunicación más robustos y resilientes. La preocupación era que una red centralizada pudiera ser destruida fácilmente durante un conflicto militar.
La agencia encargada de investigaciones avanzadas del Departamento de Defensa, conocida como ARPA (Advanced Research Projects Agency), inició diversos proyectos para explorar nuevas formas de comunicación entre computadoras.


---

# Diapositiva 7

1.1.1. ARPANET y los Orígenes de Internet

La Idea de la Conmutación de Paquetes
Hasta ese momento, las telecomunicaciones funcionaban principalmente mediante conmutación de circuitos, como la red telefónica tradicional.
En una llamada telefónica se establece un circuito dedicado entre dos puntos durante toda la conversación.
Diversos investigadores propusieron una alternativa denominada conmutación de paquetes:
Los datos se dividen en pequeños bloques llamados paquetes.
Cada paquete puede seguir rutas distintas.
Los paquetes son reensamblados en destino.
La red puede adaptarse dinámicamente a fallas.
Esta idea fue desarrollada por investigadores como:
Paul Baran
Donald Davies
Leonard Kleinrock


---

# Diapositiva 8

1.1.1. ARPANET y los Orígenes de Internet

Nacimiento de ARPANET
En 1969 se estableció la primera red ARPANET conectando cuatro instituciones:
University of California, Los Angeles (UCLA)
Stanford Research Institute (SRI)
University of California, Santa Barbara (UCSB)
University of Utah
El primer mensaje enviado fue:
	LOGIN
Sin embargo, el sistema se cayó después de transmitir solamente:
	LO
Por ello, muchas veces se considera que el primer mensaje de Internet fue simplemente “LO”.


---

# Diapositiva 9

1.1.1. ARPANET y los Orígenes de Internet

Crecimiento de ARPANET
Durante los años setenta se incorporaron:
Universidades
Centros de investigación
Laboratorios militares
ARPANET permitió:
Compartir recursos computacionales.
Acceder remotamente a sistemas.
Intercambiar información científica.
También surgieron servicios fundamentales como:
Telnet
FTP
Correo electrónico
El correo electrónico se convirtió rápidamente en la aplicación más utilizada de ARPANET.


---

# Diapositiva 10

1.1.1. ARPANET y los Orígenes de Internet

El Desarrollo de TCP/IP
El Problema de las Redes Incompatibles
A medida que aparecían nuevas redes, surgió una dificultad:
Cada red utilizaba protocolos diferentes.
Era necesario desarrollar un mecanismo capaz de interconectar múltiples redes heterogéneas.
La Solución de Vinton Cerf y Robert Kahn
En los años setenta, los investigadores Vinton Cerf y Robert Kahn desarrollaron el protocolo TCP/IP.
El objetivo era permitir que múltiples redes funcionaran como una sola red lógica.
Conceptos Revolucionarios de TCP/IP
TCP/IP introdujo conceptos fundamentales:
Direccionamiento Universal
Cada dispositivo posee una dirección única.

Independencia del Medio Físico
TCP/IP puede funcionar sobre:
Líneas telefónicas
Radio
Satélite
Fibra óptica
Ethernet
Arquitectura Abierta
No depende de un fabricante específico.
Interconexión de Redes
La palabra Internet surge precisamente de:
Inter-Networking
es decir, la interconexión de redes independientes.
El “Flag Day” de 1983
El 1 de enero de 1983 ARPANET abandonó definitivamente los protocolos anteriores y migró completamente a TCP/IP.
Muchos historiadores consideran esta fecha como el nacimiento oficial de Internet.


---

# Diapositiva 11

1.1.1. ARPANET y los Orígenes de Internet

Vinton Cerf
Robert Kahn


---

# Diapositiva 12

1.1.2. NSFNET y la Transición a Internet Comercial

Limitaciones de ARPANET
A principios de los años ochenta ARPANET enfrentaba varios problemas:
Saturación de tráfico.
Crecimiento acelerado.
Dependencia militar.
Además, las universidades requerían mayor capacidad de comunicación.
Creación de NSFNET
La National Science Foundation (NSF) decidió construir una red académica nacional.
Nació así NSFNET en 1985.
Su misión era conectar:
Universidades.
Centros de supercomputación.
Instituciones de investigación.


---

# Diapositiva 13

1.1.2. NSFNET y la Transición a Internet Comercial

Evolución de Capacidad
1985
56 kbps
1988
1.544 Mbps (T1)
1991
45 Mbps (T3)
Para la época estas velocidades eran extraordinarias.
NSFNET se convirtió rápidamente en la columna vertebral de Internet.


---

# Diapositiva 14

1.1.2. NSFNET y la Transición a Internet Comercial

Estructura Jerárquica
NSFNET introdujo una arquitectura que aún se refleja en Internet actual:
Backbone Nacional
Red troncal principal.
Redes Regionales
Conectaban estados o regiones.
Redes Locales
Universidades y organizaciones.
Esta organización inspiró posteriormente el modelo de ISP actuales.


---

# Diapositiva 15

1.1.2. NSFNET y la Transición a Internet Comercial

La Apertura Comercial de Internet
Restricciones Iniciales
Durante muchos años NSFNET tenía restricciones:
Uso académico.
Investigación.
Educación.
No se permitía tráfico comercial significativo.
Aparición de los ISP
A finales de los años ochenta comenzaron a surgir empresas privadas que ofrecían acceso a Internet.
Entre ellas:
UUNET
PSINet
Sprint
Estas empresas comenzaron a construir redes propias.


---

# Diapositiva 16

1.1.2. NSFNET y la Transición a Internet Comercial

Retiro de NSFNET
En 1995 el gobierno estadounidense retiró NSFNET como backbone principal.
A partir de entonces:
Internet pasó a manos de operadores comerciales.
El crecimiento fue impulsado por el sector privado.
Nació el mercado moderno de conectividad IP.
Este evento marca el inicio de la Internet comercial contemporánea.


---

# Diapositiva 17

1.1.3. Surgimiento de los Operadores Globales

Los Primeros Carriers IP
Durante los años noventa aparecieron grandes proveedores capaces de operar redes internacionales.
Su función era:
Transportar tráfico entre continentes.
Conectar ISP regionales.
Mantener infraestructura global.
Expansión Mundial
Los nuevos operadores comenzaron a desplegar:
Fibra óptica terrestre.
Redes metropolitanas.
Enlaces submarinos.
Puntos de Presencia (PoP).
Nacimiento del Concepto Tier 1
A medida que crecían las redes surgió una clasificación informal.
Un operador Tier 1 es aquel que:
Puede alcanzar cualquier red de Internet.
No necesita comprar tránsito IP.
Mantiene acuerdos de peering con otros Tier 1.
Este concepto aparece aproximadamente entre mediados y finales de los años noventa.


---

# Diapositiva 18

1.1.4. Evolución de los Backbones Internacionales

Primera Generación (1985 – 1995)
Características:
Redes académicas.
Capacidad limitada.
Enlaces T1 y T3.
Cobertura principalmente nacional.
Segunda Generación (1995 – 2005)
Características:
Comercialización masiva.
Explosión de ISP.
Expansión internacional.
Aparición de grandes carriers.
Tecnologías predominantes:
SONET
SDH
Fibra óptica moderna

Cuarta Generación (2015 – Actualidad)
Características:
Hiperescalares.
Nube pública.
CDN masivas.
Redes de 400G y superiores.
Los mayores generadores de tráfico ahora operan infraestructura propia:
Amazon Web Services (AWS)
Google
Microsoft
Meta
En muchos aspectos, la Internet actual ya no está dominada exclusivamente por los carriers tradicionales, sino por una combinación de operadores de transporte, proveedores de nube y redes de distribución de contenido.

Tercera Generación (2005 – 2015)
Características:
Expansión de banda ancha.
Video por Internet.
Streaming.
Redes de 10G y 100G.
Aparecen grandes proveedores de contenido:
Google
Netflix
Facebook
Estos actores comienzan a influir directamente en la arquitectura global.


---

# Diapositiva 19

1.2. Internet como Red de Redes

Introducción
Una de las características más importantes de Internet es que no pertenece a una única organización, gobierno o empresa. A diferencia de una red corporativa tradicional, Internet está formada por miles de redes independientes que cooperan entre sí para intercambiar información.
Por esta razón suele definirse a Internet como:
	“La red de redes”
Cada una de estas redes es administrada por una organización diferente, posee infraestructura propia, políticas de operación propias y objetivos comerciales distintos. Sin embargo, mediante protocolos estandarizados, todas estas redes pueden comunicarse entre sí y formar un sistema global único.
Esta arquitectura descentralizada es uno de los factores que explica la enorme escalabilidad, resiliencia y crecimiento de Internet.

1.2.1. Concepto de Sistema Autónomo.
1.2.2. Interconexión de redes independientes.
1.2.3. Tránsito IP.
1.2.4. Peering.
1.2.5. Intercambio de tráfico


---

# Diapositiva 20

1.2.1 Concepto de Sistema Autónomo (AS)

¿Qué es un Sistema Autónomo?
Un Sistema Autónomo o Autonomous System (AS) es un conjunto de redes IP y routers administrados por una misma organización que presenta una política de enrutamiento única hacia Internet.
En términos simples:
Un ISP puede ser un Sistema Autónomo.
Una empresa multinacional puede tener su propio Sistema Autónomo.
Un proveedor de nube puede operar múltiples Sistemas Autónomos.
Cada Sistema Autónomo se identifica mediante un número único denominado:
	ASN (Autonomous System Number)


---

# Diapositiva 21

1.2.1 Concepto de Sistema Autónomo (AS)

Función de un Sistema Autónomo
Un Sistema Autónomo tiene varias responsabilidades:
Administración de direcciones IP
Gestiona los bloques IPv4 e IPv6 asignados.
Publicación de rutas
Anuncia al resto de Internet qué redes puede alcanzar.
Aplicación de políticas
Decide por dónde enviar y recibir tráfico.
Interconexión
Establece relaciones con otros Sistemas Autónomos


---

# Diapositiva 22

1.2.1 Concepto de Sistema Autónomo (AS)

Importancia del ASN para un ISP
Para un proveedor de Internet, disponer de ASN propio ofrece ventajas importantes:
Independencia operativa.
Posibilidad de contratar múltiples carriers.
Implementación de redundancia.
Ingeniería de tráfico.
Participación en acuerdos de peering.
Por esta razón, la mayoría de los ISP medianos y grandes poseen ASN propio.


---

# Diapositiva 23

1.2.1 Concepto de Sistema Autónomo (AS)

Importancia del ASN para un ISP
Para un proveedor de Internet, disponer de ASN propio ofrece ventajas importantes:
Independencia operativa.
Posibilidad de contratar múltiples carriers.
Implementación de redundancia.
Ingeniería de tráfico.
Participación en acuerdos de peering.
Por esta razón, la mayoría de los ISP medianos y grandes poseen ASN propio.


---

# Diapositiva 24

1.2.2 Interconexión de Redes Independientes

El Problema Fundamental
Si Internet está formada por miles de redes independientes, surge una pregunta:
¿Cómo puede un usuario conectado a un ISP en Bolivia acceder a un servidor ubicado en Japón?
La respuesta es mediante acuerdos de interconexión entre Sistemas Autónomos.
Cada red conoce:
Sus propias rutas.
Las rutas de sus vecinos.
Las rutas aprendidas de otros operadores.
De esta manera se construye una gigantesca base de conocimiento distribuida que permite encontrar caminos entre cualquier origen y cualquier destino.


---

# Diapositiva 25

1.2.2 Interconexión de Redes Independientes

La Cadena de Conectividad
Un flujo típico podría ser:
Usuario → ISP Local → Carrier Regional → Carrier Global → Red de Destino
Por ejemplo:
Cliente en La Paz → ISP boliviano → Cirion → Telxius → Google
Cada operador participa transportando tráfico hasta acercarlo a su destino final.


---

# Diapositiva 26

1.2.2 Interconexión de Redes Independientes

El Papel de BGP
Para coordinar esta interconexión se utiliza el protocolo:
BGP (Border Gateway Protocol)
BGP permite a los Sistemas Autónomos:
Intercambiar rutas.
Informar prefijos disponibles.
Aplicar políticas de tráfico.
Seleccionar caminos óptimos.
Sin BGP no existiría Internet tal como la conocemos actualmente.


---

# Diapositiva 27

1.2.3. Tránsito IP

Definición
El tránsito IP es un servicio mediante el cual una red paga a otra para obtener acceso al resto de Internet.
Es el modelo comercial más común entre operadores.
En este esquema:
Un proveedor vende conectividad.
Un cliente compra acceso global.


---

# Diapositiva 28

1.2.3. Tránsito IP

Características del Tránsito IP
Alcance Global
Permite llegar a cualquier destino conectado a Internet.
Relación Cliente-Proveedor
Existe una relación comercial directa.
Facturación
Normalmente basada en:
Capacidad contratada.
Percentil 95.
Burstable Billing.
Acuerdos SLA
Definen:
Disponibilidad.
Latencia.
Pérdida de paquetes.

Ventajas
Simplicidad operativa.
Cobertura mundial inmediata.
Escalabilidad.
Desventajas
Costos recurrentes.
Dependencia de proveedores externos.


---

# Diapositiva 29

1.2.4. Peering

Definición
El peering es un acuerdo mediante el cual dos redes intercambian tráfico directamente sin utilizar tránsito IP.
En lugar de pagar a un tercero, ambas redes se conectan directamente.


---

# Diapositiva 30

1.2.4. Peering

Objetivos del Peering
Reducir Costos
Menor consumo de tránsito internacional.
Reducir Latencia
Las rutas son más cortas.
Mejorar Rendimiento
Menor congestión y menor cantidad de saltos.
Incrementar Resiliencia
Existencia de rutas alternativas.

Tipos de Peering
Settlement-Free Peering
No existe compensación económica.
Ambas partes consideran que el intercambio es mutuamente beneficioso.
Paid Peering
Una de las partes paga por la interconexión.
Remote Peering
La conexión se realiza mediante terceros o enlaces remotos.


---

# Diapositiva 31

1.2.4. Intercambio de Tráfico (IXP y PIT)

Concepto General
A medida que aumentó el número de operadores surgió la necesidad de crear lugares neutrales donde múltiples redes pudieran interconectarse.
Así nacieron los:
IXP (Internet Exchange Point)
PIT (Punto de Intercambio de Tráfico)


---

# Diapositiva 32

1.2.4. Intercambio de Tráfico (IXP y PIT)

Beneficios Técnicos
Menor Latencia
El tráfico permanece dentro de la región.
Menos Saltos
Se evita el paso por carriers innecesarios.
Mejor Calidad de Servicio
Menor congestión.
Redundancia
Mayor diversidad de rutas.

Relación entre Tránsito, Peering e Intercambio de Tráfico
Internet moderna se sostiene sobre tres mecanismos complementarios
En la práctica, la mayoría de los ISP utilizan simultáneamente:
Tránsito IP para alcanzar Internet global.
Peering para optimizar tráfico frecuente.
PIT para interconectarse con operadores y proveedores de contenido.


---

# Diapositiva 33

1.3 Organismos de Coordinación

Introducción
Internet suele describirse como una red descentralizada, sin un propietario único y sin una autoridad central que controle todas sus operaciones. Sin embargo, para que miles de millones de dispositivos puedan comunicarse entre sí es necesario que existan mecanismos de coordinación global.
Por ejemplo:
Las direcciones IP deben ser únicas.
Los nombres de dominio deben evitar duplicidades.
Los protocolos de comunicación deben ser compatibles.
Los estándares técnicos deben ser aceptados globalmente.
Para cumplir estas funciones existen diversas organizaciones internacionales que coordinan aspectos específicos del funcionamiento de Internet.
Es importante comprender que estas organizaciones no son propietarias de Internet ni controlan el tráfico mundial. Su función consiste en coordinar recursos, desarrollar estándares y garantizar la interoperabilidad entre redes.
Las tres organizaciones más importantes para comprender el funcionamiento de Internet son:
ICANN
IETF
LACNIC

1.3.1. ICANN.
1.3.2. IETF.
1.3.3. LACNIC


---

# Diapositiva 34

1.3.1 ICANN

¿Qué es ICANN?
ICANN significa:
Internet Corporation for Assigned Names and Numbers
Fue creada en 1998 como una organización sin fines de lucro responsable de coordinar determinados recursos críticos de Internet.
Su objetivo principal es garantizar que Internet funcione como una red global única y coherente.

¿Por qué es necesaria ICANN?
Imagine que cualquier organización pudiera crear libremente nombres de dominio sin coordinación.
Podrían existir simultáneamente:
google.com apuntando a diferentes servidores.
microsoft.com administrado por distintas entidades.
dominios duplicados en distintas regiones.
Internet dejaría de funcionar de manera consistente.
ICANN existe precisamente para evitar este tipo de conflictos.


---

# Diapositiva 35

1.3.1 ICANN

Funciones Principales de ICANN
Coordinación del Sistema de Nombres de Dominio (DNS)
Administra la estructura global de nombres de dominio.
Administración de la Zona Raíz
La zona raíz es la base de todo el sistema DNS mundial.
Contiene la información de los dominios de nivel superior (TLD).
Coordinación de Recursos Numéricos
ICANN supervisa el sistema global de asignación de:
Direcciones IPv4.
Direcciones IPv6.
ASN (Autonomous System Numbers).
Aunque la asignación regional es realizada por los RIR, ICANN coordina el sistema global.


---

# Diapositiva 36

1.3.2 IETF

¿Qué es IETF?
IETF significa:
Internet Engineering Task Force
Es la organización responsable del desarrollo de los estándares técnicos que permiten el funcionamiento de Internet.
Fue creada en 1986 y se ha convertido en el principal organismo de estandarización de protocolos de Internet.
Misión de IETF
Su objetivo es:
“Hacer que Internet funcione mejor.”
La IETF desarrolla protocolos abiertos que pueden ser implementados por cualquier fabricante u operador.

Funcionamiento de la IETF
A diferencia de organismos tradicionales, la IETF opera mediante grupos de trabajo abiertos.
Participan:
Ingenieros.
Operadores.
Fabricantes.
Universidades.
Proveedores de servicios.
Las decisiones se toman mediante consenso técnico.
Uno de sus principios más conocidos es:
“Rough consensus and running code.”
Es decir:
Consenso razonable.
Implementaciones reales funcionando.


---

# Diapositiva 37

1.3.2 IETF

Los RFC
La principal producción técnica de la IETF son los RFC.
RFC significa:
Request For Comments
Los RFC describen:
Protocolos.
Estándares.
Procedimientos.
Buenas prácticas.
Actualmente existen miles de RFC publicados.


---

# Diapositiva 38

1.3.3 LACNIC

¿Qué es LACNIC?
LACNIC significa:
Latin American and Caribbean Internet Addresses Registry
Es el Registro Regional de Internet (RIR) responsable de América Latina y el Caribe.
Fue creado en 2002.
Su sede se encuentra en Montevideo, Uruguay.


---

# Diapositiva 39

1.3.3 LACNIC

Función Principal
Administrar los recursos numéricos de Internet para la región.
Estos recursos incluyen:
Direcciones IPv4.
Direcciones IPv6.
ASN.

Área de Cobertura
LACNIC atiende:
América del Sur.
América Central.
México.
El Caribe.
Más de treinta países forman parte de su región administrativa.


---

# Diapositiva 40

Módulo 2. Operadores Tier 1, Tier 2 y Tier 3

2.1 Concepto de Tier
2.2 Operadores Relevantes para Latinoamérica
2.3 Principales Hubs Regionales


---

# Diapositiva 41

2.1 Concepto de Tier

Introducción
A medida que Internet creció durante las décadas de 1990 y 2000 surgió la necesidad de clasificar las redes según su nivel de conectividad y dependencia de otros operadores.
Aunque no existe un organismo oficial que otorgue las categorías Tier 1, Tier 2 o Tier 3, estas definiciones son ampliamente utilizadas en la industria para describir la posición que ocupa una red dentro del ecosistema global de Internet.
La clasificación está basada principalmente en:
Alcance geográfico.
Capacidad de transporte.
Dependencia de tránsito IP.
Relaciones de peering.
Cobertura internacional.
Es importante entender que la clasificación Tier no mide tamaño, cantidad de clientes ni ingresos económicos. Una empresa muy grande puede seguir siendo Tier 2 si depende de tránsito IP de terceros.

2.1.1. Tier 1
2.1.2. Tier 2
2.1.3. Tier 3


---

# Diapositiva 42

2.1.1 Tier 1

Definición Formal
Un operador Tier 1 es una red capaz de alcanzar todas las demás redes de Internet sin comprar tránsito IP a ningún otro operador.
Para lograrlo mantiene acuerdos de interconexión directa con otros operadores Tier 1.
En otras palabras:
Un Tier 1 puede llegar a cualquier destino de Internet únicamente mediante peering.


---

# Diapositiva 43

2.1.1 Tier 1

Características Principales
Cobertura Global
Posee infraestructura distribuida en múltiples continentes.
Backbone Internacional
Opera una red troncal propia de alcance mundial.
Múltiples Puntos de Presencia
Dispone de PoP en los principales hubs internacionales.
Gran Capacidad de Transporte
Opera enlaces internacionales de muy alta capacidad.
Independencia Operativa
No necesita contratar tránsito IP para acceder a Internet global.

Settlement-Free Peering
Definición
Una característica esencial de los Tier 1 es el uso de:
Settlement-Free Peering
Este término significa:
Intercambio de tráfico sin compensación económica.
Dos operadores acuerdan intercambiar tráfico sin que exista pago entre ellos.
Cada uno considera que la relación es mutuamente beneficiosa.


---

# Diapositiva 44

2.1.2 Tier 2

Definición
Un operador Tier 2 es una red que combina:
Peering.
Tránsito IP.
A diferencia de un Tier 1, no puede alcanzar toda Internet únicamente mediante peering.
Necesita comprar tránsito a otros operadores para acceder a ciertos destinos.


---

# Diapositiva 45

2.1.2 Tier 2

Características
Alcance Regional o Internacional Parcial
Los Tier 2 suelen tener presencia en varios países o regiones.
Sin embargo, no poseen cobertura global completa.
Uso de Peering
Participan activamente en:
PIT.
IXP.
Interconexiones privadas.
para reducir costos y mejorar rendimiento.
Compra de Tránsito
Para alcanzar ciertas redes necesitan contratar tránsito IP.
Infraestructura Propia
Generalmente poseen:
Backbone regional.
Centros de datos.
PoP internacionales.

Alcance Regional
Ejemplo Latinoamericano
Muchos operadores regionales poseen:
Backbone continental.
Presencia en varios países.
Acceso a cables submarinos.
pero continúan comprando tránsito IP a operadores globales.
Ventajas
Menores costos que un Tier 3.
Mayor independencia.
Capacidad de ingeniería de tráfico.
Participación activa en peering.


---

# Diapositiva 46

2.1.3 Tier 3

Definición
Un operador Tier 3 es una red que depende completamente de proveedores upstream para alcanzar Internet.
Normalmente no vende tránsito IP a otros operadores.
Su principal función es proporcionar acceso a usuarios finales.


---

# Diapositiva 47

2.1.3 Tier 3

Características
Cobertura Local
Generalmente operan en:
Una ciudad.
Una región.
Un país.
Dependencia de Tránsito
Toda su conectividad internacional depende de terceros.
Infraestructura Limitada
Pueden disponer de:
Red de acceso.
Fibra metropolitana.
Radioenlaces.
Red FTTH.
pero normalmente no poseen backbone internacional propio.
Orientación al Usuario Final
Sus clientes suelen ser:
Hogares.
Empresas.
Instituciones públicas.


---

# Diapositiva 48

2.2 Operadores Relevantes para Latinoamérica

La conectividad internacional de Internet en Latinoamérica depende de una combinación de operadores globales, carriers regionales, sistemas de cables submarinos, centros de datos y puntos de intercambio de tráfico.
Durante muchos años gran parte del tráfico latinoamericano dependió de rutas hacia Estados Unidos, principalmente Miami. Sin embargo, la expansión de la infraestructura regional ha permitido el desarrollo de nuevos hubs como:
Lurín (Perú)
Santiago (Chile)
São Paulo (Brasil)
Ciudad de México (México)
En este contexto, tres operadores tienen una importancia particular para los ISP de la región andina y del Pacífico Sur:
Telxius
Sparkle
Cirion Technologies
Estos operadores participan activamente en el transporte internacional de tráfico IP y constituyen proveedores estratégicos para numerosos ISP de Latinoamérica.

2.2.1 Telxius
2.2.2 Sparkle
2.2.3. Cirion Technologies


---

# Diapositiva 49

2.2.1 Telxius

Telxius es una compañía especializada en infraestructura de telecomunicaciones internacionales.
Su negocio se centra principalmente en:
Sistemas submarinos.
Infraestructura internacional.
Landing stations.
Transporte de capacidad internacional.
Para muchos operadores latinoamericanos, Telxius constituye una de las principales puertas de salida hacia Norteamérica, Europa y otras regiones del mundo.


---

# Diapositiva 50

2.2.1 Telxius

Infraestructura Submarina
Importancia Estratégica
La principal fortaleza de Telxius es su participación en sistemas internacionales de cables submarinos.
Estos sistemas permiten transportar tráfico entre continentes utilizando enlaces de fibra óptica de muy alta capacidad.
Los cables submarinos son responsables de más del 95% del tráfico internacional mundial.
Función de los Sistemas Submarinos
Permiten:
Conectar continentes.
Reducir latencia.
Incrementar capacidad internacional.
Diversificar rutas.
Capacidad Internacional
Los sistemas submarinos modernos utilizan tecnologías como:
DWDM
Amplificación óptica submarina
Redes ópticas de larga distancia
permitiendo capacidades de múltiples terabits por segundo.


---

# Diapositiva 51

2.2.1 Telxius

Presencia Regional
Pacífico Sur
Telxius posee una presencia importante en la costa pacífica de Latinoamérica.
Esto incluye conectividad hacia:
Perú
Chile
Ecuador
Colombia
Lurín (Perú)
Uno de los puntos más relevantes para operadores andinos.
Lurín se ha convertido en un hub regional debido a la concentración de:
Landing stations.
Centros de datos.
CDN.
Carriers internacionales.
Para muchos ISP bolivianos, Lurín representa actualmente una de las principales rutas internacionales.

Conectividad Internacional
Desde Latinoamérica, Telxius proporciona acceso hacia:
Estados Unidos
Europa
Brasil
Asia
mediante infraestructura propia y acuerdos internacionales.


---

# Diapositiva 52

2.2.2 Sparkle

Sparkle es uno de los mayores operadores internacionales de telecomunicaciones del mundo.
Históricamente ha tenido una fuerte presencia en:
Europa
Mediterráneo
América
y participa activamente en la provisión de tránsito IP internacional.


---

# Diapositiva 53

2.2.2 Sparkle

Backbone Global
Red Internacional
Sparkle opera una extensa infraestructura internacional basada en:
Fibra óptica terrestre.
Sistemas submarinos.
PoP internacionales.
Backbone IP global.


---

# Diapositiva 54

2.2.2 Sparkle

Cobertura Geográfica
Europa
Italia
Alemania
Francia
España
Reino Unido
América
Estados Unidos
Brasil
Chile
Perú
Argentina
Medio Oriente y Asia
Turquía
India
Sudeste Asiático

Beneficios
Baja Latencia
Rutas optimizadas entre continentes.
Redundancia
Múltiples caminos internacionales.
Diversidad
Alternativas frente a otros carriers.
Aplicación para ISP Latinoamericanos
Muchos operadores regionales utilizan Sparkle como:
Carrier principal.
Carrier secundario.
Ruta de respaldo.
Esto permite mejorar resiliencia y disponibilidad


---

# Diapositiva 55

2.2.3 Cirion Technologies

Cirion Technologies es uno de los principales proveedores de infraestructura digital de América Latina.
Su origen está relacionado con la evolución de las antiguas redes regionales de telecomunicaciones que durante décadas sirvieron como base de conectividad para numerosos países latinoamericanos.
Actualmente posee una de las infraestructuras más extensas de la región.


---

# Diapositiva 56

2.2.3 Cirion Technologies

Alcance Geográfico
Cirion opera infraestructura en numerosos países de:
Sudamérica
Centroamérica
México
Cobertura Regional
La red conecta:
Principales ciudades.
Centros financieros.
Centros de datos.
Landing stations.
Importancia para la Región Andina
Cirion tiene una fuerte presencia en:
Perú
Chile
Colombia
Ecuador
Bolivia

Centros de Datos Regionales
Infraestructura Digital
Cirion opera una importante red de centros de datos en Latinoamérica.
Estos centros permiten alojar:
Equipamiento de ISP.
Plataformas cloud.
CDN.
Infraestructura empresarial.
Función Estratégica
Los centros de datos facilitan:
Interconexión
Peering entre operadores.
Alojamiento
Servicios de colocation.
Cloud Connectivity
Acceso a proveedores cloud.
CDN
Instalación de cachés regionales.
Ecosistema Regional
La combinación de:
Backbone regional.
Centros de datos.
Conectividad internacional.
ha convertido a Cirion en uno de los actores más importantes de la infraestructura digital latinoamericana.


---

# Diapositiva 57

2.2.3 Cirion Technologies
