# Conectar XAMPP Remotamente

Repositorio para configurar XAMPP para acceso remoto.

## Cómo Configurar XAMPP para Acceso Remoto

Sigue estos simples pasos para permitir el acceso remoto a tu instalación de XAMPP.

### Pasos para Configurar la Página

### 1. Configurar la Red de la PC

1. Abre el "Firewall de Windows Defender" desde el buscador de Windows.
2. Ve a "Configuración avanzada".
3. Selecciona "Reglas de entrada".
4. Crea una nueva regla:
   - Tipo de regla: **Puerto**
   - Aplicar esta regla a: **TCP**
   - Puertos locales específicos: **80**
   - Permitir la conexión
   - Asigna un nombre a la regla según tu preferencia

### 2. Configurar XAMPP

1. Navega a la carpeta de XAMPP:
   - `xampp/apache/conf/extra`
2. Abre el archivo `httpd-xampp.conf`.
3. Copia el contenido del archivo `http_conf` de este repositorio y pégalo en `httpd-xampp.conf`.
