# Clean-Code

CLEAN CODE

1. **Usa nombres con significado**
1. **Usa nombres fáciles de pronunciar**
1. **Usa nombres que puedan buscarse**
1. **Nombres de clases (sustantivos) y métodos o funciones (Verbos)**
1. **Elige una sola palabra por concepto:** tarea similar = mismo nombre
1. **Las funciones deben ser pequeñas**
1. **Haz una única cosa por función** 
1. **No abuses de los switch/when.**
1. **De 0 - 3 argumentos por función.**
1. **Evita los "flag arguments":** Boolean de true false
1. **No generes "Side Effects":** una función hace o devuelve algo nunca las dos.
1. **No te repitas (DRY)**
1. **Los comentarios mienten:** actualiza los comentarios.
1. **Usa código autoexplicativo.**
1. **A veces los comentarios son necesarios**
1. **Los comentarios dicen qué hace el código, no cómo lo hace.**
1. **Diferencias entre objetos y estructuras de datos:** Los objetos encapsulan datos y operaciones relacionadas, mientras que las estructuras de datos exponen sus datos y no tienen lógica asociada.
1. **La Ley de Demeter.**
1. **Usa excepciones en lugar de código de retorno**
1. **Escribe primero el try-catch-finally**
1. **Usa excepciones unchecked.**
1. **No devuelvas Null**

