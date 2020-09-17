# Empresas identificadas 

## ![Image](https://github.com/E3-Semana-Tec/ReporteAvances/blob/master/Imagenes/tesla-logo-text-png-7_opt.png)
(Aqui debemos poner el texto que conteste estas preguntas para tesla)
- ¿Qué empresa es? ¿En qué sector se encuentra?
- ¿En qué consiste su modelo de uso de IoT? ¿Es una App, una plataforma en la nube, etc.)?
- ¿Qué problemática o necesidad resuelve?

[Contestar aquí]

## ![Image](https://github.com/E3-Semana-Tec/ReporteAvances/blob/master/Imagenes/att-logo1_opt.png)


A continuación, se presenta una colaboración entre tres empresas para desarrollar un nuevo servicio más eficiente e innovador para los consumidores. 

Se trata de la empresa de automóviles, KIA MOTORS quien implementó en su aplicación móvil “MyKIA+”, un nuevo servicio de recuperación de sus automóviles en caso de robo o emergencias. Es precisamente AT&T, quien proporciona sus herramientas y servicios como lo es su plataforma: Control Center, diseñada para facilitar la administración de soluciones IoT. Cabe mencionar que RESSER es la encargada de trabajar en el servicio de localización satelital para conocer la ubicación exacta y en tiempo real de cualquier automóvil KIA.

De esta forma, Find My Kia ayuda a todos los clientes de KIA Motors en la recuperación de sus automóviles en caso de robo, disminuyendo los índices de este delito y proporcionando seguridad al adquirir un automóvil KIA. 

Para saber más: [link](https://www.att.com.mx/newsroom/noticia/att-conecta-el-nuevo-desarrollo-de-kia-motors)


## ![Image](https://github.com/E3-Semana-Tec/ReporteAvances/blob/master/Imagenes/1280px-Oracle_logo_opt.png)
(Aqui debemos poner el texto que conteste estas preguntas para Oracle)
- ¿Qué empresa es? ¿En qué sector se encuentra?
- ¿En qué consiste su modelo de uso de IoT? ¿Es una App, una plataforma en la nube, etc.)?
- ¿Qué problemática o necesidad resuelve?

[Contestar aquí]

## ![Image](https://github.com/E3-Semana-Tec/ReporteAvances/blob/master/Imagenes/qualcomlogo.png)


Qualcomm es una compañía estadounidense que produce chipsets para la tecnología móvil CDMA y W-CDMA, son los creadores y diseñadores de los procesadores Snapdragon, también es responsable del cliente de correo electrónico Eudora. Entre sus principales productos está Brew, es una plataforma que permite la creación de aplicaciones para dispositivos móviles y Qchat. Es uno de los principales suministradores de la familia de procesadores para teléfonos inteligentes Snapdragon. Es un desarrollador de semiconductores para redes y comunicaciones, Qualcomm Atheros. También fabrica un sistema de recarga inalámbrica de vehículos eléctricos (Wireless Electric Vehicle Charging - WEVC) denominado Qualcomm Halo, esta compañía se encuentra sujeta al sector de las Nuevas Tecnologías de la Información y la Comunicación (TIC), el cual está compuesto por los sectores manufactureros y de servicios cuya actividad principal está ligada al desarrollo, producción, comercialización y uso intensivo de las mismas, dado que conecta con sus contactos clave, proyectos, accionistas y noticias relacionadas. 

Su modelo en el que utilizan el internet de las cosas (IOTS) es brindando ayuda a sus clientes para poder comercializar sus productos de una manera más rápida y con costos beneficiosos para ambas partes de esa manera solucionan la problemática, utilizando plataformas optimizadas en las áreas de cuerpos inteligentes, hogares inteligentes y ciudades inteligentes.


# El modelo de uso de IoT seleccionado colaborativamente. (esto se removera al finalizar el llenado, apliquen el mismo formato que en las anteriores)
- ¿Cuál fue el criterio y/o metodología de selección empleado por el equipo?
- ¿Quiénes son los usuarios, clientes o beneficiarios de este modelo?
- ¿Cuál es la propuesta de valor para estos públicos?
- ¿Cuál es el proceso que involucra a estos públicos?
- ¿Qué datos se generan y registran durante este proceso?

[Contestar aquí]

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

