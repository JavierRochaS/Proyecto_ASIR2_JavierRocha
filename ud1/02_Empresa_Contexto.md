# 2. Selección de la empresa o contexto de trabajo

## Ficha de la Empresa
* **Nombre Comercial:** *Lamaigniere Shipping, S.L.* (Empresa real seleccionada como modelo).
* **Ubicación Real:** Polígono Industrial La Isla, Calle Río Viejo, Dos Hermanas (Sevilla).
* **Justificación de la Ubicación:** El Polígono de la Isla es el principal nodo logístico del área metropolitana de Sevilla, con conexión directa a la SE-30 y A-4, albergando grandes centros de distribución (Amazon, Decathlon).
* **Contexto Real:** Lamaigniere es un operador logístico global con más de 100 años de historia, especializado en transporte internacional (marítimo, aéreo, terrestre) y, crucialmente, en **Gestión Aduanera**.
    * **Web Corporativa:** [Lamaigniere.com](https://lamaigniere.com/es)
* **Mapa de Suelo Industrial:** [Ficha del Polígono La Estrella (Prodetur - Diputación de Sevilla)](https://sueloindustrial.prodetur.es/poligono/pi-carretera-de-la-isla)
* **Imagen del link:** 
<p align="center">
  <img src="img/isla.png" alt="Estructura Visual del Proyecto" width="70%">
</p>


## Contexto del Sector (Datos SEPE)
El sector de **Transporte y Almacenamiento** es estratégico en Sevilla, representando el **3,98% de la afiliación** a la Seguridad Social. En el caso de Lamaigniere, el valor añadido radica en la gestión de documentación crítica internacional.

## Estructura Organizativa y Tecnológica (El Problema a Resolver)
A diferencia de una pequeña empresa de transporte local, Lamaigniere maneja un volumen crítico de datos sensibles.

* **Plantilla Aproximada (Sede Sevilla):** 40-50 empleados (Dirección, Dpto. Aduanas, Tráfico Marítimo/Aéreo, Administración, Comercial, Almacén).

* **Situación TI Actual:**
    * **Sistemas Heredados (Legacy):** La empresa ha crecido rápido y su infraestructura TI se ha quedado obsoleta.
    * **Caos Documental Crítico:** El Departamento de Aduanas y el de Tráfico manejan miles de documentos PDF (DUAs, BLs, facturas internacionales) que se comparten por carpetas de red desorganizadas o correos electrónicos, generando duplicidades y errores de versión.
    * **Seguridad Comprometida:** Existen PCs con Windows 10 y otros antiguos con Windows 7. No hay una política de dominio centralizada estricta, y las contraseñas a veces se comparten para agilizar operativas urgentes.
    * **Falta de Control:** La dirección no tiene visibilidad del estado real de los servidores que alojan el ERP o los ficheros. El mantenimiento es reactivo ante caídas.
    * **Riesgo de Parada:** Si el servidor de ficheros principal cae, la gestión de aduanas se detiene, lo que implica costes enormes por retrasos de mercancía en puerto/aeropuerto.

> **Conclusión:** La necesidad de una infraestructura IT robusta, segura, con alta disponibilidad y un sistema de gestión documental centralizado (Nube Privada) no es una opción, es una urgencia crítica para el negocio.
