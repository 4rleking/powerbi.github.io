---
layout: single
title: Introducción
excerpt: "Power BI es una colección de servicios de software, aplicaciones y conectores que funcionan conjuntamente para convertir orígenes de datos sin relación entre sí en información coherente, interactiva y atractiva visualmente."
date: 2023-08-11
classes: wide
header:
  teaser: /assets/images/Introduccion/Intro1.png
  teaser_home_page: true
categories:
  - 
tags:
  - 
---

![](/assets/images/Introduccion/Intro2.jpg)

La historia de `Power BI` comenzó en el 2006 en Microsoft bajo el nombre de proyecto `Gemini`. El objetivo de este proyecto era el de integrar el poder de *SQL Server Analysis Services (SSAS)* en Excel. Más tarde se le conocería como PowerPivot.

En el 2012, se lanza `Power View`, una herramienta de visualizaciones dinámicas que se une el ecosistema de Power BI.

En el 2013 Microsoft lanza `Power Query` que permitía a través de un *add-in* conectar Excel y Powerpivot con múltiples fuentes de información.

Con esto se promueve la adopción generalizada de estos complementos para Excel, pero le seguía faltando una pieza al rompecabezas de Power BI.

En Julio del 2015 Microsoft lanza `Powerbi.com`, una solución *SaaS* basada en la nube que permite analizar datos y compartir información en cualquier dispositivo a través de la web.

```text
"En resúmen, Power BI no es algo nuevo o poco probado. Se ha estado cocinando lentamente por los últimos diez años.
Combina la tecnología de el software de administración de datos mas usado del mundo (SQL Server) con el software
de BI más popular del planeta (Excel) y mucho más".
```

Sus datos podrían ser una hoja de cálculo de Excel o una colección de almacenes de datos híbridos locales y basados en la nube. Power BI permite conectarse con facilidad a los orígenes de datos, visualizar y descubrir qué es importante y compartirlo con cualquiera o con todos los usuarios que desee.

## Las partes de Power BI

Power BI consta de varios elementos que funcionan de manera conjunta, empezando por estos tres conceptos básicos:

* Aplicación de escritorio de Windows llamada Power BI Desktop.
* Servicio de software como servicio (SaaS) en línea denominado servicio Power BI.
* Aplicaciones para Power BI Mobile para dispositivos Windows, iOS y Android.

Estos tres elementos (Power BI Desktop, el servicio y las aplicaciones móviles) están diseñados para permitirle crear, compartir y usar información empresarial de la forma que le resulte más eficaz para usted y para su rol.

Además de estos tres elementos, Power BI también incluye otros dos:

* Power BI Report Builder, para crear informes paginados y compartirlos en el servicio Power BI. Obtenga más información sobre los informes paginados más adelante en este artículo.
* Power BI Report Server, un servidor de informes local en el que puede publicar los informes de Power BI, después de crearlos en Power BI Desktop. Obtenga más información sobre Power BI Report Server más adelante en este artículo.

## Adaptación de Power BI a su rol

La forma de utilizar Power BI depende del rol en un proyecto o equipo. Es posible que otros usuarios con otros roles usen Power BI de forma diferente.

Por ejemplo, podría utilizar principalmente el servicio Power BI para ver informes y paneles. Un compañero de trabajo, dedicado a procesar números y crear informes empresariales, podría usar ampliamente Power BI Desktop o Power BI Report Builder para crear informes y, después, publicarlos en el servicio Power BI, donde puede verlos. Otro compañero de trabajo, del departamento de ventas, podría usar principalmente la aplicación para Power BI Mobile con el fin de supervisar el progreso de las cuotas de venta y profundizar en los detalles de nuevos clientes potenciales.

Si es un desarrollador, puede usar las API de Power BI para insertar datos en conjuntos de datos o para insertar informes y paneles en sus propias aplicaciones personalizadas. ¿Tiene alguna idea de un nuevo objeto visual? Compílelo usted mismo y compártalo con los demás.

También podría usar cada elemento de Power BI en distintos momentos, en función de los objetivos o de su rol en un proyecto determinado.

Su modo de usar Power BI puede basarse en la característica o servicio de Power BI que es la mejor herramienta para su situación. Por ejemplo, puede usar Power BI Desktop para crear informes para el equipo sobre estadísticas de involucración de los clientes y ver el progreso de inventario y fabricación en un panel en tiempo real en el servicio Power BI. Puede crear un informe paginado de facturas para enviar por correo, en función de un conjunto de datos de Power BI. Cada una de las partes de Power BI está a su disposición, razón por la cual es tan flexible e interesante.

## El flujo de trabajo en Power BI

Un flujo de trabajo habitual en Power BI comienza con la conexión a orígenes de datos en Power BI Desktop y la creación de un informe. Después, ese informe se publica desde Power BI Desktop en el servicio Power BI y se comparte para que los usuarios profesionales del servicio Power BI y los dispositivos móviles puedan verlo e interactuar con él.

Este flujo de trabajo es habitual y muestra cómo los tres elementos principales de Power BI se complementan entre sí.

## Uso de la herramienta de canalización de implementación

En el servicio Power BI, puede usar la herramienta de canalización de implementación para probar el contenido antes de publicarlo para los usuarios. La herramienta de canalización de implementación puede ayudarle a implementar informes, paneles, conjuntos de datos e informes paginados. Obtenga información sobre cómo empezar a trabajar con las canalizaciones de implementación en el servicio Power BI.

## Informes paginados en el servicio Power BI

Otro flujo de trabajo implica informes paginados en el servicio Power BI. Los creadores de informes empresariales diseñan informes paginados para imprimirlos o compartirlos. También pueden compartir estos informes en el servicio Power BI. Se denominan paginados porque presentan un formato apto para encajar en una página. A menudo se usan para informes operativos, o bien para imprimir formularios como facturas o transcripciones. Muestran todos los datos en una tabla, incluso si esta abarca varias páginas. Power BI Report Builder es la herramienta independiente para crear informes paginados.

## Elaboración de informes en el entorno local con Power BI Report Server

¿Qué ocurre si tiene que mantener los informes en un entorno local, por ejemplo, detrás de un firewall? Siga leyendo.

Puede crear, implementar y administrar informes de Power BI en Power BI Desktop e informes paginados en Report Builder, con las herramientas y servicios listos para usar que proporciona Power BI Report Server.

Power BI Report Server es una solución que se implementa detrás del firewall y entrega informes a los usuarios correspondientes de diferentes maneras, que pueden ser para visualizarlos en un explorador web, en un dispositivo móvil o como correo electrónico. Además, como Power BI Report Server es compatible con Power BI en la nube, puede pasarse a la nube cuando esté listo.
