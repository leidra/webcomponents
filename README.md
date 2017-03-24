# Web components

Son componentes HTML construidos utilizando estándares web. Permiten extender el lenguaje HTML encapsulando la visualización y el comportamiento.

## Están basados en 4 especificaciones:

 - Custom Elements - 
	Define cómo construir y utilizar nuevos elementos del DOM.
 - Shadow DOM - 
	Especifica cómo encapsular el estilo y marcado de un componente web
 - Html Imports - 
	Explica la inclusión y reutilización de documentos HTML en otros documentos HTML
 - Html Template -
	Define cómo declarar fragmentos de marcado HTML que no son interpretados en la carga de la página sino posteriormmente bajo demanda.

## Ejemplo de uso

Dentro de la etiqueta <head>:

<link rel="import" href="[URL_TO_DEFINITION]/hola-mundo.html" />

dentro del body:

<hola-mundo></hola-mundo>
