# Redes Comunitarias con Starlink
**ETN1011**

## Concepto
Las redes comunitarias son infraestructuras de telecomunicaciones creadas, administradas y mantenidas por una comunidad local para proporcionar servicios de comunicación —generalmente acceso a Internet, telefonía o redes de datos— en lugares donde los operadores comerciales no ofrecen cobertura adecuada o donde la comunidad busca autonomía tecnológica.

La idea central es que la red no pertenece a una gran empresa, sino a la propia comunidad, cooperativa, asociación o municipio que la utiliza.

---

# Características principales

- Gestión comunitaria.
- Objetivo social antes que comercial.
- Infraestructura compartida.
- Gobernanza local.
- Uso frecuente en zonas rurales o marginadas.

# Tecnologías comunes

- Wi‑Fi de largo alcance
- Redes mesh
- Fibra óptica comunitaria
- LTE/4G local
- Energía solar para nodos remotos

# Importancia estratégica

- Reducen la brecha digital.
- Aumentan la soberanía tecnológica local.
- Permiten resiliencia en desastres o crisis.
- Disminuyen dependencia de monopolios.
- Pueden funcionar como redes neutras locales.

# Ejemplo: Guifi.net

## Datos generales

- Fundación: 2004
- Fundador: Ramón Roca
- Tipo: Red comunitaria sin ánimo de lucro
- Cobertura: Más de 35.000 nodos
- Sede: Gurb, Barcelona

## Historia

Guifi.net nació en 2004 en Cataluña para resolver la falta de acceso a Internet en zonas rurales. Su modelo se basa en la cooperación ciudadana y el uso compartido de infraestructuras.

## Impacto

- Desarrollo local.
- Reducción de la brecha digital.
- Innovación social.
- Referente internacional en conectividad comunitaria.

# Organizaciones de apoyo

## Internet Society
Promueve Community-Centered Connectivity y financia proyectos de redes comunitarias.

## Dynamic Coalition on Community Connectivity (DC3)
Coordina cooperación internacional entre proyectos, investigadores y reguladores.

## Rhizomatica
Impulsa redes indígenas autónomas y tecnologías abiertas.

## Association for Progressive Communications (APC)
Apoya investigación, capacitación e incidencia política.

## ITU / UIT
Apoya iniciativas de conectividad comunitaria.

## UNESCO
Promueve inclusión digital y alfabetización tecnológica.

## Emergency Telecommunications Cluster
Apoya telecomunicaciones en emergencias.

# Arquitectura General

```text
Internet Global
      |
   Backhaul
      |
 Distribución
      |
 Acceso Local
```

# Backhaul

- Fibra óptica
- Radioenlaces de microondas
- Satélites GEO
- Satélites LEO (Starlink)

# Tecnologías Inalámbricas

- Wi‑Fi de largo alcance
- Punto‑multipunto
- Antenas direccionales

# Redes Mesh

## Protocolos

- B.A.T.M.A.N.
- OLSR
- Babel

## Ventajas

- Alta resiliencia
- Descentralización
- Autocuración

## Limitaciones

- Escalabilidad
- Interferencias
- Menor rendimiento con múltiples saltos

# Fibra Comunitaria

- FTTH comunitario
- GPON
- EPON

Ventajas:

- Estabilidad
- Alta velocidad
- Baja latencia

# Redes Celulares Comunitarias

- GSM
- 4G
- 5G

Software:

- OpenBTS
- Open5GS
- srsRAN

# Energía e Infraestructura

- Paneles solares
- Baterías
- Equipos de bajo consumo
- Torres y nodos distribuidos

# Software y Gestión

- OpenWRT
- Linux
- RouterOS
- Zabbix
- LibreNMS
- Nagios
- FreeRADIUS

# Tendencias y Retos

- OpenRAN
- LTE privado
- TV White Spaces
- Profesionalización de redes comunitarias

# Protocolo B.A.T.M.A.N.

**Better Approach To Mobile Adhoc Networking**

## Concepto

Cada nodo conoce únicamente el mejor siguiente salto y no toda la topología de la red.

## Funcionamiento

- Intercambio de mensajes OGM.
- Evaluación de calidad de enlaces.
- Selección automática de rutas.
- Adaptación dinámica.

## Ventajas

- Alta resiliencia.
- Menor complejidad.
- Adecuado para redes comunitarias.

