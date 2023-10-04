# Instalación de sistemas operativos como máquinas virtuales

----
Parte 1. Investigue qué es la virtualización, una máquina virtual y cómo se instala un sistema operativo en una máquina virtual.
-
Virtualización:
-
La virtualización es una tecnología que permite crear entornos virtuales o máquinas virtuales (VMs) que simulan la existencia de hardware y software dentro de un sistema físico. Esto significa que puedes ejecutar múltiples sistemas operativos y aplicaciones en un solo servidor físico, lo que optimiza el uso de recursos y facilita la administración de sistemas.

Máquina Virtual:
-
Una máquina virtual es una instancia independiente de un sistema operativo que se ejecuta en un entorno virtualizado. Se comporta como una computadora completa, con su propio sistema operativo, recursos (como CPU, RAM y almacenamiento) y configuraciones de red. Puedes tener varias máquinas virtuales en un solo servidor físico.

Cómo se Instala un Sistema Operativo en una Máquina Virtual:
-
Seleccionar una Plataforma de Virtualización:
-
Primero, elige un software de virtualización. Algunas opciones populares incluyen VirtualBox, VMware, Hyper-V (de Microsoft) y KVM (para sistemas basados en Linux).

Instalar el Software de Virtualización:
-
Descarga e instala el software de virtualización en el sistema operativo del host (el sistema operativo físico en el que se ejecutará la máquina virtual).

Crear una Nueva Máquina Virtual:
-
Abre el software de virtualización y crea una nueva máquina virtual.
Durante este proceso, se te pedirá que asignes recursos como la cantidad de RAM y espacio en disco duro que se asignará a la VM.

Configurar la Máquina Virtual:
-
Al crear la VM, se te pedirá que indiques el archivo ISO del sistema operativo que deseas instalar. También puedes hacer esto más tarde desde la configuración de la máquina virtual.

Instalar el Sistema Operativo:
-
Inicia la máquina virtual. Esto abrirá una ventana que simula una computadora independiente.
A continuación, sigue los pasos de instalación del sistema operativo, como seleccionar el idioma, la región y la configuración de teclado.

Finalizar la Instalación:
-
Completa el proceso de instalación, incluyendo la configuración de cuentas de usuario y cualquier configuración adicional.

Instalar Herramientas de Huésped:
-
Algunos entornos de virtualización requieren la instalación de "herramientas de huésped" para mejorar la interacción entre la VM y el sistema operativo del host.

Configurar la Red (si es necesario):
-
Asegúrate de configurar la red de la máquina virtual para que pueda conectarse a Internet o a otros recursos de la red, si es necesario.

Una vez completados estos pasos, tu máquina virtual estará lista para funcionar con el sistema operativo instalado. Puedes iniciar, detener y gestionar la VM a través del software de virtualización que elegiste. Esto es especialmente útil para pruebas de software, desarrollo y configuraciones de red virtuales.
-
Parte 2. Instale VirtualBox en su sistema operativo Windows o el que tenga. Luego, instale el sistema operativo Fedora Workstation como una máquina virtual (Video 1). Finalmente, instale el VirtualBox Extension Pack.x
-
Parte 3. Utilice los archivos ISO de Windows 7 y Fedora Workstation e instálelos mediante VirtualBox (Video).
-
Parte 4. Pruebe que puede arrancar cada uno de los dos sistemas operativos como máquinas virtuales.
-



