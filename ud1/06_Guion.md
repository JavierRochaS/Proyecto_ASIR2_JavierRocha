# 6. Guion inicial del proyecto

A continuación, se presenta una planificación inicial de alto nivel para las fases de ejecución del proyecto de modernización de la infraestructura TIC. Este guion define los hitos principales y el orden lógico de implementación.

### FASE 1: Análisis Detallado y Diseño de la Arquitectura (Semanas 1-2)
*  Auditoría exhaustiva de la infraestructura de red y sistemas actuales (inventario de hardware/software).
*  Diseño de la nueva topología de red lógica (plan de direccionamiento IP, definición de zonas de seguridad).
*  Definición de los requisitos de hardware para el servidor central y selección de la plataforma de virtualización.

### FASE 2: Despliegue de la Infraestructura Base (Semanas 3-4)
*  Instalación y configuración del hipervisor en el servidor físico.
*  Creación de las máquinas virtuales base para los distintos servicios.
*  Configuración de la red virtual interna y el almacenamiento (definición de volúmenes para datos y backups).

### FASE 3: Implementación de Servicios Centrales de Gestión y Red (Semanas 5-6)
*  Despliegue y configuración del servicio de Directorio Centralizado (gestión de usuarios y grupos).
*  Implementación de los servicios básicos de red (DNS) y del sistema de asignación de IPs con Alta Disponibilidad (redundancia).
*  Pruebas funcionales de la redundancia de los servicios de red.

### FASE 4: Despliegue de Servicios de Datos y Colaboración (Semanas 7-8)
*  Instalación y configuración de la plataforma de Nube Privada para gestión documental.
*  Integración de la autenticación de la plataforma documental con el Directorio Centralizado.
*  Definición de la estructura de carpetas, permisos de acceso y migración inicial de datos críticos.

### FASE 5: Seguridad, Monitorización y Operaciones (Semanas 9-10)
*  Configuración de las políticas de seguridad perimetral (reglas de firewall lógico).
*  Despliegue del sistema de Monitorización Proactiva y configuración de alertas básicas (estado de disco, CPU, disponibilidad de servicios).
*  Implementación y automatización de las políticas de Backup y Recuperación (locales y remotas cifradas).

### FASE 6: Cierre, Documentación y Transferencia (Semana 11)
*  Realización de pruebas integrales del sistema (incluyendo simulacros de recuperación de datos).
*  Elaboración de la documentación técnica final del proyecto y guías de usuario básicas.
*  Entrega del proyecto.
