# SOLID-Sustitucion-Liskov
Ejemplo en C++ del Principio de Sustitución de Liskov (LSP) de SOLID.

Este principio se puede ver implementado en este proyecto mediante la sobrescritura del metodo virtual de calculo de descuentos en las clases que son derivadas.
En el archivo Producto.H, las clase base define los metodos virtuales AplicarDescuento() y ConvertirPrecio().
En los archivos de las clases derivadas, se heredan de la clase Producto y sobrescriben el metodo AplicarDescuento() mediante override.
