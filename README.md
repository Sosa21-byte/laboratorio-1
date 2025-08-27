# Laboratorio-1
Uso de Rufus y Ventoy
<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/89a43599-45db-4a17-b495-3d56567d07b0" />
 
##  Primer Punto  

### 1.1 Proceso de Booteo en Rufus  
- **Definición**: El booteo consiste en iniciar un sistema operativo desde un dispositivo externo (USB/CD).  
- **Con Rufus**:  
  1. Descargar Rufus.  
  2. Insertar la memoria USB.  
  3. Seleccionar la imagen ISO de Ubuntu/Windows.  
  4. Configurar sistema de archivos (NTFS o FAT32).  
  5. Dar clic en **Start**.  
- Una vez creado, el PC arranca desde la memoria configurando el BIOS/UEFI para que el arranque sea desde USB.  

### 1.2 Proceso de Booteo en Ventoy  
- **Ventoy** permite instalar **múltiples ISOs** en una sola memoria.  
- Pasos:  
  1. Descargar Ventoy.  
  2. Instalar Ventoy en la memoria USB (se crea una partición especial).  
  3. Copiar directamente las ISOs al USB.  
  4. Al iniciar el PC desde la memoria, aparece un menú con todas las ISOs cargadas.  

---

### 1.3 Bootloader y GRUB  
- **Bootloader**: Programa que gestiona el arranque de un sistema operativo.  
- **GRUB (GNU GRand Unified Bootloader)**:  
  - Es uno de los bootloaders más usados en Linux.  
  - Permite seleccionar qué sistema operativo arrancar (multi-boot).  
  - Ofrece opciones de recuperación y parámetros de arranque.  

---

### 1.4 Sistemas de archivos compatibles  
- **FAT32**: Universal, soporta casi todos los sistemas, pero limitado a archivos de 4GB.  
- **NTFS**: Usado en Windows, permite archivos grandes.  
- **exFAT**: Versión extendida de FAT, sin límite de 4GB.  
- **ext4**: Nativo de Linux, robusto para particiones de SO.  

---

### 1.5 Estructura de particiones  
- **Definición**: División lógica de un disco para organizar datos o instalar SO.  
- **Tipos**:  
  - **MBR (Master Boot Record)**: Soporta hasta 4 particiones primarias, máximo 2TB.  
  - **GPT (GUID Partition Table)**: Más moderno, soporta discos de gran tamaño y muchas particiones.  

---

## Segundo Punto  

### 2.1 Descargar imágenes ISO  
- **Ubuntu**: desde [ubuntu.com](https://ubuntu.com/download).  
- **Windows**: desde la página oficial de Microsoft.  

### 2.2 Crear memoria con Rufus (Ubuntu)  
1. Abrir Rufus.  
2. Seleccionar ISO de Ubuntu.  
3. Elegir sistema de archivos **FAT32/NTFS**.  
4. Iniciar el proceso.  

### 2.3 Crear memoria con Ventoy (Ubuntu y Windows)  
1. Instalar Ventoy en la memoria.  
2. Copiar ISO de Ubuntu y Windows a la memoria.  
3. Al arrancar, seleccionar desde el menú qué sistema instalar.  

---

##Tercer Punto  

### 3.1 Preparar partición para Ubuntu  
- Iniciar el PC desde la memoria booteable (Rufus o Ventoy).  
- Seleccionar **Instalar Ubuntu**.  
- En el instalador:  
  1. Elegir idioma y distribución del teclado.  
  2. Escoger opción **Instalar junto a Windows** o **Particionado manual**.  
  3. Crear partición **ext4** para Ubuntu y una partición de **swap**.  
  4. Continuar con instalación.  

---

## Conclusiones  
- Rufus es ideal para una ISO específica, rápido y sencillo.  
- Ventoy es versátil para múltiples ISOs en la misma memoria.  
- El conocimiento sobre particiones y sistemas de archivos es esencial para administrar instalaciones de SO.  
