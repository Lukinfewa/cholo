<div align="center">
  <img src="https://statics-maker.llt-services.com/ovi/images/2026/01/16/xlarge-wp/00c6043b-3a92-4c35-8330-9f237a7382a0-599.webp" width="600px" alt="Almada Java Logo">
  
  # LIBRO DE TÁCTICA: JAVA STREAMS & OPTIONAL
  ### "Ganar, ganar y volver a ganar: El Manual de  Guille Almada para Java 8+"
  
  [![Java Version](https://img.shields.io/badge/Java-8%2B-red?style=for-the-badge&logo=java)](https://www.oracle.com/java/)
  [![License](https://img.shields.io/badge/Licencia-MIT-blue?style=for-the-badge)](https://opensource.org/licenses/MIT)
  [![Build](https://img.shields.io/badge/Estado-Finalizado-success?style=for-the-badge)](https://github.com/Lukinfewa/almada)
</div>

<div align="center">


## 🌟 LA PIZARRA DE LAS ESTRELLAS 🌟

<table>
  <tr>
    <th colspan="3" bgcolor="#001C58"><b><font color="white" size="5">🏆 FASE DE GRUPOS: EL ADN</font></b></th>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="#1-charla-técnica-salir-a-ganar">
        <img src="https://img.shields.io/badge/FASE_1-VESTUARIO-001C58?style=for-the-badge&logo=adidas&logoColor=white" /><br>
        <sub><b>ADN DEL CLUB</b><br>Mentalidad Funcional</sub>
      </a>
    </td>
    <td align="center" width="33%">
      <a href="#2-conceptos-tácticos-del-barro-al-césped">
        <img src="https://img.shields.io/badge/FASE_2-LA_PIZARRA-c1121f?style=for-the-badge&logo=target&logoColor=white" /><br>
        <sub><b>LAS ÓRDENES</b><br>Lambdas & Interfaces</sub>
      </a>
    </td>
    <td align="center" width="33%">
      <a href="#3-la-api-de-streams-el-balón-en-movimiento">
        <img src="https://img.shields.io/badge/FASE_3-SAQUE_INICIAL-003049?style=for-the-badge&logo=google-cloud&logoColor=white" /><br>
        <sub><b>EL FLUJO</b><br>Concepto de Stream</sub>
      </a>
    </td>
  </tr>
</table>

<br>

<table>
  <tr>
    <th colspan="3" bgcolor="#001C58"><b><font color="white" size="5">🎖️ ELIMINATORIAS: DOMINAR EL CAMPO</font></b></th>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="#4-operaciones-intermedias-el-trabajo-en-el-centro-del-campo">
        <img src="https://img.shields.io/badge/FASE_4-MEDULAR-1d3557?style=for-the-badge&logo=codeforces&logoColor=white" /><br>
        <sub><b>TÁCTICA MEDIA</b><br>Filter · Map · Sorted</sub>
      </a>
    </td>
    <td align="center" width="33%">
      <a href="#5-operaciones-terminales-el-remate-a-puerta">
        <img src="https://img.shields.io/badge/FASE_5-EL_GOL-000000?style=for-the-badge&logo=target&logoColor=white" /><br>
        <sub><b>FINALIZACIÓN</b><br>Collect · Reduce</sub>
      </a>
    </td>
    <td align="center" width="33%">
      <a href="#6-la-clase-optional-el-seguro-de-vida-del-míster">
        <img src="https://img.shields.io/badge/FASE_6-BANQUILLO-f77f00?style=for-the-badge&logo=shield&logoColor=white" /><br>
        <sub><b>PLAN DE SEGURO</b><br>Optional & Nulls</sub>
      </a>
    </td>
  </tr>
</table>

<br>

## ¿Estás listo para levantar la Orejona?

<a href="#-sesión-de-entrenamiento-del-barro-al-gol">
  <img src="https://img.shields.io/badge/🏆_GÓNDOLA_DE_TROFEOS-15_NIVELES_DE_ENTRENAMIENTO_REAL-D4AF37?style=for-the-badge&logo=goldenline&logoColor=black" width="100%" />
</a>
</div>

# 1. Charla Técnica: Salir a Ganar
## 1.1. El Plan de Juego (Objetivo del manual)

Escuchadme bien, equipo. Miradme a los ojos. El objetivo de este manual no es que aprendáis a "picar código" de cualquier manera. El objetivo es que aprendáis a **competir**. Aquí vamos a presentar, con la pizarra clara y el cuchillo entre los dientes, cómo se usa la **API de Streams en Java**. No es solo una librería; es nuestra nueva formación táctica para dominar la programación funcional.

A lo largo de estas páginas, vamos a analizar a nuestros jugadores estrella: los **Streams** y la clase **Optional**. No nos vamos a quedar en la teoría; vamos a bajar al barro con **ejemplos prácticos**, jugadas ensayadas (casos de uso) y las **leyes del vestuario** (buenas prácticas) que separan a los campeones de los que se quedan en el banquillo. Aquí buscamos legibilidad, limpieza y, sobre todo, calidad en el juego.

Este manual va dirigido a los **canteranos**: estudiantes que ya saben darle patadas al balón (conocimientos básicos de Java) pero que quieren dar el salto al primer equipo y dominar el enfoque funcional que cambió nuestra historia a partir de **Java 8**.

**Porque aquí, programadores, el esfuerzo no se negocia. Partido a partido. Stream a stream.**


## 1.2. El Sistema de Juego: Del "Patadón" al Fútbol Moderno

Escuchad bien, porque aquí es donde se decide el partido. La **programación funcional** es nuestra nueva filosofía de juego. Se basa en un movimiento fluido del balón (las funciones) y en algo sagrado: **evitar los cambios de estado y los efectos secundarios**. 

En nuestro equipo, no queremos jugadores que se vuelvan locos y dejen su posición desprotegida (cambios de estado impredecibles). Queremos que, si un balón entra en una jugada, salga transformado en gol, sin que el resto del campo se convierta en un caos.

Tradicionalmente, Java jugaba al "patadón y tentetieso": la **Programación Imperativa**. Cada jugador era un objeto pesado que cargaba con toda la responsabilidad, y el entrenador tenía que gritar paso a paso cada movimiento. Era un fútbol lento, de mucho contacto y código farragoso.

Pero a partir de **Java 8**, hemos fichado el talento. El lenguaje ha incorporado elementos del fútbol total:
*   **Expresiones Lambda:** Instrucciones rápidas, como un gesto desde la banda. Menos palabras, más acción.
*   **Interfaces Funcionales:** El contrato que define el rol de cada jugador en una jugada específica.

Esto nos permite escribir código más **expresivo y conciso**. Ya no hace falta dar un discurso para decir "pasa el balón"; ahora lo hacemos con un toque sutil. 

Esto ya no es un manual, es el **Libro de Estrategia del Carlos Tartiere**.

<p align="center">⚽   ⚽   ⚽   ⚽   ⚽   ⚽</p>

# 2. Conceptos Tácticos: Del Barro al Césped
## 2.1. El Cómo contra el Qué (Imperativo vs. Funcional)

### 2.1.1 El Fútbol de "La Vieja Guardia" (Programación Imperativa)
La programación imperativa es el fútbol de antes, el de los bigotes y el barro. Se basa en darle al jugador una secuencia de instrucciones machaconas: *"Corre 10 metros, frena, mira a la banda, pon el centro con la pierna izquierda"*. 

Aquí, tú como míster tienes que especificar **paso a paso** cada movimiento. Usas los "entrenamientos" de siempre: bucles (`for`, `while`), condicionales (`if`) y variables que cambian de estado constantemente (ahora el balón está aquí, luego allí). 

Es el estilo que ha dominado Java toda la vida, especialmente al manejar plantillas de datos (colecciones). Es sencillo, sí, pero si la jugada es compleja o tienes una cantera de 10.000 jugadores, el código se vuelve eterno, repetitivo y es muy fácil que alguien cometa un error y te metan gol por la escuadra.

### 2.1.2 El Fútbol Total (Programación Funcional)
La programación funcional es nuestra **pizarra moderna**. Aquí no nos obsesionamos con el movimiento de cada músculo, sino con la **misión**. Priorizamos las funciones como el corazón del equipo. En lugar de detallar el "cómo" se corre, describimos **qué** queremos conseguir: *"Presión tras pérdida y salida rápida"*. Es un fútbol **declarativo**.

En Java, este "fútbol total" llegó con los fichajes estrella de **Java 8**: las expresiones lambda y la API de Streams. Estas herramientas nos permiten procesar a nuestra plantilla de datos de forma más elegante y eficiente. No jubilamos al viejo Java, sino que le damos un sistema táctico avanzado para que sea más claro y no se canse dando instrucciones innecesarias.

### 2.1.3 Comparativa: El Patadón vs. La Pizarra Táctica

| TÁCTICA IMPERATIVA | TÁCTICA FUNCIONAL |
| :--- | :--- |
| **Instrucciones paso a paso:** Cómo hay que jugar. | **Objetivo claro:** Qué resultado queremos obtener. |
| **Usa bucles y marcas al hombre:** Control explícito. | **Usa funciones y toques sutiles:** Transforma los datos. |
| **Estado variable:** El marcador y los jugadores cambian. | **Inmutabilidad:** Evitamos líos y efectos secundarios. |
| **Flujo detallado:** Como un partido de 90 minutos. | **Flujo expresivo:** Como el vídeo del resumen de goles. |
| **Enfoque de toda la vida:** El Java clásico. | **El gran cambio:** Introducido en Java 8. |
| **Código largo:** Mucho sudor y repetición. | **Código conciso:** Calidad y limpieza en el pase. |
| **Ideal para defender:** Lógica de control compleja. | **Ideal para atacar:** Procesamiento de colecciones. |

---

## El Equilibrio de Guille

En este equipo, ambos sistemas conviven. La **programación imperativa** sigue siendo nuestra defensa central para la lógica general de la aplicación. Pero cuando el balón llega al centro del campo y hay que manejar colecciones de datos, la **programación funcional** es nuestra delantera estrella: aporta una claridad y una pegada que hacen que el código sea puro espectáculo. **Partido a partido, función a función.**


## 2.2. Clases Anónimas: Los "Temporeros" del Código

En el fútbol, a veces necesitas a un jugador para una misión muy específica: tirar un penalti concreto o cubrir una baja solo durante cinco minutos. No le haces un contrato de cinco años, ni le pones su nombre en la marquesina del estadio. Simplemente lo sacas al campo, hace su trabajo y se va.

En Java, las **clases anónimas** son exactamente eso: una implementación de una interfaz o una subclase que creas "sobre la marcha", sin necesidad de darle un nombre oficial ni crear un archivo `.java` propio. Es una solución de emergencia para una implementación puntual que no piensas reutilizar en otro partido.

Antes de que llegaran los fichajes estrella de **Java 8** (las lambdas), las clases anónimas eran nuestra forma habitual de dar instrucciones concretas a las interfaces, sobre todo cuando solo tenían una jugada ensayada (un único método).

### Ejemplo: El entrenamiento de "jugada ensayada"
Imagina que tenemos una interfaz llamada `Jugada` con un método `ejecutar()`. En lugar de crear una clase `Corner`, una clase `Falta` y una clase `Penalti`, usamos una clase anónima para definir la jugada en el mismo momento del entrenamiento:

**La Pizarra (Interfaz):**
```java
public interface Jugada {
    void ejecutar();
}
```

**El Movimiento en el Campo (Clase Anónima):**
```java
public class Entrenamiento {
    public static void main(String[] args) {
        // Creamos un "jugador anónimo" solo para esta falta
        Jugada faltaDirecta = new Jugada() {
            @Override
            public void ejecutar() {
                System.out.println("Balón por encima de la barrera y a la escuadra.");
            }
        };

        faltaDirecta.ejecutar();
    }
}
```

### El Análisis de Guille
¿Qué ha pasado aquí? No hemos creado una clase `ClaseFaltaDirecta`. Hemos definido el comportamiento ahí mismo, en mitad del entrenamiento. Esto nos ahorra tener miles de archivos en la cantera para cosas que solo vamos a usar una vez.

Sin embargo, **ojo con el cansancio**: si empiezas a meter clases anónimas muy largas, el código se vuelve "pesado", difícil de leer y te ensucia la pizarra táctica. Por eso, con la llegada de la nueva era (Java 8), estos "temporeros" han dejado paso a las **expresiones lambda**: una forma mucho más rápida, eléctrica y concisa de dar la misma orden sin tanto papeleo.



## 2.3. Expresiones Lambda: El Grito desde la Banda

Escuchadme bien: en el fútbol moderno no hay tiempo para redactar un contrato cada vez que quieres que un jugador presione. Necesitamos **instrucciones eléctricas**. Las expresiones lambda son precisamente eso: una forma de definir una jugada (un bloque de código) de manera fulminante, sin tener que escribir toda la burocracia de un método tradicional.

Su objetivo es que el equipo juegue de forma **funcional y declarativa**. Ya no le decimos al jugador cómo tiene que poner el pie; le damos la orden directa y él la ejecuta. Una lambda es, en esencia, una función que puedes pasar como si fuera el balón (un parámetro) a otro método o usarla para que toda la plantilla (una colección) realice una acción a la vez.

### La Evolución: Del Contrato al Grito
Si las **clases anónimas** eran un contrato firmado ante notario para una sola jugada, las **lambdas** son un gesto desde la banda. 
*   **Clase Anónima:** "Yo, jugador, prometo por la presente golpear el esférico con la superficie interior del bota..." (Demasiado texto, nos meten gol).
*   **Lambda:** `(balón) -> chutar();` (Corto, directo, efectivo).

Gracias a ellas, trabajar con la **API de Streams** es como jugar al primer toque: filtramos, transformamos y rematamos los datos de una manera mucho más clara y con una "intensidad" que asusta al rival.

---

### 📋 Anatomía de la Jugada (Sintaxis)

En la pizarra de Guille Almada, una lambda siempre tiene tres partes: **Los implicados** (parámetros), **la flecha** (`->`) y **la acción** (cuerpo). Según la jugada, la orden cambia:

1.  **Sin implicados (Sin parámetros):**
    `() -> System.out.println("¡Pita el árbitro!");`
    *(Es un evento general, como el pitido inicial).*

2.  **Con un solo protagonista (Un parámetro):**
    `jugador -> jugador.correr();`
    *(No hace falta ni poner paréntesis si solo hay un jugador en la acción).*

3.  **Jugada combinada (Más de un parámetro):**
    `(pase, remate) -> pase + remate;`
    *(Aquí los paréntesis son obligatorios, como el orden en el campo).*

4.  **Plan táctico completo (Más de una sentencia):**
    ```java
    (balón) -> {
        mirarPorteria();
        armarPierna();
        return marcarGol();
    };
    ```
    *Si la orden es larga, usamos las llaves `{}` para que no se nos despiste nadie. Y si hay que devolver un resultado (un gol), el `return` es sagrado.*



## 2.4. Interfaces Funcionales: Los Especialistas de la Plantilla

En el sistema de Almada, la especialización es sagrada. No puedes poner a un delantero a despejar balones de cabeza en su propia área todo el partido. Cada jugador tiene una **misión única**. 

Una **interfaz funcional** es exactamente eso: un contrato que define **una sola tarea específica** (un único método abstracto). Es el "puesto" en el campo. Gracias a que solo tienen una tarea, podemos asignarles una **Lambda** directamente. La Lambda es la "orden" y la Interfaz Funcional es el "puesto" donde se ejecuta.

Sin una interfaz funcional, la Lambda está perdida en el vestuario, no sabe dónde jugar. Siempre van de la mano:
*   **La Interfaz** define el rol (ej: "El que tira los penaltis").
*   **La Lambda** es la ejecución (ej: "A la derecha y raso").

### El "Equipo de Gala" (Interfaces Predefinidas)
Java ya nos da un "once ideal" de interfaces preparadas en el paquete `java.util.function`. Estas son las cuatro posiciones clave que todo analista táctico debe conocer:

1.  **`Predicate<T>` (El Ojeador / El Árbitro):**
    *   **Misión:** Analizar a un jugador y decir `true` o `false`.
    *   **Ejemplo:** `jugador -> jugador.getEdad() < 20` (¿Es un canterano?).
    *   **Uso:** Se usa en los filtros para decidir quién sigue en la jugada.

2.  **`Function<T, R>` (El Enlace / El Creador):**
    *   **Misión:** Recibir un balón y devolver una asistencia. Transforma un dato en otro.
    *   **Ejemplo:** `crack -> crack.getSueldo()` (Recibo al jugador, devuelvo un número).
    *   **Uso:** Fundamental en el mapeo de datos.

3.  **`Consumer<T>` (El Rematador / El Finalizador):**
    *   **Misión:** Recibir el balón y terminar la jugada. No devuelve nada, solo actúa.
    *   **Ejemplo:** `titular -> System.out.println(titular)` (Recibo al jugador y lo imprimo en la ficha).
    *   **Uso:** Para ejecutar acciones finales sobre los datos.

4.  **`Supplier<T>` (El Canterano / El Utillero):**
    *   **Misión:** No recibe nada, pero siempre tiene un balón nuevo preparado. Provee datos.
    *   **Ejemplo:** `() -> new Jugador("Canterano")` (Crea un jugador nuevo de la nada).
    *   **Uso:** Para generar o suministrar objetos cuando se necesitan.



## 2.4.1. Especialistas a Medida: Tus Propias Interfaces

Escuchadme bien: a veces, el "once ideal" que nos da Java (`Predicate`, `Function`, etc.) no es suficiente para la guerra que tenemos en el campo. A veces necesitas un **especialista puro**, alguien que haga una jugada que solo tú has diseñado. Ahí es donde creas tus propias **Interfaces Funcionales**.

Esta es la verdadera flexibilidad del míster. Tú diseñas el puesto y luego, con una Lambda, le dices al jugador exactamente qué hacer.

### La Regla de Oro: "Un solo grito"
Para que tu interfaz sea funcional y el equipo no se vuelva loco, solo puede tener **un único método abstracto**. Es una orden directa. Si das dos órdenes a la vez, el jugador se bloquea. Un método, una misión.

### El Sello del Míster: `@FunctionalInterface`
En este vestuario usamos la anotación `@FunctionalInterface`. No es obligatoria para jugar, pero es como el **brazalete de capitán**. Le dice al compilador (el árbitro): *"Ojo, esta interfaz es solo para una tarea"*. Si alguien intenta añadir un segundo método por error, el compilador pita falta y detiene el juego antes de que cometamos un error fatal. ¡Es una buena práctica que no se negocia!

---

### Ejemplo Táctico: "La Arenga del Capitán"

Vamos a crear una interfaz propia llamada `Arenga`. Su única misión es emitir un mensaje motivacional antes de salir al campo.

**1. Definimos la posición (La Interfaz):**
```java
@FunctionalInterface
public interface Arenga {
    void darGrito(String mensaje); // El único método: la orden del capitán
}
```

**2. Ejecutamos la jugada (El Programa Principal):**
Aquí no perdemos el tiempo creando clases aburridas. Usamos una **Lambda** para definir el grito en el mismo momento en que lo necesitamos:

```java
public class Vestuario {
    public static void main(String[] args) {
        // Definimos la arenga con una Lambda: rápida y directa
        Arenga almada = mensaje -> System.out.println("ALMADA GRITA: " + mensaje + " ¡CON EL CUCHILLO ENTRE LOS DIENTES!");

        // El capitán sale al campo y ejecuta su función
        almada.darGrito("¡PARTIDO A PARTIDO!");
    }
}
```

### El Análisis del Analista
¿Habéis visto? No hay clases `Perro` ni `Mensajero` genéricas. Hemos creado un **`Arenga`**, le hemos asignado la personalidad de Almada mediante una Lambda y hemos invocado el método. El código es limpio, expresivo y, sobre todo, tiene **intensidad**. Esta es la base de todo lo que haremos luego con los **Streams**: definir comportamientos a medida para ganar cada balón dividido.

<p align="center">⚽ • ⚽ • ⚽ • ⚽ • ⚽ • ⚽</p>

# 3. La API de Streams: El Balón en Movimiento
## 3.1. ¿Qué es un Stream? (El Flujo de Juego)

Escuchadme bien: la **API Stream** de Java es nuestra nueva forma de jugar al fútbol total. Es la herramienta para manejar plantillas de datos enormes de forma clara, ordenada y, sobre todo, con una eficiencia que asfixia al rival. Olvidaos de los bucles `for` tradicionales; eso es fútbol de los años 50, correr por correr.

Un Stream nos permite decir **qué** queremos hacer con el balón, no **cómo** tiene que mover cada músculo el jugador. En lugar de recorrer la lista elemento a elemento como si estuviéramos pasando lista en el colegio, definimos una **jugada ensayada**: filtrar a los que están cansados, transformar una jugada defensiva en un contraataque y terminar rematando a puerta. Todo de forma declarativa, con la pizarra limpia.

### La Anatomía de la Jugada
Un Stream funciona como una secuencia de pases que siempre termina en algo concreto. Tenemos dos tipos de movimientos:

1.  **Operaciones Intermedias (Táctica):** Son los pases en el centro del campo. Preparan la jugada (filtrar, ordenar, transformar). Puedes encadenar tantos pases como quieras.
2.  **Operación Terminal (El Remate):** ¡Es el pitido final o el gol! Sin esta operación, la jugada no sirve de nada. Una vez que se ejecuta, el Stream se agota, el partido termina.

**Ojo a este concepto táctico:** Un Stream **NO es una colección**. No guarda a los jugadores, no es un almacén. Es el **flujo de los elementos** mientras se procesan. Solo existen mientras el balón está en movimiento.

### ¿Para qué nos sirve este sistema?
*   **Scouting (Filtrar):** Seleccionar solo a los jugadores que midan más de 1.90m.
*   **Entrenamiento (Transformar):** Convertir a todos los defensas en delanteros para una jugada desesperada.
*   **Estadísticas (Reducir):** Calcular la suma total de goles de la temporada.
*   **Fútbol de Élite (Paralelismo):** Si el partido es muy pesado, podemos poner a varios "árbitros" (hilos) a trabajar a la vez para ir más rápido.

En definitiva, los Streams son el **fútbol moderno**: un código más limpio, más expresivo y preparado para ganar la Champions de la programación.

<p align="center">⚽   ⚽   ⚽   ⚽   ⚽   ⚽</p>

# 4. Operaciones Intermedias: El Trabajo en el Centro del Campo

Escuchadme bien: las **operaciones intermedias** son los pases y la táctica. Por sí solas no ganan partidos; nadie mete un gol solo por dar un pase. Son **"perezosas" (Lazy)**: no hacen nada hasta que el árbitro pita el final. Se pueden encadenar para construir la jugada perfecta.

### 4.1. `.filter()` - El Filtro del Antidoping
Solo pasan los que cumplen la condición. Los demás, al banquillo.
```java
List<String> plantilla = Arrays.asList("Cazorla", "Costas", "Agudín", "Viñas");

// Solo pasan los que tienen más de 5 letras en su nombre
plantilla.stream()
    .filter(jugador -> jugador.length() > 6) 
    .forEach(System.out::println); // Resultado: Cazorla
```

### 4.2. `.map()` - El Cambio de Posición
Transformamos a los jugadores. Entra un dato, sale otro distinto.
```java
// Convertimos los nombres a mayúsculas para las camisetas
plantilla.stream()
    .map(String::toUpperCase)
    .forEach(System.out::println); // Resultado: CAZORLA, COSTAS, AGUDÍN, VIÑAS
```

### 4.3. `.sorted()` - La Tabla de Clasificación
Ordenamos la fila antes de salir al campo.
```java
// Ordenamos alfabéticamente
plantilla.stream()
    .sorted()
    .forEach(System.out::println); // Resultado: Agudín, Cazorla, Costas, Viñas
```

### 4.4. `.distinct()` - Sin Cromos Repetidos
Aquí no queremos duplicados. Solo valores únicos.
```java
List<String> cromos = Arrays.asList("Cazorla", "Cazorla", "Agudín");

cromos.stream()
    .distinct()
    .forEach(System.out::println); // Resultado: Cazorla, Agudín
```

### 4.5. `.limit()` y `.skip()` - El 11 Inicial y los Descartes
Controlamos quién entra en el flujo.
```java
List<String> cantera = Arrays.asList("Jugador1", "Jugador2", "Jugador3", "Jugador4", "Jugador5");

// Saltamos los 2 primeros y nos quedamos con los 2 siguientes
cantera.stream()
    .skip(2)
    .limit(2)
    .forEach(System.out::println); // Resultado: Jugador3, Jugador4
```

<p align="center">⚽   ⚽   ⚽   ⚽   ⚽   ⚽</p>

# 5. Operaciones Terminales: El remate a Puerta

Aquí se acaba la charla técnica. Las **operaciones terminales** disparan la acción. Una vez ejecutadas, el Stream se agota: el balón sale fuera de banda y el partido termina.

### 5.1. `.forEach()` - Instrucciones Individuales
Dar una orden a cada jugador que ha llegado al final de la jugada.
```java
plantilla.stream()
    .forEach(jugador -> System.out.println("¡A sudar la camiseta, " + jugador + "!"));
```

### 5.2. `.collect()` - El Autobús del Equipo
Recoge a los supervivientes y los mete en una lista o conjunto nuevo.
```java
List<String> convocados = plantilla.stream()
    .filter(jugador -> jugador.startsWith("C"))
    .collect(Collectors.toList()); // Metemos a Cazorla
```

### 5.3. `.reduce()` - El Marcador Final
Combinamos todos los elementos en un único resultado (como sumar goles).
```java
List<Integer> golesPorPartido = Arrays.asList(1, 2, 0, 1);

// Empezamos en 0 y sumamos cada gol
int totalGoles = golesPorPartido.stream()
    .reduce(0, Integer::sum); // Resultado: 4
```

### 5.4. `.count()` - El Acta del Árbitro
¿Cuántos jugadores quedan después de los filtros?
```java
long numeroDelanteros = plantilla.stream()
    .filter(jugador -> jugador.contains("DL"))
    .count();
```

### 5.5. Matchers: El VAR (`anyMatch`, `allMatch`, `noneMatch`)
Comprobaciones rápidas que devuelven `true` o `false`.
```java
// ¿Hay algún jugador que se llame "Messi"?
boolean tenemosAMessi = plantilla.stream()
    .anyMatch(jugador -> jugador.equals("Messi")); // Resultado: false (seguimos currando)
```

### 5.6. `.toArray()` - Formación Clásica
Convertimos el flujo en un Array de toda la vida.
```java
String[] arrayJugadores = plantilla.stream()
    .toArray(String[]::new);
```

### 5.7. `.findFirst()` y `.findAny()` - El MVP
Buscamos a un jugador concreto. ¡Cuidado! Devuelven un **`Optional`**.
```java
Optional<String> primero = plantilla.stream()
    .findFirst();

primero.ifPresent(System.out::println); // Si existe, lo muestra
```

Esta es la parte donde evitamos que el equipo se hunda por una lesión inesperada. En Java, el `null` es como un jugador que se borra del partido en el último minuto. Si no tienes un plan, pierdes.


<p align="center">⚽   ⚽   ⚽   ⚽   ⚽   ⚽</p>

# 6. La Clase Optional: El Seguro de Vida del Míster

## 6.1. El Fantasma de los Valores Nulos
Escuchadme bien: el error más estúpido en el fútbol es dar un pase al hueco esperando que esté tu delantero y descubrir que se ha quedado en el vestuario. En Java, eso se llama `NullPointerException` (NPE). 

Cuando intentas llamar a un método de un objeto que es `null` (como pedirle que remate a un jugador que no está en el campo), el programa "peta", el partido se suspende y nos vamos a casa con cara de tontos. Es el error más frecuente y el que más puntos nos quita.

## 6.2. ¿Qué es el Optional? El Informe Médico
El **Optional** es una clase que introdujo Java 8 y funciona como un contenedor, una caja. En lugar de pasarte al jugador y rezar para que no sea `null`, te paso una "caja de disponibilidad".
*   **Contiene un valor:** El jugador está listo para jugar.
*   **Está vacío:** El jugador está en la enfermería.

**¿Por qué lo usamos?** Porque obliga al programador (al míster) a reconocer que el jugador podría no estar. Nos obliga a tener un **Plan B**. Se acabó el jugar a ciegas.

---

## 6.3. Creación de Objetos Optional (Fichajes)

Hay tres formas de preparar este informe médico:

1.  **`Optional.of(jugador)`**: El fichaje estrella. Estás 100% seguro de que el jugador está ahí. Si por un casual le pasas un `null`, el sistema lanza una falta técnica inmediata (`NullPointerException`). ¡Aquí no se miente!
2.  **`Optional.ofNullable(jugador)`**: El jugador es duda hasta el último minuto. Si está, bien; si es `null`, la caja se crea vacía pero no explota. Es la forma más segura de trabajar.
3.  **`Optional.empty()`**: El puesto está vacante. Creamos una caja vacía a propósito. No hay fichajes.

```java
// 1. Seguro de que está (si es null, peta)
Optional<String> estrella = Optional.of("Cazorla");

// 2. Puede que esté o no (si es null, queda vacío)
String duda = obtenerFichajeDeUltimaHora(); 
Optional<String> quizasVenga = Optional.ofNullable(duda);

// 3. Sabemos que no hay nadie
Optional<String> vacante = Optional.empty();
```

---

## 6.4. Métodos Principales: El Plan de Emergencia

Una vez tenemos la caja, hay que saber qué hacer con ella. El míster no abre la caja en mitad del partido sin mirar antes.

### A. Comprobar disponibilidad
Antes de dar la orden, miramos si el jugador ha venido:
*   **`isPresent()`**: ¿Está en el vestuario? (`true/false`)
*   **`isEmpty()`**: ¿Está la taquilla vacía? (Desde Java 11).

### B. El Plan B (`orElse` y `orElseGet`)
Si el titular no está, sacamos al reserva. No podemos quedarnos con diez.
```java
Optional<String> delantero = mercado.buscar("Viñas");

// Si no está Viñas, juega el "Canterano" (Valor por defecto)
String titular = delantero.orElse("Canterano");

// orElseGet (Lazy): Solo se busca al canterano si Viñas falla
String titularPro = delantero.orElseGet(() -> "Canterano de la cantera");
```

### C. El "Todo o Nada" (`orElseThrow`)
Si el jugador no está y no tenemos reserva, se acaba el partido.
```java
// Si no hay portero, lanzamos una excepción porque no podemos jugar
String portero = listaPorteros.findAny()
    .orElseThrow(() -> new RuntimeException("¡No tenemos portero! ¡Dimito!"));
```

### D. La Jugada Maestra (`ifPresentOrElse`)
Controlamos los dos escenarios de forma limpia, como una jugada ensayada de pizarra.
```java
delantero.ifPresentOrElse(
    jugador -> System.out.println("¡Gol de " + jugador + "!"), // Plan A
    () -> System.out.println("Nadie remató el centro...") // Plan B
);
```

¡A las órdenes, míster! Aquí tienes la sesión de entrenamiento final. Dos ejercicios "pata negra" explicados paso a paso y una lista de 15 retos para que pases de ser un canterano a ser el capitán del equipo.

<p align="center">⚽   ⚽   ⚽   ⚽   ⚽   ⚽</p>

# 🏆 SESIÓN DE ENTRENAMIENTO: DEL BARRO AL GOL

## Ejercicio Completo 1: "La Convocatoria de Champions"
**Objetivo:** Filtrar a los jugadores que están en forma, ordenarlos por calidad y elegir a nuestros tres capitanes.

**Escenario:** Tienes una lista de jugadores con su nombre, nivel de energía (0-100) y su puntuación de "coraje" (0-10). Solo pueden ir convocados los que tengan más de 70 de energía. De esos, queremos a los 3 con más coraje.

```java
import java.util.*;
import java.util.stream.Collectors;

class Jugador {
    String nombre;
    int energia;
    int coraje;

    Jugador(String n, int e, int c) { nombre = n; energia = e; coraje = c; }
    public int getCoraje() { return coraje; }
    public String getNombre() { return nombre; }
    public int getEnergia() { return energia; }
}

public class ChampionsLeague {
    public static void main(String[] args) {
        List<Jugador> plantilla = Arrays.asList(
            new Jugador("Cazorla", 85, 10),
            new Jugador("Hassan", 90, 9),
            new Jugador("Viñas", 60, 8), // Está cansado, al banquillo
            new Jugador("Escandell", 95, 10),
            new Jugador("Vidal", 75, 7)
        );

        // LA JUGADA MAESTRA
        List<String> convocados = plantilla.stream()
            .filter(jugador -> jugador.getEnergia() > 70)                 // 1. El filtro del preparador físico
            .sorted(Comparator.comparing(Jugador::getCoraje).reversed()) // 2. De más coraje a menos
            .limit(3)                                        // 3. El 11 inicial (en este caso 3)
            .map(Jugador::getNombre)                         // 4. Solo quiero sus nombres para el acta
            .collect(Collectors.toList());                   // 5. Al autobús

        System.out.println("Nuestros tres guerreros: " + convocados);
    }
}
```

<p align="center">⚽   ⚽   ⚽   ⚽   ⚽   ⚽</p>


## Ejercicio Completo 2: "El Fichaje de Invierno con Optional"
**Objetivo:** Buscar un fichaje en el mercado y, si no lo encontramos, tirar de la cantera para no quedarnos con la caja vacía.

**Escenario:** Buscamos a un delantero que cueste menos de 40 millones. Si el mercado nos devuelve un `null`, el `Optional` debe salvarnos la vida.

```java
import java.util.Optional;

public class MercadoFichajes {
    public static void main(String[] args) {
        // Simulamos una búsqueda que podría no devolver nada
        String fichajeBuscado = null; 

        // EL PLAN DE EMERGENCIA DEL MÍSTER
        String delanteroFinal = Optional.ofNullable(fichajeBuscado)
            .filter(n -> n.equals("Mbappé")) // Si no es el que queríamos, no lo fichamos
            .map(String::toUpperCase)        // Le ponemos el nombre en grande
            .orElse("CANTERANO DE LA CASA"); // PLAN B: El esfuerzo no se negocia

        System.out.println("Saldremos al campo con: " + delanteroFinal);
        
        // JUGADA CON VAR
        Optional.ofNullable(fichajeBuscado)
            .ifPresentOrElse(
                f -> System.out.println("¡Habemus crack!"),
                () -> System.out.println("El mercado está tieso, tiramos de cantera.")
            );
    }
}
```

<p align="center">⚽   ⚽   ⚽   ⚽   ⚽   ⚽</p>

# 🏃‍♂️ LOS 15 NIVELES DE LA CANTERA (De menos a más)

### Nivel Canterano (Básicos)
1.  **El Saludo:** Dada una lista de nombres de jugadores, imprímelos todos usando `.forEach()`.
2.  **El Antidoping:** Dada una lista de edades, filtra solo las que sean mayores de 18.
3.  **Dorsales:** Convierte una lista de Strings de números ("1", "5", "10") en una lista de Integers usando `.map()`.
4.  **¿Hay alguien?:** Comprueba si en tu equipo hay algún jugador que se llame "Messi" usando `anyMatch`.
5.  **Caja Vacía:** Crea un `Optional` vacío y haz que imprima "No hay fichajes" usando `orElse`.

### Nivel Primer Equipo (Intermedios)
6.  **Pichichi:** Dada una lista de goles, usa `reduce` para sacar el total de goles de la temporada.
7.  **Sin Repes:** Tienes una lista con nombres de representantes duplicados. Usa `distinct` para quedarte con los únicos.
8.  **El Capi:** Busca al primer jugador de la lista que tenga más de 30 años usando `findFirst` y devuélvelo como `Optional`.
9.  **Limpieza de vestuario:** Filtra los nombres de jugadores que empiecen por "A", conviértelos a mayúsculas y guárdalos en una nueva `List`.
10. **Tallas de camiseta:** Dada una lista de jugadores, obtén una lista solo con las longitudes de sus nombres.

### Nivel Champions (Avanzados)
11. **Estadísticas:** Usa `count` para saber cuántos jugadores han marcado más de 20 goles.
12. **La Pizarra:** Agrupa a los jugadores por su posición (Defensa, Medio, Delantero) usando `Collectors.groupingBy`.
13. **Fichaje Relámpago:** Busca un jugador en un `Optional`. Si existe y su sueldo es mayor a 1M, aplícale un descuento del 10% (map) y si no, lanza una excepción `RuntimeException` (orElseThrow).
14. **Scouting Internacional:** Tienes una lista de Clubes y cada Club tiene una lista de Jugadores. Usa `flatMap` para obtener una única lista con TODOS los jugadores de todos los clubes.
15. **Presión Asfixiante:** Ejecuta un proceso de filtrado complejo sobre 1 millón de datos de jugadores usando `parallelStream` para demostrarle al profesor que sabes cómo ganar tiempo en el partido.
