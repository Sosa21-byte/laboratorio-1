# Laboratorio-1
Uso de Rufus y Ventoy
<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/89a43599-45db-4a17-b495-3d56567d07b0" />
 
##Imagen 1
![Imagen de WhatsApp 2025-08-27 a las 15 38 12_01f3b1c9](https://github.com/user-attachments/assets/4429b22f-37fb-4bfa-b57d-aaa82e251b26)

###Explicacion breve :

Se está configurando Rufus para crear un USB booteable con Ubuntu.

Se selecciona la ISO de Ubuntu (ubuntu-24.04.3-desktop-amd64.iso).

Se elige el esquema de partición MBR (compatible con BIOS/Legacy).

El sistema de archivos es NTFS (para soportar archivos grandes).

Propósito: Preparar el USB para instalar Ubuntu desde cero.

##Imagen 2 

![Imagen de WhatsApp 2025-08-27 a las 15 38 12_9723baef](https://github.com/user-attachments/assets/729a62e0-4f9e-4da4-bbaf-1c39d3d43241)

###Explicacion breve :

El USB (D:) ya tiene la ISO de Ubuntu copiada.

Ocupa ~5.93 GB de los 7.36 GB disponibles.

Propósito: El USB está listo para bootear e instalar Ubuntu.

##Imagen 3 

![Imagen de WhatsApp 2025-08-27 a las 15 41 29_cfd83da5](https://github.com/user-attachments/assets/499c4df9-8b35-4435-8e4a-b3d18520a5f6)

###Explicacion breve : 

Se usa Ventoy para hacer un USB multiboot.

El dispositivo es un USB de 32 GB (ADATA).

Ventoy ya está instalado en el USB (exFAT MBR).

Propósito: Permitir copiar múltiples ISOs (ej: Ubuntu + Windows) y bootear desde un menú.

##Imagen 4 :

![Imagen de WhatsApp 2025-08-27 a las 16 15 37_4592d8c6](https://github.com/user-attachments/assets/d6f208a4-0657-4d15-8c95-1d652a7c88a8)

###Explicacion :

El USB aparece como "Veriloy (D:)" en el explorador de Windows.

Contiene la ISO de Ubuntu (y potencialmente otras ISOs).

Propósito: Mostrar que Ventoy deja el USB visible como almacenamiento normal para copiar ISOs.

##Imagen 5 :

![Imagen de WhatsApp 2025-08-27 a las 17 00 52_e29d2d5d](https://github.com/user-attachments/assets/c8061033-35b1-43ac-804b-cc16fe7548a5)

###Explicacion breve : 

Se booteó desde el USB y se llegó al menú de Ubuntu.

Hay dos opciones:

Instalar Ubuntu (para instalación permanente).

Probar Ubuntu (modo live sin instalar).

Propósito: Decidir si se instala Ubuntu o solo se prueba.

##Imagen 6 :

![Imagen de WhatsApp 2025-08-27 a las 17 31 05_8f3bbcfa](https://github.com/user-attachments/assets/c485b93c-4745-43ab-ace6-bd6723b6e5a2)

###Explicacion breve :

Ubuntu ya está ejecutándose en modo live (desde el USB).

La interfaz está en español y muestra publicidad de características.

Propósito: Probar Ubuntu sin instalarlo, o proceder a la instalación desde el escritorio.

