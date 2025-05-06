# 💠 Compose Quadrant – Diseño con Jetpack Compose

**Compose Quadrant** es una aplicación de interfaz desarrollada con **Jetpack Compose** que divide la pantalla en cuatro cuadrantes iguales, cada uno representando una función común de Compose. Esta app fue realizada como parte de la materia *Programación en Dispositivos Móviles* para aprender a organizar y estructurar componentes visuales reutilizables.

---

## 🧭 ¿Qué muestra esta app?

La pantalla está dividida en **4 secciones iguales**, cada una contiene:

- Un título en **negrita**
- Una breve descripción del elemento componible
- Fondo de color distintivo para cada cuadrante
- Textos centrados y con padding

---

## 🧩 Componentes utilizados

- `Column()` y `Row()` para dividir la pantalla vertical y horizontalmente.
- `Box()` y `Column()` dentro de cada cuadrante para posicionar y alinear el contenido.
- `Text()` para mostrar títulos y descripciones.
- `Modifier.weight(1f)` para lograr divisiones simétricas.
- Colores personalizados con `Color(0xFF...)`.

---

## 📐 Especificaciones visuales implementadas

- Cada cuadrante ocupa el **25% de la pantalla (mitad de ancho y altura)**.
- Padding interno de `16.dp` en cada cuadrante.
- El título de cada sección tiene un **padding inferior de 16.dp** y estilo `FontWeight.Bold`.
- El texto de descripción está alineado con `TextAlign.Justify`.

---

## 🖼️ Contenido de los cuadrantes

1. **Texto componible**  
   Muestra texto y sigue las guías de diseño de Material Design.

2. **Imagen componible**  
   Crea elementos que dibujan imágenes usando clases como `Painter`.

3. **Fila componible**  
   Organiza elementos de forma horizontal.

4. **Columna componible**  
   Organiza elementos de forma vertical.

---

## 🛠️ Tecnologías utilizadas

- Kotlin con Jetpack Compose
- Android Studio (Material 3)
- Previews de interfaz con `@Preview`
- Buenas prácticas de reutilización con funciones `@Composable`

---

## 🚀 Cómo ejecutar

1. Cloná el proyecto y abrilo en Android Studio.
2. Ejecutá en un emulador o dispositivo Android.
3. Observá cómo la interfaz se adapta al tamaño de pantalla, dividiéndose en 4 partes iguales.

---

## 🧑‍🎓 Autor

- **Nombre:** Derlis Gamarra  
- **Materia:** Programación en Dispositivos Móviles  
- **Universidad:** Universidad Autónoma de Asunción  

---

Este ejercicio representa un ejemplo claro de **diseño estructurado y componible**, clave para apps modernas en Android. 📲
