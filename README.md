# 🐾 Administrador de Citas de Veterinaria

Aplicación práctica desarrollada durante un curso de JavaScript. Permite crear, editar y eliminar citas de pacientes de una veterinaria utilizando **IndexedDB** para guardar los datos de forma local en el navegador.

---

## 📌 Descripción

Este proyecto es un ejercicio práctico para mejorar habilidades en JavaScript, trabajando:

- Manipulación del DOM.
- Uso de clases para organizar el código.
- Validación y manejo de formularios.
- Gestión del estado mediante objetos.
- Almacenamiento con **IndexedDB**.
- Renderizado dinámico de elementos.

La aplicación permite:

- Registrar nuevas citas.
- Editarlas.
- Eliminarlas.
- Mantener los datos incluso al recargar la página gracias a IndexedDB.

---

## 🛠️ Tecnologías utilizadas

- HTML5  
- CSS3 / Bootstrap  
- JavaScript (ES6+)  
- IndexedDB  

---

## 📂 Funcionalidades principales

### ➕ Crear cita
El usuario completa el formulario y la cita se guarda en la base de datos local.

### ✏️ Editar cita
Al pulsar el botón “Editar”, el formulario se rellena automáticamente con los datos ya existentes.

### ❌ Eliminar cita
Elimina la cita de la interfaz y de IndexedDB.

### 🔄 Persistencia
Los datos se recuperan automáticamente desde la base de datos al cargar la aplicación.

---

## ⚙️ Estructura y lógica del proyecto

- **citaObj**  
  Objeto que mantiene temporalmente los datos de la cita que se está creando o editando.

- **Clase Citas**  
  Administra el listado de citas: agregar, editar, eliminar.

- **Clase UI**  
  Gestiona la interfaz: imprime alertas, genera el HTML de cada cita y actualiza el encabezado.

- **IndexedDB**  
  Se crea al iniciar la aplicación y almacena cada cita mediante un `id` único.

---

## ▶️ Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
