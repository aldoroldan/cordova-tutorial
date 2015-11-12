---
layout: module
title: Modulo 2&#58; Construyendo un Proyecto Cordova
---

Este modulo es opcional. Si no agrego soporte para ninguna plataforma en el modulo anterior, puede saltear este modulo e ir al [modu0e 3](setup-files.html).

## Construyendo para iOS

> Necesita tener instalado el iOS SDK en su computadora para construir la version iOS de la aplicacion usando los pasos de mas abajo.

En la linea de comando, asegurese que esta en el directorio **workshop** y escriba:

```
cordova build ios
```

El proyecto sera construido en la carpeta **workshop/platforms/ios**. Haga doble-click **Workshop.xcodeproj** para abrir el proyecto en Xcode, y ejecutarlo en el emulador o en su dispositivo.

Puede tambien ejecutar la aplicacion en el emulador de IOS directamente desde la linea de comandos. Primero instale [ios-sim]
(https://github.com/phonegap/ios-sim):

```
npm install -g ios-sim
```

o

```
sudo npm install -g ios-sim
```

Luego ejecute la aplicacion en el emulador de iOS:

```
cordova emulate ios
```

##Construyendo para Android

> Necesita tener instalado el Android SDK en su computadora para construir la version Android de la aplicacion usando los pasos de mas abajo.

Para construir el proyecto en la carpeta **workshop/platforms/android** y ejecutarlo en un dispositivo Android conectado a su computadora usando un cable USB, escriba:

```
cordova run android
```

Para construir el proyecto en la carpeta **workshop/platforms/android** y ejecutarlo en un emulador de Android, escriba:

```
cordova emulate android
```

<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-cordova-project.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> 
Anterior</a>
<a href="setup-files.html" class="btn btn-default pull-right">Siguiente <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>