## Limitaciones

- Throughput decreciente con muchos saltos.
- Sensibilidad a interferencias.
- Escalabilidad limitada.

## Hardware frecuente

### Ubiquiti

- NanoStation
- Rocket M5
- LiteBeam
- PowerBeam

### MikroTik

- RouterBOARD
- hAP ac
- LHG 5
- BaseBox

### Software

- OpenWRT
- LibreMesh
- batman-adv

# Casos reales

- Freifunk (Alemania)
- Guifi.net (España)
- Altermundi y LibreMesh (Latinoamérica)

# Arquitectura híbrida moderna

- Backbone con fibra o microondas.
- Segmentos mesh locales.
- Wi‑Fi comunitario para acceso final.

# Starlink

## ¿Qué es?

Servicio satelital de órbita baja (LEO) desarrollado por SpaceX.

## Características

- Menor latencia que GEO.
- Cobertura global.
- Despliegue rápido.

# Arquitectura con Starlink

```text
Terminal Starlink
        |
Router Principal
        |
Red Comunitaria
```

Distribución mediante:

- Wi‑Fi
- Mesh
- Radioenlaces
- Fibra

# Modelos de implementación

## Modelo simple

- Una antena compartida.
- Router central.
- Distribución Wi‑Fi.

## Modelo mesh

- Starlink como backhaul.
- BATMAN o LibreMesh.
- Expansión económica.

## Modelo con torres

- Torre central.
- Punto a multipunto.
- Cobertura regional.

# Equipos utilizados

- Terminal Starlink
- Routers MikroTik
- Equipos Ubiquiti AirMax
- Switches PoE
- Paneles solares

# Distribución Wi‑Fi Comunitaria

- 2.4 GHz para alcance.
- 5 GHz para capacidad.
- Control de usuarios.
- Segmentación de tráfico.

# Ventajas de Starlink

- Cobertura remota.
- Implementación rápida.
- Menor dependencia de fibra.
- Útil en emergencias.

# Limitaciones

- Costo mensual elevado.
- Dependencia de proveedor externo.
- Capacidad compartida.
- Sensibilidad climática.

# Aspectos regulatorios

- Licencias ISP.
- Regulación de redistribución.
- Normativas de espectro.
- Telecomunicaciones comunitarias.

# Casos de uso

- Escuelas rurales.
- Comunidades indígenas.
- Centros de salud.
- Redes de emergencia.

# CAPEX

| Concepto | Costo aproximado |
|-----------|-----------|
| Kit Starlink estándar | Bs 2.800 |
| Kit Starlink Mini | Bs 2.200 |
| Router adicional | Bs 500–2.000 |
| Torres y mástiles | Bs 1.000–8.000 |
| Sistema solar | Bs 4.000–15.000 |

# Ejemplo de nodo comunitario

| Concepto | Bs |
|-----------|-----:|
| Starlink | 2.800 |
| Router | 1.200 |
| Radios | 3.600 |
| Mástil | 2.000 |
| UPS y baterías | 3.500 |
| Instalación | 2.000 |
| **Total** | **15.100** |

# OPEX

- Plan Lite: ~Bs 400/mes.
- Plan estándar: ~Bs 531–610/mes.
- Energía.
- Soporte técnico.
- Mantenimiento.
- Reposición de equipos.

# Modelo económico

Ejemplo:

- 40 hogares.
- OPEX total: Bs 1.500/mes.
- Costo por hogar: Bs 37,5/mes.

# Ventajas para redes ciudadanas

- Cobertura rural.
- Velocidades entre 135 y 310 Mb/s.
- Baja latencia.
- Escalable con redes mesh.

# Riesgos

- Dependencia tecnológica externa.
- Costos elevados.
- Congestión en horas pico.
- Dependencia energética.
- Posibles cambios regulatorios.

# Conclusiones

- Starlink es viable como backhaul para zonas remotas.
- El principal desafío es el OPEX sostenido.
- El modelo cooperativo reduce costos.
- La combinación de Starlink, Wi‑Fi mesh y energía solar mejora la sostenibilidad.
- No reemplaza completamente a la fibra óptica, pero ayuda a reducir la brecha digital.

# Referencias

- https://starlink.com
- Experiencias de redes comunitarias en América Latina.
- Información pública sobre Starlink en Bolivia.