|<p>markdown</p><p>![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.001.png) **[Líneas**](https://tutorialmarkdown.com/sintaxis/#saltos-de-linea)**: Para iniciar una nueva línea debes agregar dos espacios en blanco al final de la línea, pulsar INTRO o usar una barra invertida \, según el editor que uses.</p><p>![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.002.png) **[Párrafos**](https://tutorialmarkdown.com/sintaxis/#parrafos)**: Para crear un nuevo párrafo sencillamente debes dejar una línea en blanco.</p>||
| - | :- |
|**Elemento**|**Sintaxis**|
|[**Encabezados**](https://tutorialmarkdown.com/sintaxis/#encabezados)|# H1  -  ## H2  -  ### H3|
|[**Negrita**](https://tutorialmarkdown.com/sintaxis#negrita)|\*\*texto\*\*     \_\_texto\_\_|
|[**Cursiva**](https://tutorialmarkdown.com/sintaxis#cursiva)|\*texto\*|
|[**Negrita](https://tutorialmarkdown.com/sintaxis#negrita) **y [Cursiva**](https://tutorialmarkdown.com/sintaxis#cursiva)**|\*\*\*texto\*\*\*|
|[**Citas**](https://tutorialmarkdown.com/sintaxis#citas)|> cita|
|[**Listas ordenadas**](https://tutorialmarkdown.com/sintaxis#listas-ordenadas)|1\. Lista|
|[**Listas no ordenadas**](https://tutorialmarkdown.com/sintaxis#listas-no-ordenadas)|<p>\* Primer elemento</p><p>+ Primer elemento</p><p>- Primer elemento</p>|
|[**Código**](https://tutorialmarkdown.com/sintaxis#codigo)|`código`|
|[**Línea horizontal**](https://tutorialmarkdown.com/sintaxis#lineas-horizontales)|---|
|[**Enlaces**](https://tutorialmarkdown.com/sintaxis#enlaces)|[anchor](https://enlace.tld "título")|
|[**Imágenes**](https://tutorialmarkdown.com/sintaxis#imagenes)|![Alt](/ruta/imagen.png)|
|[**Tablas**](https://tutorialmarkdown.com/sintaxis-extendida#tablas)|<p>| Color | Código |</p><p>| ----------- | ----------- | | Rojo | #FF0000 |</p><p>| Azul | #0000FF |</p>|
|||

[**Bloques de código avanzados**](https://tutorialmarkdown.com/sintaxis-extendida#bloques-de-codigo) ```![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.003.png)

{

`  `"Nombre": "Edu",   "Peso": "72Kg"

}

\```

[**Texto tachado**](https://tutorialmarkdown.com/sintaxis-extendida#texto-tachado) ~~Texto tachado~~ [**Listas de tareas**](https://tutorialmarkdown.com/sintaxis-extendida#listas-de-tareas) - [x] Primera tarea

\- [ ] Segunda tarea

[**Enlaces automáticos**](https://tutorialmarkdown.com/sintaxis-extendida#enlaces-automaticos) https://www.neoguias.com

Documentación

**Para abrir y cerrar documentación:** 

**/\*\***

**\***

**/\***

**@author               →        Autor de la Función** 

**@param                →       Explica los parámetros usados @return                →       Que devuelve la función** 

**@see                      →       “Ver Tambien”**

**@version              →       Version de software que se programo @property           →       Explica parámetros solo de clases @constructor     →       Explica constructor primario class @esception         →       Lanza ‘x’ exception y lanza ‘y’**

Refactorización

La **optimización y refactorización** son dos prácticas importantes en el desarrollo de software que buscan mejorar la calidad, mantenibilidad y eficiencia del código. 

La **refactorización** es el proceso de reestructurar el código existente sin cambiar su comportamiento externo para mejorar la calidad interna del código, haciéndolo más legible, comprensible, mantenible y eficiente, sin alterar su funcionalidad.

**"Rename"**: Cambia el nombre de una variable, método, clase u otro elemento del código sin cambiar su funcionalidad.

**"Change Signature"**: Permite cambiar los parámetros de un método, incluyendo tipos y orden.

**"Introduce Variable"**: Crea una nueva variable y asigna el valor de una expresión para simplificar el código.

**"Introduce Constant"**: Similar al anterior, pero para la creación de constantes.

**"Property"**: Convierte un método getter o setter en una propiedad para un acceso más sencillo. **"Introduce Parameter"**: Añade un nuevo parámetro a un método y lo utiliza en su cuerpo.

**"Introduce Functional Parameter"**: Similar al anterior, pero específico para métodos lambda o expresiones lambda.

**"Function..."**: Convierte un bloque de código en una función separada para su reutilización.

**"Function to Scope..."**: Transforma un método en una función anónima o expresión lambda asignada a una variable.

**"Type Parameter..."**: Convierte un tipo de variable en un parámetro de tipo genérico para mayor flexibilidad.

**"Type Alias..."**: Crea un alias para un tipo de variable o genérico.

**"Extract Interface..."**: Extrae métodos de una clase para formar una interfaz y organizar el código.

**"Extract Superclass..."**: Combina atributos y métodos de dos o más clases en una superclase para evitar duplicación de código.

**"Move Instance Variable to Another Class..."**: Transfiere un atributo de instancia de una clase a otra relacionada.

**"Move Static Method to Another Class..."**: Mueve un método estático de una clase a otra relacionada.

**"Change Class Signature..."**: Modifica atributos y métodos de una clase, incluyendo tipos y modificadores de acceso.

**"Encapsulate Fields..."**: Crea métodos getter y setter para los atributos de una clase. **"Change Visibility Modifier..."**: Altera el modificador de acceso de un método o atributo.

**"Introduce Polymorphic Call..."**: Reemplaza una llamada a un método concreto por una llamada a un método polimórfico.

**"Inline Local Variable..."**: Elimina una variable local y reemplaza sus referencias por el valor asignado.

**"Replace Type Code with Class..."**: Sustituye un tipo de variable codificado con clases.

**"Move to Subclass..."**: Mueve un método o grupo de métodos de una clase a una de sus subclases.

**"Pull Up..."**: Traslada un método o atributo de una subclase a su superclase.

**"Introduce Indirection..."**: Introduce un nivel de indirección en el acceso a un método o atributo.

La **Optimización** es el proceso de mejorar el rendimiento de un programa o sistema. Puede abordar aspectos como el tiempo de ejecución, la eficiencia del uso de memoria o la velocidad de respuesta. 

- **Algoritmos eficientes**: Escoger estructuras de datos y algoritmos óptimos.\
  - **Optimización de bucles y operaciones**: Evitar bucles innecesarios y usar operaciones eficientes.
    - **Uso eficiente de memoria**: Minimizar el uso y evitar fugas.
      - **Índices y estructuras de datos específicas**: Aprovechar índices y estructuras adecuadas.
        - **Eliminación de código redundante**: Revisar y eliminar código innecesario.
          - **Optimización de carga de módulos/bibliotecas**: Cargar solo lo necesario.
            - **Compilación y flags de optimización**: Utilizar opciones de compilación y flags adecuados.

pr incipios S.O.L.I.D.

Los principios SOLID son un conjunto de cinco principios de diseño de software que promueven la creación de código modular, flexible y mantenible.

**S - Principio de Responsabilidad Única (Single Responsibility Principle):**

![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.004.png) Una clase debe tener solo una razón para cambiar, es decir, debe tener una única responsabilidad.

**O - Principio de Abierto/Cerrado (Open/Closed Principle):**

![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.005.png) Las entidades de software (clases, módulos, funciones, etc.) deben ser abiertas para la extensión pero cerradas para la modificación.

**L - Principio de Sustitución de Liskov (Liskov Substitution Principle):**

![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.006.png) Los objetos de una superclase deben ser sustituibles por objetos de sus subclases sin afectar la corrección del programa.

**I - Principio de Segregación de Interfaces (Interface Segregation Principle):**

![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.007.png) Un cliente no debe verse obligado a depender de interfaces que no utiliza. En otras palabras, los clientes no deben verse afectados por interfaces que no necesitan.

**D - Principio de Inversión de Dependencias (Dependency Inversion Principle):**

![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.008.png) Las dependencias deben estar dirigidas hacia abstracciones, no hacia implementaciones. Los módulos de alto nivel no deben depender de módulos de bajo nivel; ambos deben depender de abstracciones.

GRADLE

JAR

1. Creamos un nuevo proyecto seleccionando **kotlin-Gradle-kotlin**.
1. Entramos en **build.gradle.κts.**
1. All final introducimos el siguiente **código**:

**tasks.jar {**

**manifest {**

**attributes["Main-Class"] = "MainKt"**

**}**

**configurations ["compileClasspath"].forEach { file: File ->**

**from (zipTree (file.absoluteFile) )**

**}**

**duplicatesStrategy = DuplicatesStrategy.INCLUDE**

**}**

4. **Descargamos Gradle**
4. A la izquierda **build-tmp-jar** podemos ver como se creo jas.
4. A la derecha **gradle-Tasks-build-jar** ejecutamos el jar.

![](Aspose.Words.9e105bf2-0803-4999-8817-5cae2699efcb.009.png) DOKKA

**3.** Escribimos en plugins, debajo de applications 

***id ("org.jetbrains.dokka") version "1.9.10"***

5. A la izquierda **build-dokka** podemos ver cano se creo ex dokka
5. A la derecha **gradle - Tasks - documentarion - dokkaHml** cargamos el dokka
