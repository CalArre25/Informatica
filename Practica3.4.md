# Particiones y sistemas de archivos

----
Parte 1. Investigue los conceptos involucrados: partición (física y lógica, primaria, partición de arranque) (guía), GPT y MBR (guía), formatear un dispositivo de almacenamiento (guía), sistema de archivos (guía), archivo (guía), tipos de archivo (binario, texto, programa) (guía), cómo se guarda un archivo (guía) y las operaciones de manejo de archivos (guía).
-
Partición (Física y Lógica, Primaria, Partición de Arranque)
-
Partición Física:
-
Definición: Es una división física de un disco duro que funciona como una unidad de almacenamiento independiente. Cada partición tiene su propio sistema de archivos y puede contener un sistema operativo.

Ejemplo: Un disco duro de 500 GB dividido en dos particiones de 250 GB cada una.

Partición Lógica:
-
Definición: Es una subdivisión de una partición extendida. No contiene un sistema de archivos propio y se utiliza para crear unidades de almacenamiento adicionales dentro de una partición extendida.

Ejemplo: Una partición extendida puede contener múltiples particiones lógicas, cada una con su sistema de archivos.

Partición Primaria:
-
Definición: Son las primeras cuatro particiones en un disco. Pueden contener sistemas operativos y son las únicas desde las que se puede arrancar un sistema.

Ejemplo: Una PC típica tiene una partición primaria para el sistema operativo y otras para almacenamiento de datos.

Partición de Arranque:
-
Definición: Es una partición especial en la que se carga el sistema operativo al arrancar la computadora. En sistemas Windows, se denomina "partición activa".

Ejemplo: En un disco duro, la partición que contiene el sistema operativo es generalmente la partición de arranque.

GPT (GUID Partition Table) y MBR (Master Boot Record)
-
GPT:
-
Definición: GPT es una forma moderna de organizar las particiones en un disco duro. Permite un mayor número de particiones y es compatible con discos duros de más de 2 TB. Utiliza un esquema de tabla de particiones GUID (Globally Unique Identifier).

Ejemplo: Se utiliza comúnmente en sistemas operativos más recientes y es necesario para aprovechar al máximo discos duros grandes.

MBR:
-
Definición: MBR es un esquema más antiguo para organizar particiones en un disco duro. Está limitado a 4 particiones primarias y tiene un límite de tamaño de disco de 2 TB.

Ejemplo: Aunque es menos flexible que GPT, todavía se utiliza en muchos sistemas operativos y discos duros más antiguos.

Formatear un Dispositivo de Almacenamiento:
-
Definición: Formatear un dispositivo de almacenamiento implica prepararlo para su uso al crear un sistema de archivos sobre él. Esto borra todos los datos existentes en el dispositivo.

Sistema de Archivos:
-
Definición: Es una estructura lógica que el sistema operativo utiliza para organizar y gestionar archivos en un dispositivo de almacenamiento. Ejemplos comunes incluyen NTFS (Windows), FAT32, exFAT, y ext4 (Linux).

Archivo
-
Definición: Un archivo es una unidad básica de almacenamiento de datos en un sistema informático. Puede contener texto, imágenes, programas, etc.

Tipos de Archivo (Binario, Texto, Programa):
-
Archivo Binario: Contiene datos no legibles directamente por humanos, como imágenes, videos, archivos ejecutables, etc.

Archivo de Texto: Contiene caracteres legibles por humanos y suele representar texto sin formato.

Archivo de Programa: Contiene instrucciones ejecutables para la computadora. Pueden ser binarios (ejecutables) o código fuente (requiere compilación).

Cómo se Guarda un Archivo:
-
Depende del programa que estés utilizando. Generalmente, hay una opción de "Guardar" o "Guardar Como" en el menú del programa que te permite seleccionar una ubicación y nombre para el archivo.

Operaciones de Manejo de Archivos:
-
Estas operaciones incluyen copiar, mover, renombrar, eliminar, crear y abrir archivos. Puedes realizar estas acciones a través del explorador de archivos o mediante comandos en la línea de comandos, dependiendo del sistema operativo que estés utilizando.

