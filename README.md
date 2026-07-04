# 🌳 Trabajo Práctico N.º 5 - Árboles Binarios | Algoritmos y Estructura de Datos II

![Java](https://img.shields.io/badge/Java-17%2B-orange?logo=openjdk)
![Estado](https://img.shields.io/badge/Estado-Finalizado-success)
![Licencia](https://img.shields.io/badge/Licencia-Uso%20Acad%C3%A9mico-blue)

## 📖 Descripción

Este trabajo práctico introduce la implementación de la estructura de datos **Árbol Binario** utilizando el lenguaje **Java**.

El proyecto desarrolla las clases necesarias para representar un árbol binario mediante nodos enlazados, permitiendo crear árboles, acceder a su raíz y verificar si la estructura se encuentra vacía.

Como ejemplo de utilización, se construye un árbol binario utilizando una pila (`ArrayDeque`), demostrando el proceso de creación de subárboles y su posterior unión en un único árbol.

---

# 🎯 Objetivos

- Comprender la estructura de un Árbol Binario.
- Implementar nodos enlazados mediante referencias.
- Construir árboles utilizando programación orientada a objetos.
- Aplicar encapsulamiento mediante clases independientes.
- Utilizar estructuras auxiliares (Pila) para la construcción del árbol.

---

# 🛠️ Tecnologías utilizadas

- ☕ Java
- IntelliJ IDEA
- Programación Orientada a Objetos (POO)

---

# 📂 Estructura del proyecto

```
src/
│
├── Nodo.java
├── ArbolBinario.java
└── Main.java
```

### 📌 Nodo.java

Representa cada nodo del árbol.

Contiene:

- Dato almacenado
- Referencia al hijo izquierdo
- Referencia al hijo derecho
- Constructores
- Métodos getters y setters

---

### 🌳 ArbolBinario.java

Implementa la estructura principal del árbol.

Funciones principales:

- Constructor vacío.
- Constructor con raíz.
- Obtener la raíz.
- Verificar si el árbol está vacío.
- Crear nuevos nodos mediante un método estático.

---

### 🚀 Main.java

Clase encargada de probar el funcionamiento del árbol.

Durante la ejecución:

- Se crean distintos nodos.
- Se generan subárboles.
- Se utiliza una pila (`ArrayDeque`) para almacenar árboles temporales.
- Finalmente se construye un árbol binario completo.

---

# ⚙️ Conceptos aplicados

- Árboles Binarios
- Nodos enlazados
- Pilas (Stack)
- Referencias entre objetos
- Constructores
- Encapsulamiento
- Programación Orientada a Objetos

---

# ▶️ Ejecución

1. Clonar el repositorio.

```bash
git clone https://github.com/MartinGaGi/tp5-AyED2.git
```

2. Abrir el proyecto con IntelliJ IDEA o cualquier IDE compatible con Java.

3. Ejecutar la clase:

```
Main.java
```

---

# 📚 Estructura del árbol generado

El programa construye el siguiente árbol:

```
                Ester
               /     \
          M Jose   Esperanza
          /   \      /    \
      Diego Astor Esteban Ariel
```

---

# 👨‍💻 Alumno

- Martin Gabriel Gimenez

---

---

# ⭐ Contenido académico

En este trabajo se ponen en práctica los siguientes temas:

- Implementación de Árboles Binarios.
- Creación de nodos enlazados.
- Construcción manual de árboles.
- Manejo de referencias.
- Utilización de pilas para organizar la construcción del árbol.
- Organización del código mediante Programación Orientada a Objetos.

---

## 📌 Estado del proyecto

✅ Trabajo práctico finalizado.
