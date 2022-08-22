# Paso 4: Crear medios de arranque
Ahora que ahora tiene un conjunto de archivos de trabajo, puede usar MakeWinPEMedia para crear medios WinPE de arranque.

Crear una unidad USB de arranque de Windows PE
Conecte una unidad USB a su PC técnico.

Inicie el entorno de herramientas de implementación e imágenes como administrador.

Opcional Puede formatear su llave USB antes de ejecutar MakeWinPEMedia. MakeWinPEMedia formateará su unidad de Windows PE como FAT32. Si desea poder almacenar archivos de más de 4 GB en su unidad USB de Windows PE, puede crear una unidad USB multipartición que tenga una partición adicional formateada como NTFS. Consulte Crear una unidad USB multipartición para obtener instrucciones.

Utilice MakeWinPEMedia con la opción de formatear e instalar Windows PE en la unidad flash USB, especificando la letra de la unidad de la llave USB:/UFD

Cmd

Copiar
MakeWinPEMedia /UFD C:\WinPE_amd64 P:

# Crear una ISO, DVD o CD de WinPE
Utilice MakeWinPEMedia con la opción de crear un archivo ISO que contenga los archivos de Windows PE:/ISO

Cmd

Copiar
MakeWinPEMedia /ISO C:\WinPE_amd64 C:\WinPE_amd64\WinPE_amd64.iso
