# Guía de instalación de Vivado 2019.1

La seleccción de esta versión se debe, en parte, a que no incluye Vitis (un ambiente nuevo/moderno de AMD-Xilinx para el desarrollo de sistemas digitales). Vitis require de un mayor tamño en la instalación de las herramientas y no es necesario para fines del curso.

Para descargar Vivado 2019.1, primero necesitará crear una cuenta en AMD-Xilinx. Para la descarga necesitará llenar un formulario y probablemente esperar para recibir aprobación. La versión 2019.1 la puede encontrar [acá](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools/archive.html), tanto para [Windows](https://www.xilinx.com/member/forms/download/xef-vivado.html?filename=Xilinx_Vivado_SDK_Web_2019.1_0524_1430_Win64.exe) como para [Linux](https://www.xilinx.com/member/forms/download/xef-vivado.html?filename=Xilinx_Vivado_SDK_Web_2019.1_0524_1430_Lin64.bin).

Una vez que cuente con el ejecutable, e.g. `Xilinx_Vivado_SDK_Web_2019.1_0524_1430_Win64.exe` para Windows, deberá procer a ejecutarlo y es probable que le aparezca la siguiente ventana:

![new version](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/new_version.png)

Omita el obtener la última versión y continue con la isntalación. Una vez que de clik a Continuar verá una ventana como la siguiente, la cuál simplemente resume los sistemas operativos soportados oficialmente para esta versión de Vivado.

![welcome_screen](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/welcome_screen.png)

Después de dar click en Continuar, deberá ingresar sus credenciales creadas para AMD-Xilinx, _User ID_ y _Password_, y seleccionar la opción de _Download and Install Now_

![credentials](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/credentials.png)

Después, deberá aceptar todos los términos y condiciones, y dar click en Continuar.

![terms](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/terms.png)

La versión que no require una licencia de paga es la WebPACK.

![webpack](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/webpack.png)

En la siguiente ventana deberá seleccionar lo que se instalará. Para ahorar espacio en el disco duro, se recomienda la selección que se muestra a continuación. Con el _7 Series_ seleccionado se tendrá el soporte para el Artix-7 que está presente en la Basys 3. Asegúrese de habilitar la instalación de los controladores, _cable drivers_, así como habilitar el _WebTalk_. Con las opciones anteriores se requiere poco menos de 23 GB.

![selecction](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/selecction.png)

En la siguiente ventana deberá seleccionar dónde se instalará todo. Se recomienda: 'C:\Xilinx'. Cualquier otra ruta puede funcionar **siempre y cuando NO contenga espacios**.

![location](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/location.png)

Deberá aceptar la creación del directorio de destino.

![folder](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/folder.png)

Resumen de la instalación a realizar.

![sumary](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/sumary.png)

Una vez presionado el botón de _Install_ la instalación iniciará. Primero se descargará todo lo necesario:

![downloading](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/downloading.png)

y después la instalación como tal:

![installation](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/installation.png)

Deberá aceptar la instalación de los _cable drivers_:

![drivers](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/drivers.png)

Una vez realizada la instalación deberá agregar el archivo de descripción de la tarjeta Basys 3. Para ello podrá seguir la [guía provista por Digilent](https://digilent.com/reference/programmable-logic/guides/install-board-files#:~:text=Digilent%20provides%20board%20files%20for%20each%20FPGA%20development,and%20Memory%20Interface%20Generator%29%20used%20in%20many%20designs)

Esto le permitirá, al momento de crear un proyecto, escoger una configuración que se ajusta a la Basys 3.

Antes:

![antes](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/antes.png)

Después: 

![despues](https://raw.githubusercontent.com/EL3313/wiki/main/instalacion_vivado/fig/despues.png)



