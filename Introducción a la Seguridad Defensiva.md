# Introducción a la Seguridad Defensiva (Blue Team)

La **seguridad defensiva**, también conocida como **Blue Team**, desempeña un papel fundamental en la protección de redes, sistemas y organizaciones de todo el mundo.

Cuando la seguridad defensiva falla —ya sea por ataques, vulnerabilidades explotadas o filtraciones de datos— el impacto puede ser **altamente costoso**, afectando la confiabilidad de la organización, generando pérdidas económicas y derivando en sanciones legales.

---

## Áreas Clave de la Seguridad Defensiva

### Monitoreo y Detección
Consiste en observar constantemente el comportamiento de la red y de los sistemas para identificar actividades anómalas o sospechosas que puedan indicar un ataque en curso.

###  Respuesta a Incidentes
Cuando se confirma una actividad sospechosa, se generan alertas y el equipo de respuesta a incidentes inicia el proceso para **contener, erradicar y recuperar** los sistemas afectados, devolviendo la operación a la normalidad.

###  Inteligencia de Amenazas
Se encarga de recopilar y analizar información sobre atacantes, técnicas, tácticas y tendencias con el objetivo de **anticipar ataques y fortalecer las defensas** de la organización.

###  Gestión de Vulnerabilidades
Busca identificar y corregir fallas en software, sistemas o configuraciones para reducir la superficie de ataque. Este proceso puede realizarse de manera **manual o automatizada**.

###  Investigación y Análisis
Analiza el comportamiento de los sistemas para distinguir entre actividad legítima y maliciosa, obteniendo información valiosa para prevenir futuros incidentes.

---

## Defensa en Profundidad

Las organizaciones no dependen de un solo nivel de seguridad. Implementan un enfoque llamado **Defensa en Profundidad**, que consiste en desplegar **múltiples capas de protección**, de modo que si una falla, otras continúen defendiendo el sistema.

---

## Capacitación de Empleados

El **factor humano** es uno de los eslabones más críticos en la ciberseguridad. La capacitación ayuda a los empleados a identificar y responder ante amenazas como:
- Phishing
- Ingeniería social
- Uso indebido de credenciales

---

## Tecnologías Clave de Seguridad Defensiva

###  Sistemas de Detección de Intrusiones (IDS)
Funcionan como cámaras de vigilancia dentro de la infraestructura TI, monitoreando tráfico y actividades sospechosas en la red y en los sistemas.

###  Firewalls
Actúan como guardianes de la red, permitiendo o bloqueando el tráfico según reglas de seguridad previamente definidas.

###  Políticas de Seguridad
Establecen normas claras para el uso adecuado de sistemas, contraseñas, accesos y dispositivos corporativos, reduciendo el riesgo de compromisos de seguridad.

---

## Centro de Operaciones de Seguridad (SOC)

El **SOC (Security Operations Center)** es el núcleo de la seguridad defensiva de una organización. Opera **24/7** y está compuesto por profesionales que monitorean, protegen y responden ante incidentes que afectan redes, sistemas y datos.

---

## SIEM – Security Information and Event Management

Un **SIEM** actúa como el radar de la seguridad defensiva. Centraliza y correlaciona la información generada por:
- Sistemas de seguridad
- Dispositivos de red
- Servidores
- Infraestructura TI

Esto permite detectar incidentes y analizarlos de manera rápida y eficiente.

---

## Escenario Práctico – FakeBank

El equipo de seguridad defensiva de **FakeBank**, una institución financiera, detectó un evento sospechoso mediante su SIEM.

### Detalles del Incidente
- **Tipo de ataque:** Web Discovery Attack  
- **Vulnerabilidad explotada:** Directory Enumeration  
- **URLs comprometidas:** 5  
- **Fecha:** 14 de julio de 2025  
- **Hora:** 10:21:39  
- **Duración:** 16 minutos con 32 segundos  
- **Origen:** Moscú, Rusia  
- **IP atacante:** 32.122.195.63  

---

## Mitigaciones Recomendadas

- Bloquear la IP maliciosa
- Revisar accesos y credenciales en paneles administrativos
- Implementar **rate limiting** para limitar solicitudes por usuario
- Actualizar reglas del **WAF (Web Application Firewall)**

---

## Conclusión

La seguridad defensiva es un pilar esencial para proteger los activos digitales de una organización. La combinación de personas capacitadas, procesos definidos y tecnologías adecuadas permite detectar, responder y mitigar amenazas de manera efectiva.
