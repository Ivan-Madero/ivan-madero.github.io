---
title: Documentacion
layout: doc
id: 02
permalink: /doc/
entrada: Documentación Jekyll
---

> Esta información ha sido sacada de la pagina oficial de Jekyll,
https://jekyllrb.com/docs/home/ 

## Variables Globales

site
 : Información del sitio + Archivo de configuracion `_config.yml`.

page
 : Información de la pagina + `YALM`.

layout
 : Información de diseño + `YALM`.
  
content
 : El contenido renderizado de las paginas de diseño.
 
paginator
 : Variable cuando se configura la paginación.

## Variables del sitio web
site.item
 : La hora actual (cuando se ejecuta el comando jekyll).

site.pages
 : Una lista de todas las paginas.

site.posts
 : Lista cronologica inversa de todos los posts.
 
site.related_posts
 : Lista de los ultimos 10 post por orden cronologico inverso.

site.static_files
 : Lista de archivos estaticos (archivos que no son procesados por 
 jekyll). Cada archivo tiene 3 propiedades (ruta, fecha de modificacion,
 nombre fichero)

site.html_pages
 : Lista de `site.pages` que acaban en .html.

site.html_files
 : Lista de `site.static_files` que acaban en .html.

site.collections
 : Lista de las colecciones.

site.data
 : Lista que contiene los datos cargados de los archivos `YALM` ubicados
 en el directorio `_data`.

site.documents
 : Lista de documentos de cada coleccion.

site.categories.CATEGORY
 : Lista de todos los posts de la categoria `CATEGORY`.

site.tags.TAG
 : Lista de todos los posts con la etiqueta `TAG`.

site.\[CONFIGURATION_DATA\]
 : Todas las variables configuradas atraves de la linea de comandos o del
 fichero `_config.yml`.

