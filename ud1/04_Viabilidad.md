# 4. Oportunidades y viabilidad del proyecto

## Viabilidad Técnica (Alcance del Proyecto)
El proyecto plantea una modernización integral de la infraestructura TIC de la empresa, demostrando la capacidad para diseñar y desplegar soluciones complejas que abarcan todas las áreas críticas de la administración de sistemas:
* **Gestión de Identidades:** Centralización de usuarios y permisos mediante servicios de directorio.
* **Servicios de Red Críticos:** Implementación de mecanismos de alta disponibilidad para garantizar la continuidad de la conectividad.
* **Infraestructura de Datos y Web:** Despliegue de plataformas "on-premise" para la gestión documental segura y el trabajo colaborativo.
* **Seguridad y Operaciones:** Diseño de estrategias de backup robustas, segmentación de red lógica y monitorización proactiva del entorno.

La solución propuesta se basa en arquitecturas probadas y estándares de la industria, asegurando su estabilidad y escalabilidad futura.

## Viabilidad Económica
La propuesta se ha diseñado para ser altamente eficiente en costes, maximizando el retorno de la inversión para una empresa del tamaño de Lamaigniere Shipping.

### 1. Estimación de la Inversión en Hardware (Servidor Central)
El núcleo de la nueva infraestructura será un único servidor físico potente que albergará, mediante virtualización, todos los servicios propuestos. Esto centraliza la inversión y simplifica el mantenimiento.

**Requisitos Mínimos Estimados:**
Para soportar la carga de trabajo de unos 40-50 usuarios concurrentes accediendo a gestión documental, servicios de directorio y bases de datos, se estima necesario un equipo con características similares a:
* **Procesador:** Gama empresarial (tipo Intel Xeon o AMD EPYC) de al menos 8 núcleos / 16 hilos para garantizar un buen rendimiento en virtualización.
* **Memoria RAM:** Mínimo 64 GB (recomendable 128 GB) para asignar recursos suficientes a todas las máquinas virtuales (servidor de archivos, directorio, base de datos, etc.).
* **Almacenamiento:** Sistema de discos en RAID (ej. RAID 5 o RAID 10) con tecnología SSD empresarial, ofreciendo una capacidad neta inicial de al menos 2-4 TB, con bahías libres para expansión futura.
* **Conectividad:** Doble interfaz de red Gigabit o 10G para redundancia y balanceo de carga.

**Rango de Inversión Estimado:**
Basado en precios de mercado para servidores de torre o rack de gama entrada/media con estas características y garantía profesional (3-5 años in situ), la inversión inicial en hardware se estima en una horquilla de **2.500 € a 4.500 €**.

Esta inversión es perfectamente asumible para una empresa de la facturación de Lamaigniere, especialmente considerando que sustituye a múltiples equipos obsoletos y descentralizados, y que su coste se amortiza en varios años.

### 2. Optimización de Costes de Software y Red
* **Modelo basado en Estándares Abiertos:** Se priorizará el uso de software de infraestructura (sistema operativo base, hipervisor, bases de datos) con modelos de licenciamiento abiertos que no impliquen costes recurrentes elevados, reduciendo drásticamente el OPEX (coste operativo).
* **Sin Inversión en Electrónica de Red Compleja:** La solución no requiere la adquisición de switches gestionables de alto coste, ya que la segmentación y seguridad se gestionarán a nivel lógico dentro del propio servidor.

### 3. Financiación y Subvenciones
El proyecto encaja perfectamente en los programas de ayudas a la digitalización vigentes (como el Kit Digital), específicamente en categorías como "Oficina Virtual" y "Ciberseguridad", lo que puede financiar una parte significativa de la implementación y, en algunos casos, del hardware asociado si se incluye como parte de una solución integral.

## Beneficios Esperados
* **Continuidad Operativa:** Reducción drástica del tiempo de inactividad y del riesgo de parada de negocio.
* **Eficiencia y Colaboración:** Mejora sustancial en los flujos de trabajo y la seguridad documental.
* **Control Total:** Visibilidad del estado de la infraestructura y soberanía sobre los datos corporativos.
