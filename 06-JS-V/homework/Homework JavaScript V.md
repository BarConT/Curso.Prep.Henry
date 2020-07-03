# Homework: Javascript V

* `prototype`: Todos los objetos en JavaScript estan asociados a otro objeto que es su prototipo. Los objetos heredan todas las propiedades de su 'prototype'. Los prototipos sirven para compartir propiedades y en especial, métodos, para así ahorrar espacio en memoria.

* _Constructors_ (de Clases) es una función que sirve de molde para crear varios objetos con las mismas propiedades pero con distintos valores. No retorna nada. Por convención, el nombre debe comenzar con mayúscula.
Los objetos se instancian(crean) mediante la palabra clave 'new' .
Cuando llamamos un método del objeto, JS lo busca en el objeto, si no lo encuentra, lo busca en el 'prototype'.