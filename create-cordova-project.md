---
layout: module
title: Modulo 1&#58; Creando un Proyecto en Cordova 
---
## Pasos

1. Asegurese que tiene una version actualizada de [Node.js](http://nodejs.org/) instalada en su sistema.

1. Abra una Terminal (Mac) o una Ventana de Comandos (Windows), y escribalo el siguiente comando para instalar Cordova CLI:

  ```
  npm install -g cordova
  ```

  o en la Mac:

  ```
  sudo npm install -g cordova
  ```

  Si ya tiene Cordova instalado en su computadora, asegurese de actualizar a la ultima version:

  ````
  npm update -g cordova
  ````

  o

  ````
  sudo npm update -g cordova
  ````

1. Desplacese (cd) al directorio donde almacena sus proyectos en el sistema de archivos.

1. Usando el Cordova CLI, crear un projecto Cordova llamado **Workshop** en un directorio llamado **workshop**:

  ```
  cordova create workshop com.yourname.workshop Workshop
  ```

1. Desplacese al directorio del proyecto:

  ```
  cd workshop
  ```

1. Agregue soporte para la plataforma iOS (opcional)

    > Para ser capaz de contruir para la plataforma iOS, el iOS SDK debe estar instalado en su sistema. Si no lo        esta, puede saltar este paso y agregar el soporte para otra plataforma, o simplemente ejecutar la aplicacion       del tutorial en su browser.

    1. Asegurese que el iOS SDK se encuentra disponible en su sistema.
    2. En la linea de comandos, asegurese que esta en el directorio **workshop** y escriba:

        ```
        cordova platforms add ios
        ```
        
1. Agregue soporte para la plataforma Android (opcional)
    > Para ser capaz de contruir para la plataforma Android, el Android SDK debe estar instalado en su sistema. Si       no lo esta, puede saltar este paso y agregar el soporte para otra plataforma, o simplemente ejecutar la            aplicacion del tutorial en su browser.
    1. Asegurese que el Android SDK y la herramienta ant estan disponibles en su sistema. El Android SDK esta disponible 
    [aqui](http://developer.android.com/sdk). Tanto las herramientas **android** y **ant** deben estar colocadas en su path.
    2. En la linea de comando, asegurese que esta en el directorio **workshop** y escriba:

        ```
        cordova platforms add android
        ```

1. Asegurese que esta en el directorio **workshop**, y agregue los plugins basicos a nuestros proyectos:

  ```
  cordova plugin add org.apache.cordova.device
  cordova plugin add org.apache.cordova.console
  ```

1. Examine la estructura de directorio dependiente de workshop.
    - La carpeta **www** es donde colocara el codigo de su aplicacion HTML / JavaScript . Abra el archivo           index.html en un browser para ver la aplicacion por defecto creada por el CLI de Cordova.
    - La carpeta **platforms** es donde Cordova construira su aplicacion para diferentes plataformas (iOS, Android, 
    etc). El contenido de estas carpetas sera automaticamente generado por el CLI de Cordova, 
    y nunca debe editar el codigo de ese directorio.
    - Los Plugins son instalados en el directorio **plugins**.
    - Los parametros de la Aplicacion (nombre, autor, etc) son almacenados en el **config.xml**. 


<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="index.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Anterior</a>
<a href="build-cordova-project.html" class="btn btn-default pull-right">Siguiente <i class="glyphicon
glyphicon-chevron-right"></i></a>
</div>
</div>
