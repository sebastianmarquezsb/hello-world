# hello-world

El proyecto Hello World es una tradición tradicional en la programación de computadoras. Es un ejercicio simple que te ayuda a comenzar a aprender algo nuevo. ¡Comencemos con GitHub!

Aprenderás a:

Crear y usar un repositorio
Iniciar y administrar una nueva sucursal
Realizar cambios en un archivo y enviarlos a GitHub como confirmaciones
Abrir y fusionar una solicitud de extracción

¿Qué es el GitHub?
GitHub es una plataforma de alojamiento de código para el control de versiones y la colaboración. Te permite a ti y a otros trabajar juntos en proyectos desde cualquier lugar.

Este tutorial le enseña los elementos esenciales de GitHub como repositorios , ramas , confirmaciones y solicitudes de extracción . Creará su propio repositorio Hello World y aprenderá el flujo de trabajo Pull Request de GitHub, una forma popular de crear y revisar código.

No es necesario codificar
Para completar este tutorial, necesita una cuenta de GitHub.com y acceso a Internet. No necesita saber cómo codificar, usar la línea de comandos o instalar Git (el software de control de versiones en el que se basa GitHub).

Consejo: Abra esta guía en una ventana (o pestaña) del navegador separada para que pueda verla mientras completa los pasos del tutorial.


Paso 1. Crear un repositorio
Un repositorio se usa generalmente para organizar un solo proyecto. Los repositorios pueden contener carpetas y archivos, imágenes, videos, hojas de cálculo y conjuntos de datos, cualquier cosa que su proyecto necesite. Recomendamos incluir un archivo README o un archivo con información sobre su proyecto. GitHub facilita agregar uno al mismo tiempo que crea su nuevo repositorio. También ofrece otras opciones comunes, como un archivo de licencia.

Su hello-worldrepositorio puede ser un lugar donde almacenar ideas, recursos o incluso compartir y discutir cosas con otros.

Para crear un nuevo repositorio
En la esquina superior derecha, junto a su avatar o icono de identificación, haga clic en y luego seleccione Nuevo repositorio .
Nombra tu repositorio hello-world.
Escribe una breve descripción.
Seleccione Inicializar este repositorio con un archivo README .
nueva-repo-forma

Haga clic en Crear repositorio .


Paso 2. Crear una rama
La ramificación es la forma de trabajar en diferentes versiones de un repositorio a la vez.

Por defecto, su repositorio tiene una rama llamada masterque se considera la rama definitiva. Usamos ramas para experimentar y hacer ediciones antes de comprometerlas master.

Cuando crea una rama fuera de la masterrama, está haciendo una copia, o una instantánea, de masterlo que era en ese momento. Si alguien más realizó cambios en la mastersucursal mientras trabajaba en su sucursal, podría obtener esas actualizaciones.

Este diagrama muestra:

La masterrama
Una nueva rama llamada feature(porque estamos haciendo 'trabajo de características' en esta rama)
El viaje que featuretoma antes de fusionarse conmaster
una rama

¿Alguna vez has guardado diferentes versiones de un archivo? Algo como:

story.txt
story-joe-edit.txt
story-joe-edit-reviewed.txt
Las sucursales logran objetivos similares en los repositorios de GitHub.

Aquí en GitHub, nuestros desarrolladores, escritores y diseñadores usan sucursales para mantener las correcciones de errores y el trabajo de características separadas de nuestra mastersucursal (de producción). Cuando un cambio está listo, fusionan su rama master.

Para crear una nueva sucursal
Ve a tu nuevo repositorio hello-world.
Haga clic en el menú desplegable en la parte superior de la lista de archivos que dice branch: master .
Escriba un nombre de rama readme-edits, en el cuadro de texto de la nueva rama.
Seleccione el cuadro azul Crear rama o presione "Enter" en su teclado.
gif de rama

Ahora tienes dos ramas, mastery readme-edits. ¡Se ven exactamente iguales, pero no por mucho tiempo! A continuación, agregaremos nuestros cambios a la nueva sucursal.


Paso 3. Realizar y confirmar cambios
¡Bravo! Ahora, está en la vista de código para su readme-editssucursal, que es una copia de master. Hagamos algunas ediciones.

