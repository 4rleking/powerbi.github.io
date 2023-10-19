---
layout: single
title: Power BI Desktop
excerpt: "Power BI Desktop es una aplicación gratuita que permite su instalación en el equipo local y que a su vez permite la conexión a los datos, su transformación y visualización. Este suele ser usado en el ámbito de la inteligencia empresarial, sobre todo en la creación de informes, donde posteriormente usan el servicio de Power BI para compartir estos informes."
date: 2023-08-30
classes: wide
header:
  teaser: /assets/images/Desktop/Intro1.jpg
  teaser_home_page: true
categories:
  - 
tags:
  - 
---

![](/assets/images/Desktop/Intro2.jpg)

`Power BI Desktop` es una aplicación gratuita que se puede instalar en el equipo local y que permite conectarse a los datos, transformarlos y visualizarlos. Con *Power BI Desktop*, puede conectarse a varios orígenes de datos diferentes y combinarlos (lo que se suele denominar modelado) en un modelo de datos. Este modelo de datos permite compilar objetos visuales y colecciones de objetos visuales que puede compartir como informes, con otras personas de su organización. La mayoría de los usuarios que trabajan en proyectos de inteligencia empresarial usan *Power BI Desktop* para crear informes y luego usan el *servicio Power BI* para compartir los informes con otros.

Los usos más comunes de Power BI Desktop son los siguientes:

* Establecer conexión con los datos.
* Transformar y limpiar datos para crear un modelo de datos.
* Crear objetos visuales, como gráficos o grafos, que proporcionan representaciones visuales de los datos.
* Crear informes que son colecciones de objetos visuales, en una o varias páginas de informes.
* Compartir informes con otros usuarios mediante el servicio Power BI.

Los usuarios que son responsables de esas tareas se suelen considerar analistas de datos (a los que a veces se hace referencia con el término analistas) o profesionales de inteligencia empresarial (a menudo conocidos como creadores de informes). Muchas personas que no se consideran analistas ni creadores de informes usan *Power BI Desktop* para crear informes atractivos o para extraer datos de varios orígenes. Pueden crear modelos de datos que luego pueden compartir con sus compañeros de trabajo y organizaciones.

```text
Importante
Power BI Desktop se actualiza y se publica mensualmente, incorporando comentarios de los clientes y características
nuevas. Solo se admite la versión más reciente de Power BI Desktop; a los clientes que se pongan en contacto con el servicio de soporte técnico de Power BI Desktop se les pedirá que actualicen su versión a la más reciente. Puede obtener la versión más reciente de Power BI Desktop desde Microsoft Store, o bien como un único archivo ejecutable con todos los idiomas admitidos que debe descargar e instalar en el equipo.
```

En Power BI Desktop hay tres vistas disponibles, que se seleccionan en el lado izquierdo del lienzo. Las vistas, que se muestran en el orden en que aparecen, son las siguientes:

* `Informe`. Crea informes y objetos visuales y es donde se pasa la mayor parte del tiempo de creación.
* `Datos`. Se ven las tablas, las medidas y los demás datos que se usan en el modelo de datos asociado al informe y se transforman los datos para usarlos de la mejor manera posible en el modelo del informe.
* `Modelo`. Ve y administra las relaciones entre las tablas del modelo de datos.

## Conectar a datos

Para empezar a trabajar con Power BI Desktop, el primer paso es conectarse a los datos. Hay muchos orígenes de datos distintos a los que es posible conectarse desde Power BI Desktop.

Para conectarse a los datos:

1. En la cinta Inicio, seleccione Obtener datos>Más.
    * Aparece la ventana Obtener datos, que muestra muchas categorías a las que Power BI Desktop puede conectarse.
2. Cuando se selecciona un tipo de datos, se le pide información, como la dirección URL y las credenciales, necesaria para que Power BI Desktop se conecte al origen de datos en su nombre.
3. Una vez conectado a uno o más orígenes de datos, puede que quiera transformar los datos para que le resulten útiles.

