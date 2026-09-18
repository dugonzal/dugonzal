# Duvan M. González Escobar

**Ingeniero de software.** Dos años manteniendo en pie la red de operadores de telecomunicaciones en producción 24/7. Ahora monto la observabilidad de otros sistemas y sigo con mis laboratorios.

*Software engineer: networks & transport · platform & operations · backend.*

## Las tres partes

**Redes y transporte** — SNMP v1/v2/v3 con driver propio (PDU, ASN.1/BER, USM con autenticación y cifrado), MPLS en anillos de operador y en laboratorio, SDH y PDH en gestión de red. En el banco de pruebas: 120.000 polls sin un solo fallo, a unos 38.300 req/s. Laboratorio de 18 nodos con OSPF y MPLS: 237 comprobaciones por protocolo, 0 fallos (18/18 dispositivos y 22/22 enlaces), con capturas decodificadas con tcpdump y tshark.

**Plataforma y operación** — contenedores y Kubernetes, CI/CD con GitLab y Jenkins, Terraform, Ansible y Helm. Observabilidad completa: métricas, logs, dashboards y alertas con umbrales escritos, no de fábrica.

**Backend** — Java con Spring Boot, Kafka y PostgreSQL en producción 24/7; APIs REST sobre Tomcat en Linux. Go en los proyectos propios.

## Lo que puedes mirar aquí

| Repositorio | Qué demuestra |
|---|---|
| [cliente-0](https://github.com/dugonzal/cliente-0) | La parte que su licencia deja abierta de un sistema de gestión de red: contratos de cable entre agente y gestor, códecs de telemetría (C37.118, IEC 104) y la evidencia de lo medido sobre un parque de 18 nodos. |
| [woody-woodpacker](https://github.com/dugonzal/woody-woodpacker) | Packer ELF64 en C y ensamblador x86-64: cifra el segmento del entrypoint e inyecta un stub autodescifrante manteniendo PIE/ASLR. Verificado con readelf, objdump, gdb y strace. |
| [libsam](https://github.com/dugonzal/libsam) | Las funciones de la libc reescritas en ensamblador x86-64, con `Makefile` y `Dockerfile` para reproducir el build en cualquier máquina. |
| [webserver](https://github.com/dugonzal/webserver) | Servidor HTTP en C++ con sockets, multiplexado de entrada/salida y CGI. |
| [inception](https://github.com/dugonzal/inception) | Varios servicios en contenedores propios, con TLS, volúmenes y una red interna montada a mano. |
| [patent-research-mcp](https://github.com/dugonzal/patent-research-mcp) | Servidor MCP en Python: ingesta de patentes, extracción de secciones estructuradas y exportación. |

Los repositorios del trabajo actual (el driver SNMP y el laboratorio de red) son privados y **se abren bajo petición**: acceso temporal, los informes de cada etapa, o lo levantamos y lo ves funcionando delante de ti.

## Cómo trabajo

Cada número de rendimiento que aparece aquí lleva su medición publicada. Lo que no puedo enseñar, va marcado como tal. No pido que me creas: pido que lo repitas.

- Web, CV y pruebas: **https://dugonzal.github.io**
- Correo: **dugonzal@protonmail.com**