En GitHub, los cambios guardados se llaman confirmaciones . Cada confirmación tiene un mensaje de confirmación asociado , que es una descripción que explica por qué se realizó un cambio en particular. Los mensajes de confirmación capturan el historial de sus cambios, para que otros contribuyentes puedan entender lo que ha hecho y por qué.

Realizar y confirmar cambios
Haz clic en el README.mdarchivo.
Haga clic en el  icono de lápiz en la esquina superior derecha de la vista de archivo para editar.
En el editor, escribe un poco sobre ti.
Escriba un mensaje de confirmación que describa sus cambios.
Haga clic en el botón Confirmar cambios .
cometer

Estos cambios se realizarán solo en el archivo README de su readme-editsrama, por lo que ahora esta rama contiene contenido diferente master.


Paso 4. Abra una solicitud de extracción
¡Buenas ediciones! Ahora que tiene cambios en una rama master, puede abrir una solicitud de extracción .

Las solicitudes de extracción son el corazón de la colaboración en GitHub. Cuando abre una solicitud de extracción , está proponiendo sus cambios y solicitando que alguien revise y extraiga su contribución y los combine en su rama. Las solicitudes de extracción muestran diferencias o diferencias del contenido de ambas ramas. Los cambios, sumas y restas se muestran en verde y rojo.

Tan pronto como realice una confirmación, puede abrir una solicitud de extracción e iniciar una discusión, incluso antes de que finalice el código.

Al usar el sistema @mention de GitHub en su mensaje de solicitud de extracción, puede solicitar comentarios de personas o equipos específicos, ya sea que estén al final del pasillo o a 10 zonas horarias de distancia.

Incluso puede abrir solicitudes de extracción en su propio repositorio y fusionarlas usted mismo. Es una excelente manera de aprender el flujo de GitHub antes de trabajar en proyectos más grandes.

Abra una solicitud de extracción para cambios en el archivo README
Haga clic en la imagen para una versión más grande

Paso	Captura de pantalla
Haga clic en el  Ficha Solicitud de extracción , luego, desde la página Solicitud de extracción , haga clic en el botón verde Nueva solicitud de extracción .	pr-tab
En el cuadro Comparaciones de ejemplo , seleccione la rama que hizo readme-editspara comparar con master(el original).	rama
Revise sus cambios en los diferenciales en la página Comparar, asegúrese de que sean lo que desea enviar.	diff
Cuando esté satisfecho de que estos son los cambios que desea enviar, haga clic en el botón verde grande Crear solicitud de extracción.	crear-tirar
Dé un título a su solicitud de extracción y escriba una breve descripción de sus cambios.	forma de pr
Cuando haya terminado con su mensaje, haga clic en Crear solicitud de extracción .

Consejo : puede usar emoji y arrastrar y soltar imágenes y gifs en comentarios y solicitudes de extracción.


Paso 5. Combine su solicitud de extracción
En este paso final, es hora de reunir sus cambios, fusionando su readme-editsrama en la masterrama.

Haga clic en el botón verde de solicitud de extracción Merge para fusionar los cambios master.
Haz clic en Confirmar fusión .
Continúe y elimine la rama, ya que sus cambios se han incorporado, con el botón Eliminar rama en el cuadro morado.
unir Eliminar

¡Celebrar!
¡Al completar este tutorial, ha aprendido a crear un proyecto y hacer una solicitud de extracción en GitHub!

Esto es lo que logró en este tutorial:

Creó un repositorio de código abierto
Comencé y administré una nueva sucursal
Cambió un archivo y confirmó esos cambios en GitHub
Abrió y fusionó una solicitud de extracción
¡Eche un vistazo a su perfil de GitHub y verá sus nuevos cuadrados de contribución !

Para obtener más información sobre el poder de las solicitudes de extracción, recomendamos leer la Guía de flujo de GitHub . También puede visitar GitHub Explore e involucrarse en un proyecto de código abierto.

Consejo : Consulte nuestras otras Guías , Canal de YouTube y Capacitación a pedido para obtener más información sobre cómo comenzar a usar GitHub.
