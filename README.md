# Ionic-app

Esta aplicación fue utilizada en la presentación que se realizó en Abril de 2015 https://github.com/startapplabs/starting-with-ionic 

Esta aplicación fue desarrollada por Agustin Haller https://github.com/agustinhaller y Dayana Jabif https://github.com/djabif

El framework con el cual fue construída es Ionic. Basado en AngularJS y SASS (Syntactically Awesome Style Sheets que en castellano viene a ser Hojas de estilos sintácticamente increíbles)

El deploy de **_Ionic-app_** fue realizado en **Cloud9** (https://c9.io)

### Crear un workspace en Cloud9 con template NodeJS
'Create a new workspace'

### Bajar la aplicación Ionic-app
'git clone https://github.com/diegoenriquesantos/Ionic-app.git'

### Acceder al path de la aplicación Ionic
'cd Ionic-app'

### Instalar npm y sus paquetes
'npm install'

### Iniciar la aplicación Ionic
'ionic serve -p $PORT --nolivereload'

Si al iniciar la aplicación se produce el error siguiente:

ionic $ /home/ubuntu/workspace/Ionic-app/node_modules/node-sass/lib/index.js:22
    throw new Error('`libsass` bindings not found. Try reinstalling `node-sass`?');
    ^

Error: `libsass` bindings not found. Try reinstalling `node-sass`?

Ejecutar las siguientes lineas de comando y luego volver a iniciar la aplicación:

'npm uninstall --save-dev gulp-sass'

'npm install --save-dev gulp-sass@'



