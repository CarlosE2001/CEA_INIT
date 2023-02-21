# Manual Configuracion del Ambiente

## JDK 8

- Descargar [JDK 8](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)

- > tar -zxvf jdk-8u341
- > mv jdk1.8.0_202/ jdk


<hr>

## Web Logic
- Descargar [Weblogic 12c](https://www.oracle.com/middleware/technologies/weblogic-server-installers-downloads.html)

- > ./jdk/bin/java -jar fmw_12.2.1.4.0_wls_lite_generic.jar 

- Usuario: weblogic | Contrasena: weblogic123

- Next hasta el final

- Tomar en cuenta la ruta para el dominio base

<hr>

## Netbeans 8.2

- Descargar [netbeans-8.2-linux.sh](http://www.cs.tohoku-gakuin.ac.jp/pub/Tools/NetBeans/8.2/)

- > chmod +x netbeans-8.2-linux.sh

- > ./netbeans-8.2-linux.sh --javahome /home/$USER/Documentos/jdk

<hr>

## Weblogic Data Source

- Concfugurar la base de datos para hacer la conexion a la base de datos

|NAME|JDNI|URL|PASS|
|----|----|---|----|
|SIGECU|jdbc/sigecu|jdbc:oracle:thin:@//preproduccion-bd.ucr.ac.cr:1521/UCR32|Contacte a Gos|