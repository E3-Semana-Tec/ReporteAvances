# Empresas identificadas 

## ![Image](https://github.com/E3-Semana-Tec/ReporteAvances/blob/master/Imagenes/tesla-logo-text-png-7_opt.png)


La Empresa Tesla De Elon Musk es del ramo automotriz y es una empresa la cual tiene como misión crear los mejores automóviles eléctricos y la mejor calidad a su consumidor. Es una empresa enfocada en el futuro y en la ecología. Sus principales funciones que la diferencian de otras marcas de automoviles son que fueron pioneros en la elaboracion de automoviles completamente electricos y son los mas avanzados en esa area y ademas su manejo autonomo lo cual genera un gran confort al propietario a la hora de trasladarse a lugares lejanos.

El modelo IoT que actualmente utilizan es la geolocalización y creación de rutas para que se llegue al destino sin problemas de batería ni contratiempos. Este sistema de ruta genera un camio en el cual si el vehículo lo requiere tenga una estación de carga en el transcurso del recorrido y llegar al destino con la mayor carga posible y así no tener muchos inconvenientes. Tambien su geolocalizacion ayuda al automovil a recoger al propietario en distintos lugares, obviamente tiene sus limitantes. Y en cuento al menejo autonomo en su sistema de localizacion de objetos por medio de distintas camaras y sensores alrededor del carro genera una autonomia segura. Estos beneficios le generan una gran comodidad al conductor y ademas de una gran seguridad a la hora de manejar 



## ![Image](https://github.com/E3-Semana-Tec/ReporteAvances/blob/master/Imagenes/att-logo1_opt.png)


A continuación, se presenta una colaboración entre tres empresas para desarrollar un nuevo servicio más eficiente e innovador para los consumidores. 

Se trata de la empresa de automóviles, KIA MOTORS quien implementó en su aplicación móvil “MyKIA+”, un nuevo servicio de recuperación de sus automóviles en caso de robo o emergencias. Es precisamente AT&T, quien proporciona sus herramientas y servicios como lo es su plataforma: Control Center, diseñada para facilitar la administración de soluciones IoT. Cabe mencionar que RESSER es la encargada de trabajar en el servicio de localización satelital para conocer la ubicación exacta y en tiempo real de cualquier automóvil KIA.

De esta forma, Find My Kia ayuda a todos los clientes de KIA Motors en la recuperación de sus automóviles en caso de robo, disminuyendo los índices de este delito y proporcionando seguridad al adquirir un automóvil KIA. 

