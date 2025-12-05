# 3. Identificación de necesidades tecnológicas

Tras la auditoría inicial realizada a la infraestructura actual, se han detectado carencias críticas que comprometen la seguridad, la operatividad y la eficiencia de la organización. A continuación, se detallan estas necesidades y las propuestas estratégicas de solución.

## Tabla de Análisis de Carencias y Propuestas de Solución

| Área de Impacto | Situación Actual (Problema Detectado) | Propuesta de Solución Estratégica (Concepto) |
| :--- | :--- | :--- |
| **Continuidad de Negocio (Red)** | Dependencia de un único dispositivo para servicios críticos de red (asignación de IPs). Un fallo provoca la desconexión total de la empresa. | **Implementación de Alta Disponibilidad en servicios de red:** Desplegar mecanismos de redundancia que aseguren la continuidad del servicio ante la caída de un nodo principal. |
| **Colaboración y Documentación** | Descontrol en las versiones de documentos, uso inseguro de unidades USB para transferir información y falta de un repositorio centralizado. | **Sistema Centralizado de Gestión Documental (Nube Privada):** Implantar una plataforma propia ("on-premise") para el almacenamiento seguro, control de versiones y colaboración en ficheros. |
| **Integridad y Seguridad del Dato** | Realización de copias de seguridad manuales en soportes físicos in situ. Alto riesgo de pérdida de datos ante fallo humano, físico o siniestro (incendio/robo). | **Estrategia Automatizada de Backup y Recuperación:** Automatizar el proceso de copias de seguridad e incluir una replicación externa (offsite) cifrada para garantizar la recuperación ante desastres. |
| **Gestión de Identidades y Accesos** | Uso de cuentas locales aisladas en cada equipo y contraseñas compartidas o débiles. Imposibilidad de gestionar permisos de forma unificada. | **Gestión Centralizada de Usuarios (IAM):** Implementar un sistema de directorio único para autenticar usuarios, gestionar grupos y aplicar políticas de acceso granulares. |
| **Mantenimiento y Operaciones** | Mantenimiento reactivo. Los problemas de rendimiento o capacidad (discos llenos, cuellos de botella) solo se detectan cuando causan una caída del servicio. | **Monitorización Proactiva de la Infraestructura:** Desplegar herramientas de supervisión en tiempo real del estado de los servidores y servicios para anticiparse a los fallos. |
| **Seguridad de Red Perimetral** | Red plana sin segmentación interna. El dispositivo de acceso a Internet carece de capacidades avanzadas de filtrado de tráfico. | **Segmentación Lógica y Seguridad Perimetral:** Dividir la red en segmentos lógicos según funciones/departamentos e implementar un cortafuegos para filtrar el tráfico entrante, saliente y entre zonas. |

## Propuesta
La propuesta se centra en solventar las vulnerabilidades críticas detectadas transformando una infraestructura precaria y manual en un entorno gestionado y profesional. Se prioriza la **centralización de la gestión** (usuarios y datos), la **automatización de procesos críticos** (backups) y la introducción de la **alta disponibilidad y la monitorización** para asegurar la continuidad operativa de la empresa.
