# Repaso de Kotlin

Este es un breve repaso sobre Kotlin, un lenguaje de programación moderno desarrollado por JetBrains. Kotlin se ha convertido en un lenguaje popular para el desarrollo de aplicaciones Android y también se puede utilizar para desarrollar aplicaciones en otras plataformas.

## Tabla de contenidos

1. [¿Qué es Kotlin?](#qué-es-kotlin)
2. [Características principales](#características-principales)
3. [Sintaxis básica](#sintaxis-básica)
4. [Tipos de datos y variables](#tipos-de-datos-y-variables)
5. [Funciones](#funciones)
6. [Programación orientada a objetos](#programación-orientada-a-objetos)
7. [Null Safety](#null-safety)
8. [Recursos adicionales](#recursos-adicionales)

## ¿Qué es Kotlin?

Kotlin es un lenguaje de programación moderno y conciso que se ejecuta en la máquina virtual de Java (JVM). Fue desarrollado por JetBrains con el objetivo de ser interoperable con Java y mejorar la productividad de los desarrolladores.

Kotlin es un lenguaje seguro, expresivo y fácil de leer, lo que lo convierte en una excelente opción tanto para principiantes como para desarrolladores experimentados. Además, Kotlin proporciona muchas características modernas, como la programación funcional y la seguridad de tipo nulo, que ayudan a reducir errores y mejorar la calidad del código.

## Características principales

Algunas de las características principales de Kotlin incluyen:

- **Interoperabilidad**: Kotlin es compatible con Java y puede interoperar sin problemas con el código Java existente. Esto permite a los desarrolladores utilizar bibliotecas y herramientas de Java en proyectos de Kotlin.

- **Null Safety**: Kotlin tiene un sistema de tipos que ayuda a evitar errores de referencia nula en tiempo de compilación. Esto significa que el manejo de valores nulos está integrado en el lenguaje y se fomenta el uso de prácticas seguras para evitar errores comunes.

- **Funciones de extensión**: Kotlin permite agregar nuevas funciones a clases existentes sin modificar su código fuente. Esto facilita la adición de funcionalidad a bibliotecas externas o clases de terceros.

- **Programación orientada a objetos**: Kotlin es un lenguaje orientado a objetos en el que todo es un objeto. Proporciona características como herencia, polimorfismo y encapsulamiento para estructurar y organizar el código.

- **Programación funcional**: Kotlin admite programación funcional y ofrece características como funciones de orden superior, lambdas y expresiones de función. Esto permite un código más conciso y legible, y fomenta un estilo de programación más declarativo.

## Sintaxis básica

La sintaxis de Kotlin es similar a la de otros lenguajes modernos como Java o C#. Aquí hay un ejemplo básico de un programa Kotlin:

```kotlin
fun main() {
    println("¡Hola, Kotlin!")
}
```

En este ejemplo, `main()` es la función de entrada del programa y `println()` se utiliza para imprimir un mensaje en la consola.

## Tipos de datos y variables

Kotlin proporciona varios tipos de datos, incluyendo enteros, flotantes, caracteres, booleanos y cadenas de caracteres. Además, Kotlin permite declarar variables como mutables (`var`) o inmutables (`val`).

Aquí hay un ejemplo de declaración de variables en

 Kotlin:

```kotlin
val nombre: String = "Juan"
var edad: Int = 25
```

En este ejemplo, `nombre` es una variable inmutable de tipo `String` y `edad` es una variable mutable de tipo `Int`.

## Funciones

En Kotlin, las funciones se definen con la palabra clave `fun`. Pueden tener parámetros y devolver un valor. Aquí hay un ejemplo de una función que suma dos números:

```kotlin
fun sumar(a: Int, b: Int): Int {
    return a + b
}
```

En este ejemplo, la función `sumar` toma dos parámetros de tipo `Int` y devuelve un valor de tipo `Int`.

## Programación orientada a objetos

Kotlin es un lenguaje orientado a objetos en el que todo es un objeto. Permite la definición de clases, interfaces, herencia y polimorfismo. Aquí hay un ejemplo básico de una clase en Kotlin:

```kotlin
class Persona(val nombre: String, var edad: Int) {
    fun saludar() {
        println("Hola, mi nombre es $nombre y tengo $edad años.")
    }
}
```

En este ejemplo, se define una clase `Persona` con una propiedad `nombre` y una propiedad mutable `edad`. La clase también tiene un método `saludar()` que imprime un mensaje utilizando las propiedades de la clase.

## Null Safety

Kotlin aborda el problema de los valores nulos en tiempo de compilación mediante su sistema de tipos de nulo. En Kotlin, los tipos de datos pueden ser nulos o no nulos, lo que ayuda a prevenir errores de referencia nula.

Por ejemplo, para declarar una variable que puede ser nula, se utiliza el operador `?` después del tipo de datos:

```kotlin
val resultado: Int? = null
```

En este caso, `resultado` puede contener un valor entero o ser nulo.

## Recursos adicionales

- [Documentación oficial de Kotlin](https://kotlinlang.org/docs/): La documentación oficial de Kotlin proporciona una guía completa sobre el lenguaje, incluyendo tutoriales, referencias y ejemplos.
- [Kotlin Playground](https://play.kotlinlang.org/): Un entorno en línea donde puedes probar y ejecutar código Kotlin sin necesidad de configuración adicional.
- [Kotlin Koans](https://kotlinlang.org/docs/tutorials/koans.html): Una serie de ejercicios interactivos que te ayudarán a aprender Kotlin paso a paso.
- [Kotlin en Android](https://developer.android.com/kotlin): Información y recursos específicos sobre el uso de Kotlin para el desarrollo de aplicaciones Android.

Este repaso solo proporciona una introducción básica a Kotlin. A medida que profundices en el lenguaje, descubrirás muchas más características y conceptos avanzados que te ayudarán a escribir código más eficiente y conciso.
