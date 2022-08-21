# Paso 1: Crear archivos de trabajo
No importa qué tipo de medio vaya a crear, lo primero que debe hacer es crear un conjunto funcional de archivos de Windows PE en su PC del técnico.

Asegúrese de que su PC tenga instalado el complemento ADK y ADK windows PE.

En caso de no tenerlos puedes obtenerlos en los siguientes links:

<a href="https://go.microsoft.com/fwlink/?linkid=2120254">ADK 2004</a><br>
<a href="https://go.microsoft.com/fwlink/?linkid=2120253">ADK WINPE 2004</a>
Recuerda que las dos herramientas no son iguales cada una es independiente de sus funciones.

Inicie el entorno de herramientas de implementación e imágenes como administrador.

Ejecute para crear una copia funcional de los archivos de Windows PE. Para obtener más información acerca de copype, vea Opciones de línea de comandos de Copype:
Script:  copype amd64 C:\WinPE_amd64

Una vez tengas este archivo llamado Boot.WIM Prodecemos a la fase 2.
