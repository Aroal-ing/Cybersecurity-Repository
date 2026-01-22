# FUNDAMENTOS DE LINUX

En esta parte estarán descritos los comandos fundamentales de un Sistema Operativo Linux y su función.  
Todos los comandos fueron comprobados en una máquina virtual con Ubuntu.

---

## COMANDOS BÁSICOS

### echo  
Genera texto parametrado.  
Si el texto tiene más de una palabra o espacios, debe ir entre comillas dobles.

Ejemplos:
- `echo hola`
- `echo` "hola mundo"`

---

### whoami  
Se usa para saber el usuario con el que hemos iniciado sesión.

Ejemplo:
- `whoami`

---

### ls  
Lista los archivos y carpetas existentes en el directorio actual.  
También permite listar el contenido de otro directorio sin posicionarse en él.

Ejemplos:
- `ls`
- `ls Documentos`

---

### cd  
Permite cambiar de directorio.

Ejemplo:
- `cd directorio`

---

### cat  
Abreviación de *concatenate*.  
Muestra el contenido de un archivo (no solo archivos `.txt`).  
También se puede usar con rutas absolutas o relativas.

Ejemplos:
- `cat archivo.txt`
- `cat /ruta/al/archivo.txt`

---

### pwd  
Significa *Print Working Directory*.  
Muestra el directorio actual en el que nos encontramos y la ruta completa.

Ejemplo:
- `pwd`

---

### find  
Se usa para buscar archivos cuando no sabemos exactamente dónde están.

Ejemplos:
- `find -name archivo.txt`
- `find -name *.txt`

---

### wc  
Cuenta líneas, palabras o caracteres de un archivo.  
Muy usado para contar entradas o logs.

Ejemplo:
- `wc -l archivo.log`

---

### grep  
Filtra información específica dentro de un archivo.  
A diferencia de `cat`, no muestra todo el contenido, solo lo que coincide con el parámetro indicado.

Ejemplo:
- `grep "texto a buscar" archivo.txt`

---

## OPERADORES DE SHELL

### &  
Ejecuta comandos en segundo plano, permitiendo seguir usando la terminal.

Ejemplo:
- `apt install apache2 &`

---

### &&  
Permite ejecutar varios comandos en una sola línea.  
El segundo comando solo se ejecuta si el primero tuvo éxito.

Ejemplo:
- `comando1 && comando2`

---

### >  
Redirecciona la salida de un comando hacia un archivo.  
Si el archivo existe, se sobrescribe.

Ejemplo:
- `echo hey > welcome.txt`

---

### >>  
Funciona igual que `>`, pero en lugar de sobrescribir, agrega el contenido al final del archivo.

Ejemplo:
- `echo hola >> welcome.txt`

---

## CONCEPTOS CLAVE APRENDIDOS

- Entender por qué Linux es tan común hoy en día.
- Interactuar con mi primera máquina Linux.
- Ejecutar los comandos más fundamentales del sistema.
- Introducción a la navegación por el sistema de archivos.
- Uso de comandos como `find` y `grep` para búsquedas más eficientes.
- Activar y combinar comandos aprendiendo los operadores de shell más importantes.
