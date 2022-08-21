# Paso 1: Crear archivos de trabajo
No importa qué tipo de medio vaya a crear, lo primero que debe hacer es crear un conjunto funcional de archivos de Windows PE en su PC del técnico.

Asegúrese de que su PC tenga instalado el complemento ADK y ADK windows PE.

En caso de no tenerlos puedes obtenerlos en los siguientes links:

Recuerda que las dos herramientas no son iguales cada una es independiente de sus funciones.
ADK: https://go.microsoft.com/fwlink/?linkid=2120254
ADK Windows PE: https://go.microsoft.com/fwlink/?linkid=2120253

Inicie el entorno de herramientas de implementación e imágenes como administrador.

Ejecute para crear una copia funcional de los archivos de Windows PE. Para obtener más información acerca de copype, vea Opciones de línea de comandos de Copype:
Script:  copype amd64 C:\WinPE_amd64

Una vez tengas este archivo llamado Boot.WIM Prodecemos a la fase 2.
