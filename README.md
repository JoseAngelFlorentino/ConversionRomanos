# 1.	¿Qué es un Coding Dojo? 
Un Coding Dojo se refiere a una reunión de programadores para trabajar de manera colaborativa y no competitiva en algún problema o reto de programación durante una cantidad de tiempo extendida. El objetivo de un Coding Dojo es adquirir nuevas habilidades, crear un ambiente acogedor y ser divertido. (Rodríguez, 2011)

2.	Diferencia entre Requerimientos, Criterios de Aceptación y Escenarios de Prueba. Dar ejemplos a partir de un problema distinto a la referencia. 
Un requerimiento de software es una propiedad que se debe encontrar dentro de las características de algo que tiene como objetivo la solución de un problema real. Los criterios de aceptación son un grupo de declaraciones que indican como juzgar si algún componente de software o cualquier sistema satisface algún requerimiento. Los escenarios de pruebas son un conjunto de ejemplos concretos utilizados para validar un criterio de aceptación en específico.
Se diferencian en que los requerimientos son descripciones detalladas de las características de un sistema, los criterios de aceptación son elementos utilizados para satisfacer la necesidad de verificar las propiedades de los requerimientos, y los escenarios son ejemplos reales y concretos para validar uno de los criterios de aceptación marcados. (Martínez, 2017)

Ejemplo: Se necesita la creación de un cronometro digital. 
Req-1: El cronometro necesita medir el tiempo con una diferencia de máximo 0.01 segundos entre el cronómetro y un reloj preciso. 
Req-2: El cronometro debe tener la funcionalidad de elegir cuando empieza a correr. 
Req-3: El cronometro debe tener la funcionalidad de parar el conteo del tiempo. 
Req-4: El cronometro debe tener la funcionalidad de poder avanzarle 5 segundos al correo del tiempo sin perder su conteo. 

Cri-3-1: El cronometro no debe perder el conteo del tiempo cuando se para el conteo justo antes de entrar a otro minuto. 
Cri-3-2: El cronometro no debe perder el conteo del tiempo cuando se para el conteo justo antes de entrar a otra hora. 
Cri-3-3: El cronometro no debe perder el conteo del tiempo cuando se para el conteo justo antes de entrar a otro segundo.
Sce-3-1-1: Se para el cronometro junto antes de entrar a otro minuto. 
3.	De dos ejemplos de requerimientos no-funcionales, y especifique cuál es su categoría (seguridad, performance, portabilidad, etc.)
Siguiendo con el ejemplo del cronometro, y asumiendo que es para una aplicación de celular. 
Req-1: El cronometro debe interrumpir el auto apagado de la pantalla de un celular y mantenerse corriendo. Este requerimiento no-funcional tiene de categoría de estabilidad, porque necesita cumplir de este requerimiento para mantenerse corriendo sin problemas. 
Req-2: El cronometro debe ser virtualmente instantáneo en su comienzo y al ser manualmente terminado. Este requerimiento no-funcional tiene categoría de performance, debido a que se trata del tiempo en que dura para procesar inputs del usuario.  

4.	¿Qué es TDD?
El test driven development es un enfoque de programación que se utiliza durante el desarrollo de software en donde se realizan unitarias antes de empezar a escribir el código. El objetivo de hacer TDD es la realización de un código limpio, robusto y simple creando casos de pruebas para las funcionalidades y en caso de algún error reescribir el código libre de errores. (Pérez, 2024)

5. ¿Que son pruebas unitarias automatizadas?
Las pruebas unitarias de software son un instrumento que se utiliza para validar una sección de algún código fuente. Los desarrolladores dividen el código fuente en sus componentes y se testean para confirmar que esa función, proceso o actividad específica este operando con el funcionamiento correcto. (Tamushi, 2022)
6. ¿Cuál fue el 1er framework de pruebas unitarias y para cual lenguaje fue creado?
El primer framework de pruebas unitarias fue un testing framework para Smalltalk llamado SUnit, creado en el 1989 por Kent Beck. 
7. Describa los componentes de la arquitectura xUnit. 
•	Preparación: Toda línea de código necesario para preparar la prueba de testeo. 
•	Acto: Llamar al código que se quiere probar. 
•	Afirmar: Realizar afirmaciones sobre el resultado de la ejecución. 
8. Indique al menos tres desventajas de las pruebas unitarias automatizadas
•	Las pruebas unitarias no siempre detectan todas las fallas dentro de una aplicación. 
•	Las pruebas unitarias manuales requieren mucho tiempo y mano de obra. 
•	Gestionar cientos de pruebas unitarias es complicado sin automatizarlos. (Parasoft, 2024)


9. Indique al menos tres ventajas de las pruebas unitarias automatizadas
•	Las pruebas unitarias son caracterizadas por su velocidad en la detección de errores en los sistemas por la poca cantidad de código requerido para el análisis
•	Estas pruebas se aplican en las etapas tempranas del desarrollo para prevenir errores fatales en fases siguientes, lo que evita incrementos de costos. 
•	La calidad del desarrollo depende del funcionamiento correcto de los productos informáticos. Las pruebas unitarias contribuyen a este funcionamiento debido a su detección temprana de errores, culminando en la entrega de código limpio. (Tamushi, 2022)
