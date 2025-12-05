# 5. Obligaciones legales y normativas

El diseño de la nueva infraestructura TIC se fundamenta en el cumplimiento estricto del marco normativo vigente. Las leyes y reglamentos de referencia utilizados para este análisis se adjuntan como documentos PDF en la carpeta `documentos` del repositorio para su consulta directa.

## 1. Protección de Datos Personales (RGPD y LOPDGDD)
Dada la naturaleza de la información tratada por Lamaigniere Shipping (datos de clientes internacionales, expedientes de aduanas, RRHH), la solución propuesta se basa en el principio de "Privacidad desde el Diseño":

* **Soberanía y Control del Dato:** Al optar por una infraestructura de nube privada alojada localmente ("on-premise"), la empresa mantiene el control absoluto sobre la ubicación física y lógica de los datos, cumpliendo con las exigencias de control sobre transferencias internacionales.
* **Seguridad del Tratamiento (Art. 32 RGPD):** Se implementarán medidas técnicas como la autenticación centralizada única y el cifrado de datos sensibles en reposo y en tránsito.
* **Confidencialidad:** Los sistemas de backup incluirán cifrado robusto para proteger la información almacenada fuera de las instalaciones principales, conforme al Título VIII de la LOPDGDD sobre garantía de derechos digitales.

> **Referencias Normativas (Documentos locales):**
> * [**Reglamento General de Protección de Datos (RGPD - UE)**](documentos/RPGD.pdf) (Ver Art. 32 "Seguridad del tratamiento", Pág. 52)
> * [**Ley Orgánica de Protección de Datos (LOPDGDD - España)**](documentos/BOE-protecciondedatos.pdf) (Ver Titulo VIII, Pág. 50 a 58)

---

## 2. Propiedad Intelectual y Licencias de Software
Para garantizar la seguridad jurídica y la sostenibilidad económica de la nueva infraestructura:

* **Política de Licenciamiento:** El diseño prioriza el uso de software basado en estándares abiertos con licencias permisivas (tipo GPL, Apache, MIT) para los sistemas base y servicios críticos, asegurando el uso legal conforme a las disposiciones sobre programas de ordenador (ver **Título VII, Página 34** del texto refundido adjunto).
* **Auditoría de Cumplimiento:** Como paso previo a la implantación, se requiere realizar un inventario para detectar y regularizar cualquier software propietario sin licencia válida en la infraestructura actual, evitando infracciones de derechos de autor.

> **Referencia Normativa (Documento local):**
> * [**Ley de Propiedad Intelectual (Texto Refundido)**](documentos/BOE-propiedadintelectual.pdf) (Ver Título VII "Programas de ordenador", Pág. 34)

---

## 3. Seguridad en Servicios de la Sociedad de la Información (LSSI-CE)
La empresa presta servicios por vía electrónica a través de sus plataformas web y de gestión.

* **Seguridad de las Comunicaciones:** Se garantizará que el acceso a la nueva intranet corporativa y a la plataforma de gestión documental se realice exclusivamente a través de protocolos seguros (HTTPS) con certificados válidos, protegiendo la integridad y confidencialidad de las comunicaciones telemáticas, en línea con las obligaciones de los prestadores de servicios 

> **Referencia Normativa (Documento local):**
> * [**Ley de Servicios de la Sociedad de la Información (LSSI-CE)**](documentos/BOE-lss.pdf) (ver **Título II** del documento adjunto).

---

## 4. Prevención de Riesgos Laborales (PRL) en el entorno TIC
El diseño de la solución tendrá en cuenta la seguridad física y ergonómica del personal técnico y de oficina:

* **Seguridad en el Centro de Datos (CPD):** La instalación del nuevo equipamiento servidor deberá cumplir con las normas de seguridad para evitar riesgos eléctricos y garantizar una correcta organización del cableado (evitando caídas y tropiezos), conforme a los principios generales de acción preventiva (ver **Capítulo III** del documento adjunto).
* **Ergonomía:** La configuración de los puestos de trabajo informatizados deberá respetar las pautas sobre pantallas de visualización de datos (PVD) para prevenir la fatiga visual y postural.

> **Referencia Normativa (Documento local):**
> * [**Ley de Prevención de Riesgos Laborales (PRL)**](documentos/BOE-PRL.pdf) (Ver Capítulo III "Derechos y obligaciones", Pág. 11)