Para saber más: [link](https://www.att.com.mx/newsroom/noticia/att-conecta-el-nuevo-desarrollo-de-kia-motors)


## ![Image](https://github.com/E3-Semana-Tec/ReporteAvances/blob/master/Imagenes/qualcomlogo.png)


Qualcomm es una compañía estadounidense que produce chipsets para la tecnología móvil CDMA y W-CDMA, son los creadores y diseñadores de los procesadores Snapdragon, también es responsable del cliente de correo electrónico Eudora. Entre sus principales productos está Brew, es una plataforma que permite la creación de aplicaciones para dispositivos móviles y Qchat. Es uno de los principales suministradores de la familia de procesadores para teléfonos inteligentes Snapdragon. Es un desarrollador de semiconductores para redes y comunicaciones, Qualcomm Atheros. También fabrica un sistema de recarga inalámbrica de vehículos eléctricos (Wireless Electric Vehicle Charging - WEVC) denominado Qualcomm Halo, esta compañía se encuentra sujeta al sector de las Nuevas Tecnologías de la Información y la Comunicación (TIC), el cual está compuesto por los sectores manufactureros y de servicios cuya actividad principal está ligada al desarrollo, producción, comercialización y uso intensivo de las mismas, dado que conecta con sus contactos clave, proyectos, accionistas y noticias relacionadas. 

Su modelo en el que utilizan el internet de las cosas (IOTS) es brindando ayuda a sus clientes para poder comercializar sus productos de una manera más rápida y con costos beneficiosos para ambas partes de esa manera solucionan la problemática, utilizando plataformas optimizadas en las áreas de cuerpos inteligentes, hogares inteligentes y ciudades inteligentes.


# El modelo de uso de IoT seleccionado colaborativamente.

El modelo que seleccionamos fue la marca automotriz Tesla La cual consideramos que es un beneficio mas accesible para la población ya que casi todo el mundo utiliza los automóviles y es un beneficio hacia todas las personas que pudieran comprar dicho automóvil. Su propuesta de valor es la creación de automóviles, electicos, autónomos y cómodos, estos con varios sistemas IoT que favorecen en la comodidad del propietario. 

Gracias al IoT puede manejar autónomamente y crear rutas más eficientes diseñadas con base a la batería del automóvil, el destino y distintas estaciones de carga para el vehículo. Además, cuenta con un software que avisa al usuario si el automóvil tiene algún problema y este puede comunicarse fácilmente con la agencia y en caso de accidentes automovilísticos podría comunicarse con servicios de ayuda. 

Los datos que genera este modelo son principalmente datos no estructurados que a traves de machine lerning y deep lerning se pueden convertir a datos semi-estructurados para facilitar su analisis en la nube, estos datos son desde las credenciales unicas de cada usuario (como su dirección IP) hasta los puntos de geolocalizacion de este mismo.

# Guía rápida introductoria al uso de GitHub, sus comandos básicos y recursos de apoyo en línea. 

GIT LOG

-git log -<limite>
Limita el número de commits a <limite>. Ejemplo.  “git log -5” limitará a 5 commits.
  
-git log –oneline
Une cada commit en una sola línea.

-git log -p
Muestra la diferencia completa de cada commit.

-git log –stat
Incluye qué archivos fueron alterados y el número relativo de líneas que se agregaron o eliminaron de cada uno de ellos.

-git log --author= ”<compañero>”
Busca commits de un autor en particular.

-git log --grep=”<compañero>”
Busca commits con un mensaje de commit que coincide con <compañero>.

-git log <desde>..<hasta>
Muestra los commits que ocurren entre <desde> y <hasta>. Args puede ser un ID de confirmación, nombre de rama, HEAD o cualquier otro tipo de referencia de revisión.
  
-git log --<archivo>
Solo muestra los commits que tiene el archivo especificado.
  
-git log --graph—decorate
--graph flag dibuja un gráfico basado en texto de confirmaciones en el lado izquierdo de la confirmación msgs. --decorate agrega nombres de ramas o etiquetas de confirmaciones que se muestran.

GIT DIFF

-git diff HEAD 
Muestra la diferencia entre el directorio de trabajo y la última confirmación.

-git diff --cached 
Muestra la diferencia entre los cambios preparados y la última confirmación.

REWRITING GIT HISTORY
-git commit--amend
Reemplace la última confirmación con los cambios por etapas y la última confirmación conjunto. Usa sin nada preparado para editar el mensaje de la última confirmación.

-git rebase <base>
Vuelva a basar la rama actual en <base>. <base> puede ser un ID de confirmación, nombre de la rama, una etiqueta o una referencia relativa a HEAD.

-git reflog 
Muestra un registro de cambios en el HEAD del repositorio local. Agrega la marca --relative-date para mostrar la información de la fecha o --all para mostrar todas las referencias.

UNDOING CHANGES

-git revert <commit>
Crear una nueva confirmación que deshaga todos los cambios realizados en <commit>, luego aplíquelo a la rama actual.
  
-git reset <file> 
Elimina <file> del área de ensayo, pero deja el directorio de trabajo sin alterar. Esto desestabiliza un archivo sin sobrescribir ningún cambio.
  
-git clean -n 
Muestra qué archivos se eliminarían del directorio de trabajo. Utilice el indicador -f en lugar del indicador -n para ejecutar la limpieza.

# Porducto Final
![Image](https://raw.githubusercontent.com/E3-Semana-Tec/ReporteAvances/master/Imagenes/tesla-logo-text-png-7_opt.png)

## FindMyTesla
FindMyTesla busca ser una aplicación de IoT que permita el rastreo de todos los automoviles registrados a la propiedad de un usuario determinado, esta infromación sera monitoreada y almacenada constantemente en la nube y estara disponible para el usuario cuando este asi lo desee.

Algunos de los beneficios que ofrece la aplicación es que puedes conocer la localización en tiempo real de cualquier automovil que tenga los recursos necesarios para conectarse a la red y para conocer su información geográfica y que su información sera registrada y alamacenada en una base de datos en la nue para el uso que el usuario crea conveniente, desde compartirlo con familiares hasta sincronizarlo con las autoridades pertinentes por cuestiones de seguridad.

## Video demostrativo
[![TITLE](https://img.youtube.com/vi/8n84DjIJGkA/0.jpg)](https://www.youtube.com/watch?v=8n84DjIJGkA)

## Plataforma de almacenamiento en la nube
![Image](https://github.com/E3-Semana-Tec/AppIoT/blob/master/Captura%20de%20pantalla%20(422).png?raw=true)

## Párrafo Explicativo 
La aplicación FindMyTesla pone al propietario en comunicación directa la ubicación exacta en la que se encuentra su vehículo Tesla. Los datos proporcionados por el sistema de navegación determinan la ubicación en tiempo real del vehículo, esta ubicación se envía automáticamente a la nube de la posición global actual y se presenta en la aplicación FindMyTesla, a la que se puede acceder a travez del teléfono móvil. Para acceder a dicha información del vehículo, el propietario debe crear una cuenta con su usuario y contraseña, en la cual tendrá la oportunidad de  permitir que más usuarios accedan a la información de su vehículo. 

Por otro lado, ademas de permitir el acceso a diferentes usuarios, por temas de seguridad, la aplicación enviara las credenciales del usuario que esta utilizando la aplicación al propietario.  El software de mapeo en la aplicación brinda instrucciones precisas y la calidad es mejor que cualquier otra aplicación en el mercado. Ya sea que el vehículo sea de la familia o de la empresa, este rastreador GPS para su Tesla es una herramienta valiosa por la seguridad que brinda. Por ejemplo, en el caso de que suceda algo impensable y te roben el coche, puedes utilizar el dispositivo instalado en tu coche para localizar rápidamente dónde está.

## Proceso de Control de calidad
1. Documentación
2. Gestión de la configuración
3. Aseguramiento de la calidad
4. Verificación
5. Validación
6. Revisión en conjunto
7. Auditoria
8. Solución de problemas


## Archivos descargables 
En la sigueinte liga podra descargar el archivo **.aia** de "FindMyTesla" versión **Pre-Alpha**: [FindMyTesla](https://github.com/E3-Semana-Tec/AppIoT/blob/master/AppIoT%20(2).aia)

En la siguiente liga podra descargar el archivo **.apk** de "FindMyTesla" versión **Pre-Alpha**: [FindMyTesla](https://github.com/E3-Semana-Tec/AppIoT/blob/master/AppIoT.apk)

## Referencias 
- [AppInventor2](https://www.appinventor.mit.edu)

- [Github](https://www.Github.com)

- Dudler, R. (2016). La guía sencilla. Retrieved September 18, 2020, from: [Link](https://rogerdudler.github.io/git-guide/index.es.html)

- Arciniega, F. (2017, May 26). Normas y Estándares de calidad para el desarrollo de Software. Retrieved September 18, 2020, from: [Link](https://fernandoarciniega.com/normas-y-estandares-de-calidad-para-el-desarrollo-de-software/)

