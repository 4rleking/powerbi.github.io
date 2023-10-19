---
layout: single
title: Conceptos básicos para los diseñadores en el servicio Power BI
excerpt: ""
date: 2023-08-23
classes: wide
header:
  teaser: /assets/images/
  teaser_home_page: true
categories:
  - 
tags:
  - 
---

![](/assets/images/)

El objetivo de este artículo es que se familiarice con el servicio Power BI: cuáles son los diferentes elementos, cómo funcionan conjuntamente y cómo puede trabajar con ellos. Podrá aprovechar este artículo al máximo si ya se ha [registrado](https://learn.microsoft.com/es-es/power-bi/fundamentals/service-self-service-signup-for-power-bi) en el servicio Power BI y ha [agregado](https://learn.microsoft.com/es-es/power-bi/connect-data/service-get-data) algunos datos. Como diseñador, su flujo de trabajo típico consiste normalmente en empezar creando informes en Power BI Desktop. A continuación, los publica en el servicio Power BI, donde puede continuar modificándolos. También usa el servicio Power BI para crear los paneles basados en los informes.

En este artículo, si aún no tiene sus propios informes, instale uno de los [ejemplos](https://learn.microsoft.com/es-es/power-bi/create-reports/sample-datasets) de Power BI.

Cuando abra el servicio Power BI en un explorador, empezará en su pantalla Inicio. Estos son los elementos que puede ver:

1. Panel de navegación
2. Iniciador de aplicaciones de Microsoft 365
3. Botón Inicio de Power BI
4. Botones de iconos, incluidos los de configuración, ayuda y comentarios
5. Cuadro de búsqueda
6. Contenido recomendado que se usa más o que marcó como favorito
7. Pestañas Recientes, Favoritos y Mis aplicaciones

Usted y los usuarios finales de sus informes y paneles tienen la misma experiencia de inicio en el servicio Power BI de un explorador.

Más adelante se explicarán estas características de forma detallada, pero primero analizaremos algunos conceptos de Power BI. O bien, es posible que desee ver este vídeo primero. En el vídeo, Will da un repaso a los conceptos básicos y muestra el servicio Power BI.

## Conceptos de Power BI

Los bloques de creación principales de Power BI son los paneles, los informes, los libros, los conjuntos de datos, los flujos de datos y las aplicaciones. Todos se organizan en áreas de trabajo y se crean en las capacidades. Es importante comprender qué son las áreas de trabajo y las capacidades antes de profundizar en los bloques de creación, así que vamos a empezar por ahí.

### Capacidades

Las capacidades son un concepto básico de Power BI que representa un conjunto de recursos (almacenamiento, procesador y memoria) que se usan para hospedar y facilitar el contenido de Power BI. Las capacidades son compartidas o reservadas. Una capacidad compartida es la que se comparte con otros clientes de Microsoft, mientras que una reservada es para un solo cliente. Las capacidades reservadas necesitan una [suscripción](https://learn.microsoft.com/es-es/power-bi/enterprise/service-premium-what-is) y se describen detalladamente en [Administración](https://learn.microsoft.com/es-es/power-bi/enterprise/service-premium-capacity-manage) de las capacidades Premium.

De manera predeterminada, las áreas de trabajo se crean en una capacidad compartida. En la capacidad compartida, las cargas de trabajo se ejecutan en recursos informáticos compartidos con otros clientes. Como la capacidad debe compartir recursos, se imponen ciertas limitaciones para garantizar un "juego limpio", como un tamaño de modelo máximo (1 GB) y una frecuencia de actualización diaria máxima (ocho veces al día).

### Áreas de trabajo

Las áreas de trabajo se crean en las capacidades. Básicamente, son contenedores de paneles, informes, aplicaciones, libros, conjuntos de datos y flujos de datos en Power BI.

Existen dos tipos de áreas de trabajo: Mi área de trabajo y las áreas de trabajo.

* Mi área de trabajo es el área de trabajo personal de cualquier cliente de Power BI en la que puede trabajar con su contenido. Solo usted tiene acceso a esta área de trabajo. Puede compartir paneles e informes desde Mi área de trabajo. Si desea colaborar en paneles e informes o crear una aplicación, querrá trabajar en un área de trabajo.
* Las áreas de trabajo se usan para colaborar y compartir el contenido con los compañeros. Puede agregar compañeros a las áreas de trabajo y colaborar en paneles, informes, aplicaciones, libros y conjuntos de datos. Con solo una excepción*, cada miembro del área de trabajo necesita una licencia de Power BI Pro o Premium por usuario (PPU).
  * Para más información sobre las áreas de trabajo, consulte [Creación de un área de trabajo en Power BI](https://learn.microsoft.com/es-es/power-bi/collaborate-share/service-create-the-new-workspaces).
  * Para más información sobre las licencias, consulte [Licencias por usuario y basadas en capacidad del servicio Power BI](https://learn.microsoft.com/es-es/power-bi/fundamentals/service-features-license-type).

  Las áreas de trabajo también son los lugares donde puede crear, publicar y administrar aplicaciones para su organización. Entienda las áreas de trabajo como áreas de almacenamiento provisional y contenedores del contenido que componen una aplicación de Power BI (consulte la [sección siguiente](https://learn.microsoft.com/es-es/power-bi/fundamentals/service-basic-concepts#apps)).

Para más información sobre el uso compartido en general, consulte [Formas de colaborar y compartir en Power BI](https://learn.microsoft.com/es-es/power-bi/collaborate-share/service-how-to-collaborate-distribute-dashboards-reports).

Ahora pasemos a los bloques de creación de Power BI.

### Aplicaciones

Una aplicación es una colección de paneles e informes creada para entregar las métricas clave a los consumidores de Power BI de su organización. Las aplicaciones son interactivas, pero los consumidores no pueden editarlas. Los consumidores de la aplicación (los compañeros que tienen acceso a las aplicaciones) no necesitan licencias Pro o Premium por usuario (PPU). Una aplicación puede tener permisos diferentes a los establecidos en un área de trabajo. Esta funcionalidad facilita a los diseñadores la administración de los permisos de una aplicación.

Las aplicaciones son una forma sencilla para que los diseñadores compartan muchos tipos de contenidos a la vez. Los diseñadores de aplicaciones crean paneles e informes y los agrupan en una aplicación. Los diseñadores comparten o publican la aplicación en una ubicación en la que el usuario empresarial puede acceder a ella. Es más fácil encontrar e instalar contenido en el servicio Power BI o en un dispositivo móvil cuando se ha organizado conjuntamente como una aplicación. Después de instalar una aplicación, el usuario empresarial no tendrá que recordar los nombres de varios paneles o informes porque están todos juntos en una aplicación. Puede acceder fácilmente a la aplicación en un explorador o en un dispositivo móvil.

### Flujos de datos

Un flujo de datos ayuda a las organizaciones a unificar los datos de orígenes dispares. Son opcionales y se suelen usar en proyectos complejos o grandes. Representan los datos preparados y agregados a una fase intermedia para su uso en conjuntos de datos. Los flujos de datos se muestran en Power BI Desktop con un conector dedicado para habilitar los informes. Cuando se conecta a un flujo de datos, el conjunto de datos puede utilizar los datos y la lógica empresarial previamente preparados, promoviendo un único origen de confianza y la reutilización de los datos. Usan la amplia colección de conectores de datos de Microsoft Purview, lo que permite la ingesta de datos de orígenes de datos locales y basados en la nube.

Los flujos de datos se crean y se administran solo en áreas de trabajo (pero no en Mi área de trabajo) y se almacenan como entidades en Common Data Model (CDM) en Azure Data Lake Storage Gen2. Normalmente, están programados para actualizarse de forma periódica para almacenar datos actualizados. Son ideales para preparar los datos para su uso (y para una posible reutilización) en conjuntos de datos. Para más información, consulte [Introducción a los flujos de datos y la preparación de datos de autoservicio](https://learn.microsoft.com/es-es/power-bi/transform-model/dataflows/dataflows-introduction-self-service).

Un flujo de datos se puede consumir de las tres maneras siguientes:

* Crear una tabla vinculada desde el flujo de datos para permitir que otro autor de flujo de datos use los datos.
* Crear un conjunto de datos desde el flujo de datos para permitir que un usuario emplee los datos para crear informes.
* Crear una conexión desde herramientas externas que pueden leer el formato CDM (Common Data Model).

Consumo desde Power BI Desktop: para consumir un flujo de datos, abra Power BI Desktop y seleccione flujos de datos de Power BI en el cuadro de diálogo Obtener datos.

Nota
El conector de flujos de datos de Power BI usa un conjunto de credenciales diferentes a las del usuario que ha iniciado sesión actualmente. Esto es así por diseño, para admitir usuarios de varios inquilinos.

Seleccione el flujo de datos y las tablas a las que quiere conectarse.

No se pueden tener paneles ni informes sin datos (bueno, sí se pueden tener paneles e informes vacíos, pero no serán útiles hasta que tengan datos), así es que examinemos conjuntos de datos.

#### Análisis en profundidad de los flujos de datos

* [Introducción a los flujos de datos y la preparación de datos de autoservicio](https://learn.microsoft.com/es-es/power-bi/transform-model/dataflows/dataflows-introduction-self-service).
* [Configurar y consumir un flujo de datos](https://learn.microsoft.com/es-es/power-bi/transform-model/dataflows/dataflows-configure-consume).
* [Creación de un flujo de datos](https://learn.microsoft.com/es-es/power-bi/transform-model/dataflows/dataflows-create).

### Conjuntos de datos

Un conjunto de datos es una colección de datos que importa o a lo que se conecta. Power BI permite importar y conectar con todos los tipos de conjuntos de datos y ponerlos todos en un solo lugar. Los conjuntos de datos también pueden obtener datos de flujos de datos.

Los conjuntos de datos están asociados a áreas de trabajo y un mismo conjunto de datos puede formar parte de muchas áreas de trabajo. Al abrir un área de trabajo, los conjuntos de datos asociados aparecen en la pestaña Conjuntos de datos. Cada conjunto de datos de la lista es un origen de datos disponible para uno o varios informes y puede contener datos procedentes de uno o varios orígenes (por ejemplo, un libro de Excel en OneDrive, un conjunto de datos tabular local de SSAS o un conjunto de datos de Salesforce). Hay muchos orígenes de datos compatibles diferentes y estamos agregando nuevos todo el tiempo. Consulte la lista de [tipos de conjuntos de datos](https://learn.microsoft.com/es-es/power-bi/connect-data/service-get-data) que se pueden usar con Power BI.

En el ejemplo siguiente, seleccionamos Mi área de trabajo y, después, la pestaña Conjuntos de datos y flujos de datos.

Un único conjunto de datos...

* Se puede usar una y otra vez en una o varias áreas de trabajo.
* Se puede usar en muchos informes diferentes.
* Las visualizaciones de ese conjunto de datos se pueden mostrar en muchos paneles diferentes.

Para [importar o conectarse](https://learn.microsoft.com/es-es/power-bi/connect-data/service-get-data) a un conjunto de datos, seleccione Crear en el panel de navegación. Siga las instrucciones para importar o conectarse al origen específico y agregue el conjunto de datos al área de trabajo activa. Los nuevos conjuntos de datos se marcan con un asterisco amarillo. El trabajo que realice en Power BI no cambiará el conjunto de datos subyacente.

Los conjuntos de datos que agrega un miembro del área de trabajo están disponibles para otros miembros del área de trabajo con un rol de administrador, miembro o colaborador.

Los conjuntos de datos se pueden actualizar, cambiar de nombre, explorar y eliminar. Use un conjunto de datos para crear un informe desde cero o mediante la ejecución de [información rápida](https://learn.microsoft.com/es-es/power-bi/create-reports/service-insights). Para ver qué informes y paneles ya están usando un conjunto de datos, seleccione Ver relacionados. Para explorar un conjunto de datos, selecciónelo. Lo que realmente hace es abrir el conjunto de datos en el editor de informes, donde puede empezar realmente a explorar los datos mediante la creación de visualizaciones.

Ahora pasemos a la sección siguiente: los informes.

#### Análisis en profundidad de los conjuntos de datos

* [Conjuntos de datos en el servicio Power BI](https://learn.microsoft.com/es-es/power-bi/connect-data/service-datasets-understand).
* [Modos de conjuntos de datos en el servicio Power BI](https://learn.microsoft.com/es-es/power-bi/connect-data/service-dataset-modes-understand).
* [¿Qué es Power BI Premium?](https://learn.microsoft.com/es-es/power-bi/enterprise/service-premium-what-is).
* [Orígenes de datos del servicio Power BI](https://learn.microsoft.com/es-es/power-bi/connect-data/service-get-data).
* [Obtención de ejemplos para Power BI](https://learn.microsoft.com/es-es/power-bi/create-reports/sample-datasets).

### Informes

Un informe de Power BI se compone de una o más páginas de visualizaciones, como gráficos de líneas, mapas y gráficos de rectángulos. A las visualizaciones también se les denomina objetos visuales. Todas las visualizaciones de un informe proceden de un único conjunto de datos. Usted y sus compañeros pueden crear informes desde cero, y se pueden compartir directamente con usted, ya sea en un área de trabajo o como parte de una aplicación. A veces, Power BI los crea automáticamente cuando se conecta a conjuntos de datos desde Excel, Power BI Desktop, bases de datos y aplicaciones SaaS. Por ejemplo, cuando se conecta a una aplicación SaaS, Power BI importa un informe precompilado.

Hay dos maneras de ver los informes e interactuar con ellos: Vista de lectura y vista de edición. Al abrir un informe, se abre en la vista de lectura. Si tiene permisos de edición, verá Editar informe en la esquina superior izquierda y podrá ver el informe en la vista de edición. Si un informe se encuentra en un área de trabajo, todos los usuarios con un rol de administrador, miembro o colaborador pueden editarlo. Estos usuarios tienen acceso a todas las funcionalidades de exploración, diseño, creación y uso compartido de la vista de edición del informe. Las personas con las que comparta el informe pueden explorarlo e interactuar con él mediante la vista de lectura.

Cuando se abre un área de trabajo, los informes asociados aparecen en la pestaña Contenido. Cada informe de la lista representa una o más páginas de visualizaciones basadas en solo uno de los conjuntos de datos subyacentes. Para abrir un informe, selecciónelo.

Cuando abre una aplicación, ve un panel o un informe. Si la aplicación abre un panel, para acceder a un informe subyacente, seleccione un icono del panel (se proporciona más información sobre los iconos más adelante) que se ancló desde un informe. Tenga en cuenta que no todos los iconos se anclan desde los informes, por lo que tendrá que hacer clic en unos cuantos iconos para encontrar un informe.

Si la aplicación se abre en un informe, verá una lista de páginas de informe (y, opcionalmente, un panel) al lado izquierdo.

De forma predeterminada, el informe se abre en la Vista de lectura. Simplemente seleccione Editar informe para abrirlo en la vista de edición (si tiene los permisos necesarios).

En el ejemplo siguiente, se seleccionó Mi área de trabajo y, después, la pestaña Contenido.

UN informe...

* Se encuentra en una misma área de trabajo.
* Se puede asociar con varios paneles dentro de esa área de trabajo. Los iconos anclados desde ese informe pueden aparecer en varios paneles.
* Se puede crear con los datos de un conjunto de datos. Power BI Desktop puede combinar más de un conjunto de datos en un único informe, y ese informe se puede importar en Power BI.

#### Análisis en profundidad de los informes

* [Creación de un informe a partir de un archivo de Excel en el servicio Power BI](https://learn.microsoft.com/es-es/power-bi/create-reports/service-report-create-new).
* [Acerca de los informes de Power BI optimizados para dispositivos móviles](https://learn.microsoft.com/es-es/power-bi/create-reports/power-bi-create-mobile-optimized-report-about).

### Paneles

Un panel es algo que usted crea en el servicio Power BI o que un compañero de trabajo crea en este y comparte con usted. Es un lienzo individual que contiene uno o varios iconos y widgets. Cada icono anclado desde un informe o desde [Preguntas y respuestas](https://learn.microsoft.com/es-es/power-bi/consumer/end-user-q-and-a) muestra una [visualización](https://learn.microsoft.com/es-es/power-bi/visuals/power-bi-report-visualizations) única creada a partir de un conjunto de datos y anclada al panel. Además, pueden anclarse páginas de informe completas a un panel como un único icono. Hay muchas maneras de agregar iconos al panel; demasiadas para tratarlas en este artículo de información general. Para más información, consulte [Introducción a los iconos del panel para los diseñadores de Power BI](https://learn.microsoft.com/es-es/power-bi/create-reports/service-dashboard-tiles).

¿Por qué se crean paneles? Estas son solo algunas de las razones:

* Para observar de un solo vistazo toda la información necesaria para tomar decisiones.
* Para supervisar la información más importante sobre su empresa.
* Para garantizar que todos los compañeros estén coordinados, y vean y usen la misma información;
* Para supervisar el funcionamiento correcto de un negocio, producto, unidad de negocio, campaña de marketing, entre otros.
* Para crear una vista personalizada de un panel más grande (con las métricas importantes para usted).

Cuando se abre un área de trabajo, los paneles asociados aparecen en la pestaña Contenido.

Para abrir un panel, selecciónelo. Cuando abre una aplicación, ve un panel o un informe. Cada panel representa una vista personalizada de algún subconjunto de los conjuntos de datos subyacentes. Si es el propietario del panel, también tiene acceso de edición a los conjuntos de datos e informes subyacentes. Si se compartió el panel con usted, las acciones que puede realizar van a depender de los permisos que asigna el propietario.

Hay muchas maneras diferentes mediante las que usted o un compañero de trabajo pueden compartir un panel. Se necesita Power BI Pro para compartir un panel y puede que sea necesario para ver un panel compartido.

UN panel...

* Está asociado a un área de trabajo única.
* Puede mostrar visualizaciones de muchos conjuntos de datos diferentes.
* Puede mostrar visualizaciones de muchos informes diferentes.
* Puede mostrar visualizaciones ancladas desde otras herramientas (por ejemplo, Excel).

#### Análisis en profundidad de los paneles

* [Creación de un panel de Power BI desde un informe](https://learn.microsoft.com/es-es/power-bi/create-reports/service-dashboard-create).
* [Creación de una copia de un panel en el servicio Power BI](https://learn.microsoft.com/es-es/power-bi/create-reports/service-dashboard-copy).
* [Optimización de un panel para teléfonos móviles: Power BI](https://learn.microsoft.com/es-es/power-bi/create-reports/service-create-dashboard-mobile-phone-view).

### Libros

Los libros son un tipo especial de conjunto de datos. Si leyó la sección Conjuntos de datos anterior, sabrá casi todo lo que necesita saber acerca de los libros. Pero quizás se pregunte por qué a veces Power BI clasifica un libro de Excel como un conjunto de datos y otras veces como un libro.

Cuando usa datos provenientes de archivos de Excel, puede elegir Importar los datos o Conectarse al archivo. Si elige Conectar, aparecerá el libro en Power BI como lo haría en Excel Online. Pero, a diferencia de Excel Online, puede disfrutar de algunas características fantásticas que lo ayudarán a anclar elementos de las hojas de cálculo directamente en los paneles.

No puede editar el libro en Power BI, Si necesita hacer algún cambio, seleccione Editar y, a continuación, edite el libro en Excel Online o ábralo en Excel en el equipo. Todos los cambios que realice se guardarán en el libro en OneDrive.

#### Análisis en profundidad en los libros

* [Obtención de datos de archivos de libro de Excel](https://learn.microsoft.com/es-es/power-bi/connect-data/service-excel-workbook-files).
* [Publicación en Power BI desde Microsoft Excel](https://learn.microsoft.com/es-es/power-bi/connect-data/service-publish-from-excel).

## Panel en Mi área de trabajo

Hemos analizado las áreas de trabajo, las aplicaciones y los bloques de creación. Vamos a aunarlo todo y a revisar las partes que conforman la experiencia de panel en el servicio Power BI.

### Panel de navegación

Use el panel de navegación para localizar las áreas de trabajo y los bloques de creación de Power BI y moverse entre ellos: paneles, informes, aplicaciones, libros y conjuntos de datos.

* Para agregar datos u orígenes de datos, seleccione Crear.
* Para abrir o administrar contenido favorito, contenido reciente o contenido compartido con usted, seleccione Examinar.
* Seleccione Centro de conectividad de datos para explorar los conjuntos de datos de la organización a fin de encontrar los datos que se adapten a las necesidades.
* Seleccione Métricas para hacer un seguimiento de las métricas empresariales clave.
* Vea, abra o elimine una aplicación mediante Aplicaciones.
* Para acceder al centro de conectividad de todo el aprendizaje y los ejemplos de Power BI, seleccione Aprender.
* Seleccione Áreas de trabajo para mostrar y abrir las áreas de trabajo colaborativas.
* Seleccione Mis áreas de trabajo para mostrar y abrir su área de trabajo personal.

### Lienzo

Dado que se ha abierto un panel, el área del lienzo muestra los iconos de la visualización. Si, por ejemplo, se hubiera abierto el editor de informes, el área del lienzo mostraría una página del informe.

Los paneles se componen de [iconos](https://learn.microsoft.com/es-es/power-bi/create-reports/service-dashboard-tiles). Los iconos se crean en la vista de edición del informe, en Preguntas y respuestas, y en otros paneles, y se pueden anclar desde Excel, SSRS, etc. Un tipo especial de icono, llamado [widget](https://learn.microsoft.com/es-es/power-bi/create-reports/service-dashboard-add-widget), se agrega directamente al panel. El creador o propietario de un informe colocó específicamente los iconos que aparecen en un panel. La acción de agregar un icono a un panel se denomina anclar.

### Cuadro de pregunta de Preguntas y respuestas

Una manera de explorar los datos es formular una pregunta y dejar que Preguntas y respuestas de Power BI proporcione una respuesta en forma de visualización. Se puede usar Preguntas y respuestas para agregar contenido a un panel o informe.

Preguntas y respuestas busca una respuesta en los conjuntos de datos conectados al panel. Un conjunto de datos conectado es aquel que tiene al menos un icono anclado a ese panel.

Tan pronto como empieza a escribir la pregunta, Preguntas y respuestas lo dirige a la página Preguntas y respuestas. A medida que escribe, Preguntas y respuestas le ayuda a formular la pregunta correcta y a encontrar la mejor respuesta por medio de sus funciones para reformular, autorellenar, hacer sugerencias, etc. Cuando tenga una visualización (respuesta) satisfactoria, la puede anclar al panel. Para obtener más información, vea [Preguntas y respuestas para usuarios profesionales de Power BI](https://learn.microsoft.com/es-es/power-bi/consumer/end-user-q-and-a).

### Iconos en la barra de encabezado negra

Los iconos en la esquina superior derecha son los recursos para las configuraciones, notificaciones, descargas, obtener ayuda y proporcionar comentarios al equipo de Power BI.

### Título del panel

No siempre es fácil averiguar qué área de trabajo y panel están activos, por lo que Power BI muestra el área de trabajo y el título del panel. En este ejemplo, se ve el área de trabajo (Mi área de trabajo) y el título del panel (Ejemplo de ventas y marketing). Si hubiera un informe abierto, aparecería su nombre.

### Iniciador de aplicaciones de Microsoft 365

Con el iniciador de aplicaciones, las aplicaciones de Microsoft 365 están disponibles fácilmente con un solo clic. Desde aquí, puede iniciar rápidamente el correo electrónico, los documentos, el calendario y mucho más.

### Inicio de Power BI

Si hace clic en Power BI, vuelve al inicio de Power BI.

### Iconos con etiqueta en la barra de menús gris

Esta área de la pantalla contiene más opciones para interactuar con el contenido (en este caso, con el panel). Además de los iconos etiquetados que puede ver, al seleccionar el icono Más opciones (...) se muestran opciones para ver contenido relacionado, abrir la vista de linaje, abrir métricas de uso, etc.