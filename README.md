# Prueba Técnica para Desarrollador Frontend

**Posición:** Desarrollador Frontend 
**Duración estimada:** 3 horas

## Descripción

Esta prueba técnica está diseñada para evaluar tus conocimientos en **JavaScript** y **React**. Consta de dos partes: una sección enfocada en JavaScript y otra en React. Se valorarán buenas prácticas, organización del código, y cómo gestionas el estado en una aplicación React.

### Parte 1: JavaScript (45 minutos)

#### 1. Manipulación de Arrays y Objetos (20 minutos)

Tienes el siguiente array de objetos:

```javascript
const products = [
  { id: 1, name: 'Laptop', price: 15000, category: 'Electronics' },
  { id: 2, name: 'Chair', price: 1200, category: 'Furniture' },
  { id: 3, name: 'Headphones', price: 2000, category: 'Electronics' },
  { id: 4, name: 'Table', price: 3000, category: 'Furniture' },
];
```

Implementa una función que agrupe los productos por categoría y devuelva el resultado en el siguiente formato:

```javascript
{
  Electronics: [
    { id: 1, name: 'Laptop', price: 15000 },
    { id: 3, name: 'Headphones', price: 2000 }
  ],
  Furniture: [
    { id: 2, name: 'Chair', price: 1200 },
    { id: 4, name: 'Table', price: 3000 }
  ]
}
```

#### 2. Funciones Asíncronas (25 minutos)

Crea una función llamada `fetchUserData` que use `fetch` para obtener datos desde el endpoint `https://jsonplaceholder.typicode.com/users`.

- La función debe manejar errores de manera adecuada.
- Debe retornar solo los nombres y correos electrónicos de los usuarios en un array.

### Parte 2: React (2 horas y 15 minutos)

#### 1. Construir una Aplicación de Lista de Tareas (2 horas)

Crea una aplicación simple de React que maneje una lista de tareas. Debe cumplir con los siguientes requisitos:

- **Añadir Tareas**: Los usuarios deben poder agregar nuevas tareas.
- **Marcar como Completa**: Cada tarea debe tener un botón para marcarla como completada. Las tareas completadas deben estar visualmente diferenciadas.
- **Eliminar Tareas**: Debe existir un botón para eliminar una tarea de la lista.
- **Filtrar Tareas**: Debe existir un botón para filtrar las tareas entre "Completadas" y "Pendientes".

**Requisitos Técnicos**:

- Utiliza `useState` para manejar el estado de la lista de tareas.
- Utiliza `useEffect` para almacenar la lista de tareas en `localStorage` y cargarlas cuando la aplicación se inicie.
- El componente principal debe llamarse `TodoApp` y puede contener componentes adicionales como `TaskList`, `TaskItem`, etc.

#### 2. Pregunta de optimización (15 minutos)

Supongamos que la lista de tareas puede llegar a ser muy grande, y que algunas operaciones (como marcar como completada) se vuelven lentas. ¿Qué técnicas de optimización en React podrías utilizar para mejorar la experiencia del usuario? Explica brevemente.

## Evaluación

**Criterios de Evaluación**:

1. **Calidad del Código**: Se valorará el uso correcto de buenas prácticas, el uso de ES6 y la organización del código.
2. **Funcionalidad**: Que la aplicación cumpla con todos los requisitos mencionados.
3. **React Hooks**: Comprensión y uso adecuado de `useState` y `useEffect`.
4. **Creatividad**: Si se agrega alguna funcionalidad adicional o se mejora la UI de manera creativa.

---

Por favor, asegúrate de seguir las instrucciones y enviar el código bien comentado, en un repositorio de GitHub o similar. ¡Buena suerte!
