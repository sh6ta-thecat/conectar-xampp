# conectar-xampp
repositorio para poder hacer que xampp se conecte remotamente
# Como configurar para acceder a xampp remotamente

Esto es un simple proceso
## Pasos para crear la página

### 1. Configurar la red de la pc

+  Desde tu buscador de windows busca: Firewall de Windows Defender e ingresa
+  Busca la parte de configuracion avanzada
+  Busca :"Reglas de entrada"
+  Crea una nueva regla
++ tipo de regla:Puerto
++ Se aplica esta regla UTC TCP...: TCP
++ SE APLICA ESTA REGLA A TODOS...: Puertos locales especificos 80
++ permitir la conexion
++ siguiente paso
  +agregarle el nombre al gusto
### 2. Configurar xampp
+ ingresa a la carpeta de xampp
+ direccion de las carpetas:xammpp>apache>conf>extra
+ abre el archivo:httpd-xampp.conf
+ copia el contenido del archivo http_conf de este repositorio
