# Homework: Javascript IV


	* Objetos: son una collección de propiedades. Se pueden representar todas las cosas del mundo real con objetos en JavaScript. Se declaran mediante la palabra clave 'var' luego el nombre del objeto, después el signo igual '=' y por último, se abren y cierran llaves '{}'. Dentro de las llaves, se colocan las propiedades separadas por comas ',' .
	Un objeto puede contener enteros, strings, funciones, arreglos y otros objetos dentro.

	* Propiedades: son similares a las variables pero pertenencen a un objeto. Estan formadas por dos partes: el nombre(o clave) y el valor. Su sintaxis es: el nombre de la propiedad seguido de dos puntos ':' y el valor. Cada propiedad debe estar separada por una coma ','.

	* Métodos: son propiedades que tienen dentro una función. La sintaxis es: el nombre del metodo, luego dos puntos ':', la palabra reservada 'fuction' se cierran y abren paréntesis (dentro de estos van los parámetros si los hay) y se abren y cierran las llaves '{}'. Dentro de las llaves se colocan las instrucciones.

	* Bucle `for…in`: es utilizado para recorrer cada una de las propiedades de un objeto. Su sintaxis es: la palabra reservada 'for', luego se abren los paréntesis y se coloca una nueva variable, la palabra 'in', después el nombre del objeto y se cierran los paréntesis. Luego se abren y cierran las llaves. Dentro se colocan las instrucciones, utilizando la variable declarada dentro de los paréntesis para ir iterando por las propiedades del objeto, mediante la notacion de corchetes.

	* Notación de puntos vs notación de corchetes: se utilizan para acceder a las propiedades. 
	La notacion de corchetes se escribe el nombre del objeto y luego entre corchetes y comillas se escribe el nombre de la propiedad. Por ejemplo: objeto['propiedad'] . La ventaje es que se pueden pasar nombres de variables dentro de los corchetes, resultando mas fácil el acceso a las propiedades.
	La notacion de puntos se escribe el nombre del objeto seguido de un punto y el nombre de la propiedad. Por ejemplo: objeto.propiedad . La ventaja es que es mas sencillo de escribir.
	En ambos casos, cuando se quiere llamar un método, se deben colocar los paréntesis para finalizar la llamada. Por ejemplo: objeto['metodo']() o objeto.metedo() .