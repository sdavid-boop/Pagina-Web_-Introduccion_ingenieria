# Buscador de Tareas en Tiempo Real

## 1. Descripción de la idea
Web interactiva con interfaz en modo oscuro para filtrar tareas por título o categoría en tiempo real sin recargar la página.

## 2. Característica elegida
Filtrado reactivo en el cliente y actualización dinámica del DOM usando JavaScript Vanilla y Tailwind CSS.

## 3. Qué se hizo para demostrarla
Se vinculó un evento al buscador que filtra un arreglo de datos insensible a mayúsculas y actualiza el DOM instantáneamente, mostrando una alerta visual si no hay coincidencias.

## 4. Requisito comprobable
* **Instrucción de prueba:** Abre `index.html` en el navegador y busca un término (ej. *"Diseño"* o *"XYZ"*).
* **Resultado esperado:** La lista muestra solo las coincidencias en título o categoría sin recargar. Si no hay coincidencias, avisa *"No se encontraron resultados"*.

## Instrucciones de ejecución
1. Descarga el repositorio.
2. Abre `index.html` en tu navegador (no requiere servidor ni dependencias).