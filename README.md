
## Despliegue de apps Sprint Boot en Aws

1. Crear cuenta en AWS
2. Buscar en el buscador el service Elastic Beanstalk
3. dar click en el boton **Create Application**
4. Asignas un nombre al aplicativo
5. En el apartado plataforma, seleccionas:
   * Plataforma: **Java**
   * Raminificación de la plataforma: **Corretto 17 running on 64bit Amazon Linux 2** o elegir la versión de Java utilizada
   * Versión de la plataforma: por defecto **3.4.5(Recommended)**.
6. En el apartado de Código de la aplicación seleccionar cargar codigo y se procede a colcoar el archivo punto.jar ubicado en la carpeta target.
7. por ultimo, se selecciona el boton crear una aplicación.

### Nota:
Es importante resaltar que para realizar el proceso se debe ir al service **S3**(Alamacenamiento Escalable en la nube) de AWS, y realizar los siguientes pasos: 
* Dentro d ela sección S3, elegir el servicio creado
* ingresar en el apartado Permisos
* Ingresamos en el apartado **Bloquear acceso público(configuración del bucket)**
* desactivamos la opcion **Bloquear todo el acceso publico**

