# Pre Entrega 1 - Matías Ugarriza

Este proyecto se trata de una tienda virtual de cervezas artesanal.

## Actualizaciones

* *Versión Actual*
    * Actividad 1:
        * Crear componente ItemCount ✔
        * Crear función para que sume o reste.✔
        * Agregar límite según stock.✔
    * Actividad 2:
        * Crear Item e ItemList. ✔
        * Crear un archivo JSON con los items. ✔
        * Crear una función que busque los items del archivo json. ✔
        * Que el item sea una card de bootstrap ✔
        * Los ítems se tienen que cargar con un llamado promise de 2 segundos. Usar: https://getbootstrap.com/docs/5.3/components/spinners/ ✔
    * Actividad 3:
        * Crear componente ItemDetailContainer. ✔
        * Usando UseEffect llamar a un async mock usando una promesa con 2 segundos de carga que devuelva un ítem y lo guarde en un estado prop. ✔
        * Crear Item Detail con descripción, foto y precio. ✔

* 22bcdb0 "Primer Entrega":
        * Crear un NavBar. ✔
        * Usar una librería de estilos. ✔
        * Crear componente CartWidget con número hardcodeado y el ícono de Cart. ✔
        * Crear componente contenedor ItemListContainer con una prop de saludo mostrando las opciones y el styling integrado. ✔
        * Crear Landing del proyecto. ✔

### Objetivos y Mejoras por hacer
 



* Pre Entrega 2:
    * NavBar con Cart
    * Catálogo
    * Detalle del producto
    * Rutas: 
        * '/' --> <ItemListContainer /> 
        * '/category/:id' <ItemListContainer />
        * '/item/:id' <ItemDetailContainer />
    * Usar BrowserRouter y el id de la categoría como nombre en la URL param.
        
* Otras Mejoras:
    * El ítem tiene que contener información breve. Agregar información sobre el producto en el item.
    * Agregar datos al archivo data.js
    * Agregar categorías al navbar.
    * Revisar estilo del brand.
    * Mejorar las cards.
    * Ver si hace falta guardar info en LocalStorage.
    * Crear función para agregar al carrito.
