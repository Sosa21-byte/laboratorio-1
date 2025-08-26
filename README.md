# Laboratorio-1
Uso de Rufus y Ventoy 
<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/89a43599-45db-4a17-b495-3d56567d07b0" />

Primer Punto

1.1 Proceso de Booteo en Rufus

Definición: El booteo consiste en iniciar un sistema operativo desde un dispositivo externo (USB/CD).
Con Rufus:
Descargar Rufus.
Insertar la memoria USB.
Seleccionar la imagen ISO de Ubuntu/Windows.
Configurar sistema de archivos (NTFS o FAT32).
Dar clic en Start.
Una vez creado, el PC arranca desde la memoria configurando el BIOS/UEFI para que el arranque sea desde USB.
1.2 Proceso de Booteo en Ventoy

Ventoy permite instalar múltiples ISOs en una sola memoria.
Pasos:
Descargar Ventoy.
Instalar Ventoy en la memoria USB (se crea una partición especial).
Copiar directamente las ISOs al USB.
Al iniciar el PC desde la memoria, aparece un menú con todas las ISOs cargadas.
1.3 Bootloader y GRUB

Bootloader: Programa que gestiona el arranque de un sistema operativo.
GRUB (GNU GRand Unified Bootloader):
Es uno de los bootloaders más usados en Linux.
Permite seleccionar qué sistema operativo arrancar (multi-boot).
Ofrece opciones de recuperación y parámetros de arranque.
1.4 Sistemas de archivos compatibles

FAT32: Universal, soporta casi todos los sistemas, pero limitado a archivos de 4GB.
NTFS: Usado en Windows, permite archivos grandes.
exFAT: Versión extendida de FAT, sin límite de 4GB.
ext4: Nativo de Linux, robusto para particiones de SO.
1.5 Estructura de particiones

Definición: División lógica de un disco para organizar datos o instalar SO.
Tipos:
MBR (Master Boot Record): Soporta hasta 4 particiones primarias, máximo 2TB.
GPT (GUID Partition Table): Más moderno, soporta discos de gran tamaño y muchas particiones.
