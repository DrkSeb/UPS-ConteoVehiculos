# UPS-ConteoVehiculos
# DetectorVehicular
## Construcción del Prototipo
En esta sección se muestran los componentes que fueron utilizados para para la creación del contador de Vehículos en tiempo real, dando una descripción del hardware y software que posee este prototipo.
### Cámara
NVIDIA Jetson NANO HD AI camera 800M CSI interface IMX219, esta es una cámara que posee chips sensibles a la luz, su resolución es de 1080 P y el ángulo del campo de visión es de 77 grados [Espesificaciones de Cámara](https://www.waveshare.com/wiki/IMX219-77_Camera).
### Nvidia Jetson Nano
Es una plataforma diseñada y creada por Nvidia, que está enfocada para su uso en aplicaciones de inteligencia artificial entre estas se encuentra la detección de objetos en tiempo real, clasificación de imágenes entre otras [Nvdia Jetson Nano](https://developer.nvidia.com/embedded/jetson-nano-developer-kit).
### OpenDataCam 3(beta 1)
Un software creado por [move lab](https://www.move-lab.com/), el cual tiene como función el conteo de objetos en tiempo real, a través de una cámara, archivo de video, cámaras ip.

![PicsArt_08-20-03 43 21](https://user-images.githubusercontent.com/38445434/90823827-19c1f900-e2fc-11ea-85ed-d5d90d42cc70.jpg)

## Diagrama de Actividades del Sistema
![actividades](https://user-images.githubusercontent.com/38445434/90815540-77e8df00-e2f0-11ea-8538-93b4d9ee7243.jpg)

## Método de Evaluación
Para evaluar el rendimiento y uso del dispositivo se utiliza la herramienta JetsonStats

![metricas](https://user-images.githubusercontent.com/38445434/90820269-c00b0000-e2f6-11ea-8ad9-c832b154ab8b.jpg)

## Las pruebas se realizaron en 3 avenidas de la ciudad de Quito-Ecuador
Cada una de las pruebas en 3 horas del día 9-10 am, 1-2 pm y 4-5pm.

![IMG_20200617_182828](https://user-images.githubusercontent.com/38445434/90822224-ba62e980-e2f9-11ea-8dea-9d9206b7a95a.jpg)
![IMG_20200617_182842](https://user-images.githubusercontent.com/38445434/90822233-be8f0700-e2f9-11ea-94b0-43a2b96a1f38.jpg)

### Av. De los Conquistadores
El prototipo ubicado a una altura de 4 metros, para evitar la oclusión de los vehículos pequeños

![Motocicleta gua](https://user-images.githubusercontent.com/38445434/90816595-26d9ea80-e2f2-11ea-9a87-2c14ea64453e.jpg)

### Av. 6 de diciembre y Av. Francisco de Orellana
El prototipo ubicado a una altura de 1,45 metros, para forzar la oclusión de los vehículos pequeños y evaluar el detector

![Oclusion](https://user-images.githubusercontent.com/38445434/90816318-b206b080-e2f1-11ea-9bfa-f787cd34172c.jpg)

## Resultados obtenidos
[Drive con Respaldo de Base de Datos](https://1drv.ms/u/s!As0bj9D3Nf6YgqR3FXj5KXx7dW_Fmw?e=1pThyH)

### Nvidia Jetson Nano

![jetsontab](https://user-images.githubusercontent.com/38445434/90821060-eda47900-e2f7-11ea-83f8-5f590f11d11c.png)
![jetsonEnergia](https://user-images.githubusercontent.com/38445434/90820938-c3eb5200-e2f7-11ea-9fd8-28260504c349.png)

### Métricas Machine Learning

![resultados](https://user-images.githubusercontent.com/38445434/90817708-cb106100-e2f3-11ea-93dc-ecfd50124662.jpg)

# Referencias 
1. [Instalación JetsonStats](https://pypi.org/project/jetson-stats/1.6.2/)
2. [Instalación OpenDataCam](https://opendatacam.github.io/opendatacam/documentation/USE_WITHOUT_DOCKER.html),para nuestro caso empleamos instalacion sin Docker

