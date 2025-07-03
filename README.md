# Instalacion de Windows Subsystem for Linux (Ubuntu) de manera sencilla en Windows 11
Veremos como instalar WSL de manera sencilla a pasos sin tener que tocar principalmente la terminal cmd o PoweShell para quien no este familiarizado, dando por hecho de contar con un equipo de potencia suficiente.
 
**Paso 1.** Abre el _Menu de Inicio_ de Windows 11, en el buscador escribe _Activar o desactivar las caracteristicas de Windows,_ al acceder asegurate de tener marcadas estas caracteristicas:

    [✓] Subsistema de Windows para Linux
    [✓] Virtual Machine PLataform

Al _aceptar_ se te pedira que reinicies el equipo*

***Nota!*** es recomendable que tengas activada la virtualizacion desde la BIOS o la interfaz UEFI*

**Paso 2.** Busca la _Microsoft Store_ en la _barra de tareas_ o escribiendola en el _Menu de Inicio,_ escribe _Ubuntu,_ selecciona e instala alguna version.

Cuando termine de instalarse, abrelo desde la _Microsoft Store_ y espera a que se inicialize

**Paso 3.** Crea y confirma un nombre de usuario con contraseña en la terminal de Ubuntu

***Nota!*** recuerda que la contraseña no es visible al escribirla y tampoco los caracteres **_"*"_** apareceran)

**Paso 4.** Actualiza las librerias con los siguientes comandos

    sudo apt update && sudo apt upgrade

Presta atencion para confirmas los upgrades con la tecla _Y_ o _S._

Ese comando se usa con regularidad para mantener tu sistema al dia.

***Nota!*** despues de copiar el comando, solo basta con presionar click derecho en la terminal para pegarlo.

#Listo

Hasta este punto ya se tiene instalado WSL en su forma mas basica y sencilla para quien apenas este empezando o requiera hacer o replicar alguna funcion que solo se encuentre disponible en linux