Parte 2. Use una USB sin datos o nueva y practique los procesos de manejo de particiones (crear, cambiar de tamaño, fusionar y eliminar particiones en Windows con Disk Management (guía), de los siguientes tipos: FAT, exFAT, FAT32, NTFS y EXT4. Saque sus conclusiones.
-
Crear, cambiar el tamaño, fusionar y eliminar particiones son operaciones esenciales en la gestión del almacenamiento de un sistema. Aquí están las conclusiones específicas para cada tipo de sistema de archivos:
-
FAT (File Allocation Table)
-
Crear Particiones FAT:
-
Ventajas: Es compatible con una amplia gama de sistemas operativos y dispositivos.

Desventajas: Limitaciones en tamaño de archivos y particiones. No es la mejor opción para discos grandes.

Cambiar Tamaño de Particiones FAT:
-
Puedes cambiar el tamaño, pero con limitaciones. No es una operación muy flexible.

Fusionar Particiones FAT:
-
Fusionar particiones FAT puede ser complicado y puede requerir herramientas de terceros.

Eliminar Particiones FAT:
-
Es una operación relativamente sencilla.

exFAT (Extended File Allocation Table)
-
Crear Particiones exFAT:
-
Ventajas: Mejora las limitaciones de FAT32, es adecuado para dispositivos extraíbles y almacenamiento flash.

Desventajas: No es tan ampliamente compatible como FAT32.

Cambiar Tamaño de Particiones exFAT:
-
Es posible cambiar el tamaño, pero la flexibilidad puede depender del sistema operativo.

Fusionar Particiones exFAT:
-
Puede ser complicado y puede requerir herramientas adicionales.

Eliminar Particiones exFAT:
-
Es una operación relativamente sencilla.

FAT32 (File Allocation Table 32)
-

Crear Particiones FAT32:
-
Ventajas: Es compatible con una amplia gama de sistemas operativos. Adecuado para dispositivos extraíbles y discos duros.

Desventajas: Limitaciones en tamaño de archivos (4 GB) y tamaño de particiones.

Cambiar Tamaño de Particiones FAT32:
-
Limitado por las restricciones del sistema de archivos.

Fusionar Particiones FAT32:
-
Puede ser complicado y puede requerir herramientas adicionales.

Eliminar Particiones FAT32:
-
Es una operación relativamente sencilla.

NTFS (New Technology File System)
-
Crear Particiones NTFS:
-
Ventajas: Soporte para archivos grandes y sistemas de archivos robustos. Proporciona características de seguridad y compresión.

Desventajas: No es tan ampliamente compatible como FAT32.

Cambiar Tamaño de Particiones NTFS:
-
Puede ser realizado con mayor flexibilidad que en los sistemas FAT.

Fusionar Particiones NTFS:
-
Puede ser llevado a cabo más fácilmente que en sistemas FAT.

Eliminar Particiones NTFS:
-
Es una operación relativamente sencilla.

EXT4 (Fourth Extended Filesystem)
-
Crear Particiones EXT4:
-
Ventajas: Diseñado para sistemas Linux, ofrece rendimiento y características avanzadas.

Desventajas: No es compatible con sistemas operativos Windows sin software adicional.

Cambiar Tamaño de Particiones EXT4:
-
Puede ser realizado con flexibilidad en sistemas Linux.

Fusionar Particiones EXT4:
-
Se puede hacer utilizando herramientas específicas de Linux.

Eliminar Particiones EXT4:
-
Es una operación relativamente sencilla en sistemas Linux.

En resumen, la elección del sistema de archivos dependerá del sistema operativo que utilices y del propósito del disco o partición. NTFS y EXT4 son opciones populares para sistemas Windows y Linux, respectivamente. FAT32 y exFAT son útiles para dispositivos extraíbles y almacenamiento flash, mientras que FAT se utiliza principalmente en situaciones específicas. Cada sistema de archivos tiene sus ventajas y desventajas, por lo que es importante elegir el más adecuado para tus necesidades.
-
Parte 3. Repita las mismas operaciones de la Parte 3 de esta práctica usando la aplicación GParted Live CD/USB/HD/PXE Bootable Image copiando el archivo ISO en la USB con Ventoy y arrancando el ISO. Utilice este tutorial. Compare Disk Management y gParted y saque sus conclusiones.
-
Parte 4. Practique la recuperación de particiones eliminadas con TestDisk (tutorial en video, tutorial escrito) en discos o dispositivos de almacenamiento formateados. También, practique la recuperación de dispositivos que no son reconocidos o que piden ser formateados, como una USB (tutorial).
-




