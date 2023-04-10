# Sprint 06 - Tarea 01 - Javascript Básico (1-29)

Avanzar hasta la sección 29 del curso **Javascript Básico** que esta en la [Algoritmos de JavaScript y Estructuras de Datos](https://www.freecodecamp.org/espanol/learn/javascript-algorithms-and-data-structures/).

Además, en su repositorio del proceso de formación (`formacion_junior`), cree una carpeta dentro de  `formacion_junior/cursos/` que se llame `javascript` y a su vez dentro de esta una que se llame `javascript_basico`. Dentro de esta última carpeta cree un archivo que se llame `bases.md`. La extensión de este archivo indica que es un archivo Markdown, que es un lenguaje que se usa para formatear archivos de texto.

Algunos elementos de Markdown son:

- Titulos: para escribirlos usamos la siguiente sintaxis:
    ```markdown
    # Titulo 1
    ## Titulo 2
    ### Titulo 3
    ```

    Que se verían:
    # Titulo 1
    ## Titulo 2
    ### Titulo 3

- Listas ordenadas:
    ```markdown
    1. Elemento 1
    2. Elemento 2
    3. Elemento 3
    ```

    Que se verían:
    1. Elemento 1
    2. Elemento 2
    3. Elemento 3

- Código en linea: si queremos que dentro de un texto una o varias palabras se muestren como código lo hacemos así:
    ```markdown
    Este es un texto hay una `palabra` como código.
    ```
    Se vería:

    Este es un texto hay una `palabra` como código.

- Bloques de código:
    ```markdown
        ```javascript
        var num1 = 5;
        var num2 = 3;
        var num3 = num1 + num2;
        ```
    ```
    Fíjese en las tres comillas simples inclinadas a la izquierda al principio y al final del bloque. Además, indicamos que el bloque de código es de javascript, por eso el nombre después de las tres primera comillas. El resultado sería:
    ```javascript
    var num1 = 5;
    var num2 = 3;
    var num3 = num1 + num2;
    ```

Unos conceptos más amplios de Markdown pueden encontrarse en [Markdown.es](https://markdown.es/sintaxis-markdown/#codigo).

La idea es que con estos elementos de markdown transcriba todos los ejercicios realizados en el curso **Javascript Básico**. En el archivo creado inicialmente debe haber un título con el nombre del curso y una lista ordenada, donde cada punto es una sección del curso. Para cada punto se debe poner el nombre de la sección y el ejercicio trabajado. Por ejemplo, para la sección 7 sería:

7. Comprendiendo las variables no inicializadas: Inicializa las tres variables `a`, `b`, y `c` con `5`, `10` y `"I am a"` respectivamente para que no sean `undefined`.
    ```javascript
    var a;
    var b;
    var c;

    a = a + 1;
    b = b + 5;
    c = c + " String!";
    ```
    Solución:
    ```javascript
    //aqui iría cómo quedó el ejercicio solucionado
    ```

La idea con esto es que tengamos un registro de los concepto básico de javascript, de manera que en el momento que necesitemos recordar algo tengamos un lugar donde ir a buscar.

**Criterios de Aceptación**

- En el repositorio del proceso de formación se debe evidenciar un commit que incluya los cambios requeridos.