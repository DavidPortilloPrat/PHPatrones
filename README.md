# PHPatrones
Serie de ejemplos de programación con patrones en php

- Abstract Factory
El patrón Abstract Factory define que objetos no abstractos o concretos que la factory creará.

La factory concreta debe crear los objetos adecuados para su contexto, asegurándose que todos los objetos creados por la factory concreta deben funcionar correctamente para una circunstancia concreta dada.

En este ejemplo usamos AbstractBookFactory que especifica dos clases, AbstractPHPBook y AbstractMySQLBook, los cuales son necesarios para crear la factory concreta.

La clase concreta AnayaBookFactory extiende AbstractBookFactory y puede crear la clase AnayaMySQLBook y AnayaPHPBook, las cuales son las adecuadas para el contexto Anaya

La creación de interfaces permite