## Transformación y limpieza de datos y creación de un modelo

En Power BI Desktop, puede limpiar y transformar los datos con el [Editor de Power Query integrado](https://learn.microsoft.com/es-es/power-bi/transform-model/desktop-query-overview). Con el Editor de Power Query, puede realizar modificaciones en los datos, como cambiar un tipo de datos, quitar columnas o combinar datos de varios orígenes. Es como esculpir: se empieza con un gran bloque de barro (o datos), luego se quitan trozos o se agregan otros según sea necesario, hasta que los datos adoptan la forma deseada.

Para iniciar el Editor de Power Query:

* En la sección Consultas de la cinta Inicio, seleccione Transformar datos.
* Aparece la ventana Editor de Power Query.

Cada paso que se da para transformar datos (como cambiar el nombre de una tabla, transformar un tipo de datos o eliminar una columna) se registra con el Editor de Power Query. Cada vez que esta consulta se conecta al origen de datos, se ejecutan esos pasos de modo que los datos siempre tengan la forma especificada.

En la imagen siguiente se muestra la ventana Editor de Power Query de una consulta a la que se dio forma y se ha convertido en un modelo.

Una vez que los datos tienen la forma deseada, puede crear objetos viduales.

## Creación de objetos visuales

Una vez que se tiene un modelo de datos, se pueden arrastrar campos al lienzo del informe para crear objetos visuales. Un objeto visual es una representación gráfica de los datos del modelo. Hay muchos tipos diferentes de objetos visuales entre los que elegir en Power BI Desktop. En el siguiente objeto visual se muestra un gráfico de columna simple.

Para crear o cambiar un objeto visual:

* En el panel Visualizaciones, seleccione el icono Crear objeto visual.

Si ya tiene un objeto visual seleccionado en el lienzo del informe, cambia al tipo seleccionado.

Si no hay ningún objeto visual seleccionado en el lienzo, se crea un nuevo objeto visual en función de la selección.

## Crear informes

Lo más frecuente es que quiera crear una colección de objetos visuales que muestre diversos aspectos de los datos usados para crear el modelo en Power BI Desktop. A una colección de objetos visuales, en un archivo de Power BI Desktop, se le denomina informe. Un informe puede tener una o varias páginas, al igual que un archivo de Excel puede tener uno o varias hojas de cálculo.

Con Power BI Desktop, puede crear informes complejos y de gran riqueza visual mediante los datos de varios orígenes, todo en un informe que se puede compartir con otros usuarios de la organización.

En la siguiente imagen se ve la primera página de un informe de Power BI Desktop denominado Información general, como se observa en la pestaña situada en la parte inferior de la imagen.

## Compartir informes

Una vez que está listo para compartir con otras personas, puede publicar el informe en el servicio Power BI y ponerlo a disposición de cualquier persona de la organización que tenga una licencia de Power BI.

Para publicar un informe de Power BI Desktop:

1. Seleccione Publicar en la cinta Inicio. Power BI Desktop se conecta al servicio Power BI con la cuenta de Power BI.
2. Se le pedirá que seleccione dónde quiere compartir el informe en el servicio Power BI. Por ejemplo, el área de trabajo, un área de trabajo de equipo o alguna otra ubicación del servicio Power BI.

Debe tener una licencia de Power BI para compartir informes en el servicio Power BI.

## Pasos siguientes

Para empezar a trabajar con Power BI Desktop, lo primero que necesita es descargar e instalar la aplicación. Hay varias maneras de obtener Power BI Desktop:

* [Obtención de Power BI Desktop desde Microsoft Store](https://aka.ms/pbidesktopstore)
* [Obtener Power BI Desktop](https://learn.microsoft.com/es-es/power-bi/fundamentals/desktop-get-the-desktop)
* [Descargar Power BI Desktop desde la Web](https://www.microsoft.com/download/details.aspx?id=58494)
