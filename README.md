# ☕ Java Collections — Ejercicios prácticos

Ejercicios del framework de colecciones de Java (`ArrayList`, `HashMap`) aplicados a problemas reales: una biblioteca, un diccionario, un chatbot tipo ELIZA y una carrera de coches con interfaz gráfica.

---

## 📚 Contenido

| Ejercicio | Colección | Descripción |
|-----------|-----------|-------------|
| `ejeArrayList/eje01` | `ArrayList` | Carrera de coches con ventana gráfica |
| `ejeArrayList/eje02` | `ArrayList` + `enum` | Biblioteca de libros clasificados por género |
| `ejeArrayList/eje03-04` | `ArrayList` | Generación y tratamiento de valores aleatorios |
| `ejeHashmap` | `HashMap` | Biblioteca indexada por clave |
| `ejeHashmap03` | `HashMap` | Mini diccionario de traducción |
| `ejeHashmap04` | `HashMap` | **Eliza**: chatbot clásico basado en palabras clave |

<!-- TODO: añade una captura de la carrera de coches o una conversación con Eliza -->

## 🛠️ Stack

**Java 17+ · Java Collections Framework · Swing · Eclipse**

## 🚀 Ejecutar en local

```bash
git clone https://github.com/3r4yn/java-colecciones.git
cd java-colecciones
javac -d bin $(find src -name "*.java")
java -cp bin ejeHashmap04.Eliza
```

## 🧠 Decisiones técnicas

- **`ArrayList` cuando importa el orden** y el recorrido (listados, carrera); **`HashMap` cuando se busca por clave** (diccionario, respuestas de Eliza), con acceso O(1).
- **`enum Genero`** en lugar de `String` para los géneros de los libros: evita erratas y permite agrupar con seguridad de tipos.
- **Encapsulación:** entidades (`Libro`, `Coche`) separadas de las clases que gestionan las colecciones.

## 👤 Autor

**Brayan** — Estudiante de 2º DAW · [GitHub](https://github.com/3r4yn)
