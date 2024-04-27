---
author: Edgar León Martín
pubDate: 2020-03-12
title: ¿Por qué Rust debería ser tu próximo lenguaje de programación?
tags: ["rust"]
description: Rust es un lenguaje de programación desarrollado por Mozilla. En este post analizaremos por qué aprender rust y veremos sus puntos fuertes!
layout: ../../layouts/MarkdownPostLayout.astro
---

### Descubre por qué Rust es el Futuro 🚀

En este post, exploraremos las razones para aprender Rust y sus poderosos argumentos:

### 🌟 ¿Qué hace a Rust tan Especial?

Rust es un lenguaje de programación desarrollado por Mozilla. Es un lenguaje bastante joven.

Puede instalarse en la mayoría de sistemas operativos y también en hardware embebido.

Una de las cosas interesantes de rust, es que combina la velocidad de los lenguajes de bajo nivel con las herramientas, seguridad y debugging de los lenguajes de alto nivel.

### 📦 Cargo: Tu Aliado en la Programación

Cargo es el gestor de paquetes de Rust. Como NPM para javascript, Cargo recoge y compila todo lo que necesites para tu proyecto.

Para crear un nuevo proyecto en Rust usa Cargo, también se usa para verificar tu código, compilar y gestionar tus dependencias.

Todos los proyectos nuevos de Rust tienen un fichero Cargo.toml, el cual contiene los detalles del proyecto y las dependencias, parecido a package.json de node o composer.json de composer para php.

Cada vez que verificas o haces una build del proyecto, Cargo usa el fichero Cargo.toml para empaquetar todo lo que el proyecto necesita.

Si nunca has usado un gestor de paquetes, no te preocupes, Cargo es bastante simple para los primerizos!

### 💨 Rust: Rendimiento sin Límites

Rust es rápido, la manera en la que administra la memoria hace que no requiera un garbage collector (colector de basura), lo que suele dar problemas. Otros lenguajes, en cambio, tienen que estar continuamente verificando que está siendo ejecutado en tiempo real para prevenir problemas.

Rust no verifica en tiempo de ejecución, ya que el propio compilador evita que se genere código incorrecto. Esto puede hacer que tarde más en compilarse pero se ejecutará más rápidamente.

Lo dicho anteriormente, significa que gracias a su manejo inteligente de memoria no sobrecarga,por lo tanto, Rust es perfecto para hardware integrado, como por ejemplo la raspberry pi.

### 🌐 Rust para la web

Rust puede almacenar los datos directamente en un stack en memoria o en un puntero. Los datos guardados directamente en caché pueden tener una latencia hasta 30 veces menor que los datos guardados en punteros.

Por eso cachear y las estructuras de datos eficientes son importantes. Y por ello Rust hace un gran trabajo!

Por ejemplo, cuando creamos un vector dinámico en Rust, no solo se guarda el puntero al primer elemento en la pila si no que también guarda el tamaño y la capacidad del vector. Esto hace que saber la longitud del vector sea más rápido. Indirectamente también hace que otras operaciones también sean más rápidas.

### 🔐 Seguridad en la Memoria

¿Qué quiere decir que Rust sea memory safety?

Pues implica que garantiza la protección contra toda una clase de bugs que son causados por acceso no seguro a la memoria, el uso después de liberar, punteros colgantes, etc…

Errores que en otros lenguajes como C/C++ nos dan bastantes dolores de cabeza.

El compilador de Rust, vigila las localizaciones de memoria que usamos o la referencia y detecta los bugs en tiempo de compilación.

También ofrece la posibilidad de marcar nuestro código como _“unsafe”_ para manejar directamente la memoria.

### 📚 ¡Explora el Repositorio!

Gracias a Cargo y [crates.io](https://crates.io/), Rust cuenta con abundancia de librerías de calidad que podemos usar para nuestros proyectos.

Hay alrededor de 33.000 librerias en [crates.io](https://crates.io/) que podemos añadir a nuestro proyecto de Rust con un simple comando de Cargo.

Frameworks para web tenemos a [Rocket](https://rocket.rs/) y para blockchain encontramos [Substrate](https://www.parity.io/substrate).

### 🛤️ ¡Únete a la Aventura!

La decisión de aprender Rust es un viaje que no te querrás perder. Acompáñame mientras exploramos su emocionante universo.
