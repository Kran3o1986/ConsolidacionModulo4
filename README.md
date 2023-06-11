# ConsolidacionModulo4

Práctica de consolidación módulo 4

FUNDAMENTOS DE PROGRAMACIÓN AVANZADA EN JAVASCRIPT
INSTRUCCIONES
Lee con atención cada uno de los requerimientos que se presentan a continuación, y desarrolla la prueba de 
acuerdo con lo solicitado.
DESCRIPCIÓN
¿Alguna vez has querido saber cómo serían los personajes de ficción en la vida real? En este ejercicio
desarrollarás una aplicación, la cual permitirá a los usuarios tener una mejor idea de cómo serían algunos 
de sus personajes favoritos de Star Wars, en la vida real.
Aplicarás tus conocimientos avanzados de JavaScript, para crear una aplicación web que muestre la altura
y el peso de algunos de los personajes más interesantes de las películas de Star Wars. Dado que son de 
ficción, conocer sus dimensiones puede ayudar a los fans a comprender mejor qué tan grandes o pequeños 
serían en la vida real. La vista que necesitas desarrollar contiene el siguiente diseño:
Ahora bien, ¿de dónde obtenemos la información de los personajes?: tendrás que consumir la API de Star 
Wars (https://swapi.dev/), cuya documentación se encuentra en su página de inicio. Si te fijas en el lado 
izquierdo de la vista, notarás rangos de número: el primero es del 1 al 5, el segundo es del 6 al 11, y el 
último es del 12 al 17. Cada vez que el mouse de un usuario ingresa en el espacio sobre éstos, tu programa 
usará el método fetch() para obtener y procesar la información desde la API, mostrándola en otro bloque 
como se muestra la siguiente imagen. Cada bloque debe desplegar el nombre del personaje, su estatura y 
su peso.
Los números a la izquierda de la vista corresponden a los resultados de las consultas de personas. Por 
ejemplo, en la sección "1 - 5", debes generar dinámicamente los bloques que muestran información de: 
https://swapi.dev/people/1,
https://swapi.dev/people/2, 
https://swapi.dev/people/3, 
https://swapi.dev/people/4 y 
https://swapi.dev/people/5.
Debes repetir este proceso con los diferentes rangos de números necesarios, tal como se indica en el lado 
izquierdo de la vista.
Es importante tener en cuenta que estás limitado a mostrar 5 resultados por sección, y la generación 
dinámica de los bloques de contenido debe realizarse mediante el uso de un generador. En total, tu 
proyecto tiene que ser capaz de generar información que refleje lo que se encuentra en la siguiente imagen:
Todo lo que se ha considerado hasta este momento son requisitos, pero de manera opcional, puedes 
utilizar recursos como jQuery o animaciones para enriquecer la vista. 
