# Habilidades de Búsqueda (Information Gathering & OSINT)

En esta práctica se abordan conceptos clave relacionados con la **recopilación de información**, una fase fundamental en ciberseguridad y OSINT.

## Objetivos de la Práctica

- Evaluar la fiabilidad de las fuentes de información  
- Utilizar motores de búsqueda de manera eficiente  
- Explorar motores de búsqueda especializados  
- Leer y analizar documentación técnica  
- Hacer uso de redes sociales como fuente de información  
- Consultar medios de comunicación  

---

## Evaluación de Fuentes de Información

Dado que en Internet **cualquiera puede publicar contenido**, es responsabilidad del analista evaluar la información antes de utilizarla. El hecho de que algo esté publicado no significa que sea correcto ni que provenga de una fuente experta.

Antes de confiar en una fuente, se recomienda:

- Identificar la **fiabilidad y reputación de la fuente**
- Comprobar la **evidencia y razonamiento** de la información presentada
- Evaluar si la información es **objetiva, imparcial y racional**
- Corroborar los datos utilizando **múltiples fuentes**

---

## Operadores de Búsqueda

Los motores de búsqueda ofrecen operadores avanzados que permiten **filtrar y refinar resultados**, aunque comúnmente no se explotan al máximo.

Ejemplos de operadores útiles:

- `"texto exacto"`  
  Busca sitios que contengan la frase exacta entre comillas.

- `site:`  
  Limita la búsqueda a un dominio específico.  

- `-palabra`  
Excluye resultados que contengan una palabra específica.

- `filetype:`  
Filtra resultados por tipo de archivo (pdf, doc, ppt, xls).

---

## Motores de Búsqueda Especializados

### SHODAN
Motor de búsqueda que permite encontrar **dispositivos conectados a Internet** como servidores, cámaras, routers e IoT, mostrando:
- Puertos abiertos
- Servicios activos
- Versiones
- Vulnerabilidades expuestas

Además, Shodan funciona como guía de herramientas según el área de ciberseguridad:
- Blue Team
- Red Team
- SOC
- Network / SysAdmin

---

### CENSYS
A diferencia de Shodan, Censys se enfoca en:
- Hosts
- Sitios web
- Certificados digitales
- Otros activos expuestos en Internet

Se utiliza comúnmente para:
- Enumerar dominios en uso
- Auditar puertos y servicios
- Detectar activos fraudulentos o mal configurados

---

### VIRUSTOTAL
Plataforma que permite analizar **archivos, URLs y hashes** para determinar si contienen malware, troyanos o código malicioso, utilizando múltiples motores antivirus en un solo análisis.

---

### Have I Been Pwned (HIBP)
Servicio que permite verificar si una **dirección de correo electrónico** ha sido comprometida en alguna **filtración de datos** conocida.

---

### CVE (Common Vulnerabilities and Exposures)
Funciona como un **diccionario de vulnerabilidades** conocidas.  
Cada vulnerabilidad se identifica mediante un **CVE ID**, por ejemplo: CVE-2024-29988

La organización **MITRE** es la encargada de mantener y estandarizar estos identificadores.

---

### Exploit Database
Exploit Database es una plataforma que recopila **exploits públicos** asociados a vulnerabilidades conocidas.  
Algunos exploits están marcados como **Verified**, lo que indica que han sido probados y funcionan.

Cabe destacar que en **GitHub** existen numerosas herramientas relacionadas con CVEs enfocadas en crear **PoC (Proof of Concept)**, es decir, pruebas controladas de explotación.

---

## Documentación Técnica

Todo sistema, programa o herramienta (kernel, shell, software, etc.) cuenta con una **documentación oficial**, comúnmente conocida como **manual**.

- En Linux: `man ip`
- En Windows: `help`, `Get-Help` (PowerShell)

La documentación técnica:
- Está bien organizada
- Describe comandos, funciones y parámetros
- Se mantiene actualizada

 **Leer documentación técnica es una habilidad clave**, ya que proporciona información confiable directamente desde los desarrolladores del sistema o herramienta.

---

## Conclusión

Las habilidades de búsqueda y análisis de información son esenciales en ciberseguridad. Una correcta recopilación y validación de datos permite tomar decisiones informadas, reducir errores y fortalecer tanto ataques controlados como defensas efectivas.



