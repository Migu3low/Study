# Fundamentos

## Configuración e inicio:
- Instalar segun SO
### Exploración de Docker Desktop:
![Docker Desktop](images/docker_desktop.png)
¿Cómo navegar por la interfaz de Docker Desktop?
Docker Desktop es una herramienta fundamental para los desarrolladores que desean optimizar sus procesos de desarrollo y despliegue de aplicaciones. Al abrir Docker Desktop, te encontrarás con una pantalla que puede parecer abrumadora al principio, pero conocer su estructura te permite aprovechar al máximo esta potente herramienta.

¿Qué es el Learning Center?
El Learning Center es una de las secciones más valiosas de Docker Desktop. Aquí puedes encontrar información y consejos útiles sobre cómo trabajar con diferentes lenguajes de programación en Docker. Las categorías más utilizadas están fácilmente accesibles, proporcionando guías y ejemplos para comenzar a experimentar con Docker. Sin embargo, no se limita solo a los lenguajes más populares, ya que puedes explorar una variedad más amplia de herramientas compatibles.

¿Cuáles son las secciones clave de Docker Desktop?
Contenedores: Esta es una de las áreas que más utilizarás. A medida que avances en tu aprendizaje y desarrollo, irás llenando esta sección con múltiples contenedores creados para tus proyectos.

Imágenes: Posee tres categorías principales:

Local: Imágenes almacenadas en tu máquina.
Remota: Imágenes disponibles en Docker Hub.
Artefactos: Incluye opciones como “Early Access” que merecen consideración antes de uso extensivo.
Docker Scout: Una herramienta que te permite analizar cómo se están desplegando tus imágenes, incluso antes de ser creadas como contenedores.

Ambientes de Desarrollo o Dev Environments: Aunque está en fase beta, se destaca por su capacidad para uniformizar las herramientas utilizadas por los desarrolladores, asegurando la coherencia en el uso de versiones de programas y configuraciones.

Volúmenes: Funcionan como unidades de almacenamiento externo que tus contenedores y sistema operativo pueden utilizar. Son especialmente útiles para compartir recursos, como archivos de video, entre el sistema operativo anfitrión y los contenedores Docker.

¿Cómo configurar y utilizar Docker Desktop?
En la parte superior derecha de Docker Desktop, encontrarás un engranaje que te lleva a la configuración. Aquí puedes ajustar desde elementos estéticos, como el tema de color, hasta configuraciones más avanzadas.

Integración con WSL (Windows Subsystem for Linux): En Windows, es crucial habilitar la opción de usar WSL para crear una comunicación efectiva entre Docker y tus contenedores.

Actualizaciones: Docker Desktop se actualiza automáticamente, lo cual es vital para estar al tanto de las últimas características y mejoras. Asegúrate de que esta opción esté habilitada para evitar lapsos en las actualizaciones.

En resumen, aunque Docker Desktop cuenta con una interfaz gráfica completa, es importante recordar que la línea de comandos sigue siendo un componente esencial. La interfaz permite ejecutar comandos equivalentes con clics, pero dominar ambas formas enriquecerá tu experiencia como desarrollador. ¡Sigue explorando y experimentando para dominar Docker Desktop por completo!

# Linea de comandos:

¿Cómo interactuar con Docker desde la línea de comandos?
Docker es una herramienta poderosa para gestionar contenedores, y puede ser utilizada tanto desde una interfaz gráfica como desde la línea de comandos. Dominando la línea de comandos, no solo tienes un control más detallado sobre las tareas, sino que también puedes automatizar procesos y trabajar eficientemente en entornos sin interfaz gráfica. Exploremos algunas de las funcionalidades básicas para manejar Docker desde la terminal.

¿Cómo verificar la instalación de Docker?
Lo primero que debes hacer una vez instalado Docker es asegurarte de que todo está funcionando correctamente. Un comando esencial para esto es:

`docker version`
Este comando te mostrará la versión de Docker instalada y confirmará que la línea de comandos tiene acceso al motor de Docker.

¿Qué información proporciona docker info?
Para obtener una visión más detallada del entorno en el que Docker opera, puedes usar:

`docker info`
Este comando te dará detalles sobre el hardware que Docker está utilizando, como la memoria, el procesador y posibles configuraciones de la GPU. Esta información es crucial si estás considerando optimizar los recursos de hardware para un mejor rendimiento.

¿Cómo gestionar imágenes y contenedores?
Docker organiza todo en imágenes y contenedores, y es vital entender cómo gestionar estos elementos desde la línea de comandos para un manejo eficiente.

¿Cómo listar tus imágenes?
Para ver todas las imágenes disponibles en tu entorno local, el comando a utilizar es:

`docker images`
Este listado es análogo al que verías en la sección de imágenes de Docker Desktop, y es una herramienta esencial para mantener un seguimiento de las imágenes que tienes disponibles.

¿Cómo ver los contenedores activos?
Para controlar y ver todos los contenedores que están activos en tu entorno de Docker, debes usar:

`docker ps`
Este comando te proporciona información sobre los contenedores que están corriendo, similar a lo que verías en la sección de contenedores en Docker Desktop.

¿Cómo obtener ayuda para comandos específicos?
Docker cuenta con una extensa documentación que es fundamental para el aprendizaje y el uso eficiente de sus comandos. Para explorar las opciones de un comando específico, utiliza la opción help.

¿Cómo usar help para comandos?
Si bien Docker no tiene una lista infinita de comandos, cada uno de ellos tiene múltiples parámetros que pueden personalizarse. Por ejemplo:

Para obtener ayuda sobre el comando docker build:
`docker build --help`
Para el comando docker run:
`docker run --help`
Esta función es increíblemente útil para descubrir y entender los diversos parámetros disponibles para cada comando, sin necesidad de memorizar todo.

Recomendaciones para mejorar tu experiencia con Docker
Aquí te ofrecemos algunos consejos prácticos para que puedas sacar el máximo provecho de Docker:

Explora ambas interfaces: Experimenta tanto con la línea de comandos como con Docker Desktop, y decide cuál se adapta mejor a tu estilo de trabajo.
Consulta la documentación regularmente: La documentación es tu mejor aliado para aprender y recordar funciones y parámetros.
Automatiza procesos: Aprende a crear scripts que te permitan automatizar tareas repetitivas usando la línea de comandos.
Recuerda, la práctica constante con Docker y la exploración de sus múltiples funcionalidades te ayudarán a dominar esta herramienta y a convertirte en un experto en la gestión de contenedores. La eficiencia y el conocimiento vienen con el uso continuo y la curiosidad por aprender más. ¡Sigue explorando!
