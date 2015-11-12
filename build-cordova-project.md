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

##Building for Android

> You need the Android SDK installed on your computer to build an Android version of your 
application using the steps below.

To build the project in the **workshop/platforms/android** folder and run it on an Android device connected to your 
computer using a USB cable, type:

```
cordova run android
```

To build the project in the **workshop/platforms/android** folder and run it in the Android emulator, type:

```
cordova emulate android
```

<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-cordova-project.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> 
Previous</a>
<a href="setup-files.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>


