# Trabajo Practico Tienda

Se requiere desarrollar un programa utilizando programación orientada a objetos para una tienda para ayudar con las tareas del día a día. Para resolver este problema implementaremos las clases: Producto, Carrito y Tienda ademas de un menu iterativo para seleccionar la accion que se desea realizar. Los requisitos minimos de cada clase son los siguientes:

## Producto
- Esta clase almacena el nombre de un producto, su costo, su precio de venta y su stock. 
- El precio de venta de un producto se calcula como el costo + 30% del costo.
- No se puede crear un producto sin nombre o sin costo.

## Tienda
- Debe almacenar una lista de todos los productos que vende la tienda y el dinero en caja.
- Se debe poder agregar y eliminar productos de la lista de productos.
- Mostrar el listado de los productos de la tienda y el stock de cada uno. Se debe poder seleccionar por teclado el producto que se quiere agregar al carrito e indicar la cantidad.
- Debe poder cobrar el importe total de la compra. Para esto hay que ingresar la cantidad de dinero con la que el cliente va a pagar y devolver cuánto vuelto hay que dar(si hubiese vuelto). Luego de cobrar se debe agregar el monto de la venta al dinero en caja.

## Carrito
- Puede agregar un producto al carrito y la cantidad de ese producto que se desea comprar.
- Puede eliminar un producto del carrito.
- Calcula el subtotal a pagar de los productos que se agregaron al carrito.

## Ayudas
Para definir listas y metodos para usarlas:
Para declarar e inicializar una lista
```
List<DataType> myList = [listElem1, listElem2, …]
```
Para declarar una lista vacía
```
List<DataType> myList = new List<DataType>()
```
Obetener el indice de un elemento de la lista. Si el elemento no existe devuelve -1.
```
myList.IndexOf(listElement)
```
Agregar un elemento a una lista
```
myList.Add(someElement)
```
Elemininar un elemento de una lista
```
myList.Remove(listElement)
```
Ordenar una lista
```
myList.Sort()
```

Definir arrays
```
dataType[] myArr = new dataType[limit]
```

### Importante
Deberán hacer las validaciones que consideren necesarias para prevenir los posibles errores. Por ejemplo: si el stock de un producto es 0, no se puede agregar al carrito. Creen los objetos que consideren necesarios para probar todas las funcionalidades de las clases.

## Entrega
La fecha límite de entrega será el __viernes 7/6/24 a las 23:59__.
La entrega del trabajo será en _grupos de a dos_. Deberán presentar el trabajo en un repositorio de GitHub por medio de este [formulario](https://docs.google.com/forms/d/e/1FAIpQLSe9nfyupkEDB0ph3sUhW1OO3zstxZCDP0ejapWokyKNYbSbgQ/viewform?usp=sf_link)
