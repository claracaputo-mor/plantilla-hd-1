---
title: Acerca de
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/nav-menu.html sections="Sobre la edición;Sección 1;Sección 2;Sección 3;" %}

## Sobre la edición de Grupo 2


El presente trabajo se enmarca en la cursada de Humanidades Digitales 2025 en la Universidad Torcuato Di Tella. Su propósito fue llevar a cabo la digitalización del libro Lazarillo de Ciegos Caminantes, una obra del siglo XVII por Alonso Carrió de la Vandera que relata su recorrido por ciudades y pueblos de la América colonial. El autor fue un funcionario borbónico comisionado como visitador de correos entre 1771 y 1772 en el Virreinato del Perú y del Río de la Plata. En el transcurso de este cuatrimestre, fue posible realizar, de manera grupal y colaborativa, la edición y digitalización del apartado Nota (folios d7-g3) donde encontrar los comentarios, reflexiones y anotaciones hechos durante su pasaje por Buenos Aires.

El proceso de digitalización consistió de cuatro etapas. Como punto de partida, trabajamos con la materialidad del libro y recurrimos a la versión digitalizada del Lazarillo de Ciegos Caminantes, disponible en la Biblioteca Nacional de España, y la edición de texto plano en la Biblioteca Virtual Cervantes. A partir de la redacción en caracteres básicos y sin formato, fue posible comenzar con la transformación del texto histórico en su versión digital con el programa Visual Studio Code en lenguaje XML - TEI. 

Los folios se dividieron entre las cuatro integrantes, donde cada una realizó la codificación de la cantidad de páginas correspondientes, que luego unificamos en un único archivo XML - TEI. En esta segunda etapa,  se llevó a cabo la identificación de los párrafos y cambios de página conforme a la versión digitalizada. Como también marcar las notas, lugares, personajes y tablas relevantes dentro del archivo XML-TEI para que sean expresadas, etiquetadas y resaltadas de forma desplegable en la página web. 


Además, completamos y detallamos la descripción de los personajes y de notas según su “key” determinada en los documentos de Excel correspondientes. Para los lugares, realizamos la georeferenciación con coordenadas tomadas de Google Maps y la descripción de las localidades mencionadas en el relato. Una vez completado esto, cargamos al repositorio los documentos con las referencias utilizadas y, gracias a la extensión xslt-transform de Visual Studio Code, generamos archivos HTML con los datos almacenados en XML. Esto nos permitió construir nuestro sitio web estático con el software Jekyll desde la plataforma Git Hub y generar nuestra página web con la plantilla Collection Builder del HD LAB - CONICET para llevar adelante la publicación digital del apartado Nota. Es decir, generamos archivos HTML a partir de fichas XML-TEI, que nos permitieron visualizar nuestro sitio.  

En una tercera etapa, nos ocupamos de la visualización del texto. Para ello, realizamos el StoryMap donde registramos algunos lugares, elegimos imágenes y armamos el itinerario. Este StoryMap se integró al sitio web a modo de enriquecer la propia lectura e inmersión dentro del relato que acompañan los viajes realizados en la obra. 

Finalmente, en una cuarta etapa, realizamos modificaciones en el sitio web para agregar nuestra impronta y estética. Completamos textos sobre cómo fue la edición, cambiamos la imagen de portada y elegimos una paleta de colores que nos pareció adecuada para la temática, entre otros cambios. Este proceso se realizó a lo largo de todo el cuatrimestre con el que dio fruto a nuestro sitio sobre el apartado Nota del Lazarillo de ciegos caminantes.  