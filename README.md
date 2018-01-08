# maven
¿DE QUE TRATA ESTE PROYECTO?
A continuación expongo una explicación sobre mi proyecto JAVA gestionado con la herramienta MAVEN.
Este proyecto lo he realizado en el modulo de PROGRAMACIÓN con el lenguaje JAVA y en el entorno ECLIPSE.
El proyecto se basa en la ORIENTACIÓN A OBJETOS, el cual es un AUTOBÚS y a este le asignamos unos atributos y
unos comportamientos en Bus.java para más tarde probarlo con una especie de Test en PruebaBus.java, comprobado así
que todos los métodos están correctos y bien realizados.

¿QUE VOY A APRENDER?
1. Clonar un proyecto GITHUB en tu repositorio local (a no ser que ya lo hayas hecho antes).

2. Gestionar un proyecto JAVA con la herramienta MAVEN (varios comandos sencillos).

3. Saber que te proporcionan los comandos usados con MAVEN y ver la estructura de mi proyecto.

¿CÓMO LO PRUEBO?
1. Primero deberás clonar este proyecto en tu repositorio local con la orden "git clone" y a continuación la dirección de
este proyecto. Tal que así ---> "git clone https://github.com/robefernandez22/Maven.git" (sin las comillas, claro).

2. Te creará una carpeta llamada "Maven", a la cual deberemos trasladarnos, una vez dentro de la misma procedemos a construir
con el comando "mvn package". Después de eso todo debería estar correcto por lo que pasamos al siguiente paso.

3. Si vemos el contenido de la carpte en la que estamos ("Maven"), veremos que nos ha creado una carpeta "target" la cual
contiene los ".class" ("Bus.class" y "PruebaBus.class"). Después de todas estas comprobaciones pasamos al siguiente paso.

4. Y el último paso es probar el JAR que nos crea y lo hacemos de la siguiente manera ---> "java -cp target/MiProyectoMaven.jar:. 
autobus.PruebaBus"
