

## ESPACIO DE NOMBRES PARA CLASES DE HTML CON PREFIJOS

- o-: Objeto - Puede usarse en múltiples contextos no relacionados. Modificar con precaución, ya que puede afectar otras partes del código.

- c-: Componente - Es una pieza específica de la interfaz de usuario. Los cambios en sus estilos deben ser detectables en el contexto actual. Modificación segura y sin efectos secundarios.

- [has- | is-]: Estado - Indica que el estilo actual es temporal o depende de un estado o condición. Se aplica por un período breve y opcional.

- _.: Hack - Clase para forzar un funcionamiento específico. Su uso es excepcional y debe considerarse temporal (Casos de uso extremos).

- js-: JavaScript - Indica que esta parte del DOM tiene comportamientos vinculados a JavaScript. No modificar si no trabaja con JavaScript.

- qa-: Pruebas - Reservado para pruebas automatizadas de control de calidad. No se debe modificar, es para fines de prueba.

> Se usa la nomenclatura de BEM para nombrar clases, en combinacion con ITCSS para el espacio de nombres (Componentes, Objetos, Estados, Hacks, Ganchos JavaScript). Referencia de articulo:  [csswizardry](https://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/ "Ir al articulo")