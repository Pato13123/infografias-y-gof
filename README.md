# infografias-y-gof
Metodologías y tipos de prueba GOF
•	PATRONES GOF
Esto es un conjunto de patrones los cuales nos permiten resolver problemas en el ámbito del desarrollo de software, estos presentan un conjunto de pautas y soluciones para poder abordar desafíos de software orientado a objetos, de estos existen 3 tipos 
1.	Los patrones de creación: básicamente se encargan de la creación de objetos y los más conocido en este ámbito son el patrón singleton, Factory method y el patrón builder 
2.	Patrones de estructura: estos nos permiten componer clases y objetos para formar estructuras grandes en este ámbito los más conocidos son Adapter, el patrón Composite y el patrón Decorator
3.	Patrones de comportamientos: estos se centran en crear objetos y asignar responsabilidades, los más conocidos son el Observer, el patrón Strategy y el patrón Template Method.
•	TIPOS DE PRUEBA
Existen varios tipos de prueba pero normalmente los mas utilizados y los mas comunes son:
	Pruebas unitarias o de testing: prueban componentes del software para verificar que funcione correctamente
	Pruebas de integración: básicamente su funcionalidad es mirar que las partes de software funcionen cuando estas se combinen
	Pruebas de sistema: garantizan que se cumpla lo que el cliente haya pedido y que funcione en su totalidad
	Pruebas de rendimiento: verificar si ante varias cargas de trabajo el software sigue funcionando en cualquier ámbito 
	Pruebas de regresión: en algunas ocasiones al código o al software se le aplican cambios o actualizaciones esta prueba es para ver que dichos cambios no causen problemas en el software y mirar que funcione correctamente



•	¿Cuáles son los objetivos de esta prueba?
Su principal funcionalidad es encontrar algún error, cuando dicha prueba encuentra algún error significa que va por buen camino, mostrando cosas que al cliente le pudieron haber sucedido con la prueba se hace un testeo y se logra resolver dicho problema.
Una prueba no es algo secundario, es casi la mitad del esfuerzo en el desarrollo de software del mismo proyecto, un pequeño error de estos le puede costar a la empresa más de sesenta millones de dólares
•	CAJA BLANCA Y CAJA NEGRA 
La caja blanca se trata del conocimiento de la estructura en su parte interna y de mirar el funcionamiento del código fuente del sistema, con esto la persona conocida como Tester puede acceder a las variables, los algoritmos y las rutas de ejecución del código,
Sirve básicamente para probar la lógica interna del sistema.

Seguido de esto nos encontramos con la caja negra, con la cual el tester no conoce la estructura interna del sistema, aquí el tester solo conoce el E/S entrada y salida del sistema sin tener conocimiento de cómo se está procesando internamente, básicamente la funcionalidad externa de dicho sistema.
Esto es bastante importante ya que sirve para mira la calidad del sistema.
