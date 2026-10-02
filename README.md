# Cuidado de Aziel - Panel Financiero

Esta es una aplicación web (Progresive Web App - PWA style) diseñada para gestionar y controlar el tiempo, los turnos y los pagos relacionados con el cuidado de Aziel. 

## Características

*   **Registro de Turnos:** Permite ingresar la hora de entrada y salida, calculando automáticamente las horas de cuidado.
*   **Gestión de Finanzas:** Calcula el pago total en base a una tarifa por hora configurable.
*   **Adelantos:** Permite registrar adelantos o retiros de dinero, descontándolos del pago total.
*   **Historial Mensual:** Filtra los registros por mes para llevar un control ordenado.
*   **Reportes por WhatsApp:** Genera un resumen financiero con un solo clic para enviarlo vía WhatsApp.
*   **Almacenamiento Local:** Todos los datos se guardan en tu navegador (Local Storage), por lo que funciona sin necesidad de un servidor o base de datos externa.

## Cómo usar en GitHub Pages

Para que la aplicación funcione en internet y puedas acceder desde tu celular de manera sencilla:

1. Sube todos los archivos de esta carpeta a un nuevo repositorio en tu cuenta de GitHub.
2. Ve a los **Settings** (Configuraciones) de tu repositorio.
3. En el menú lateral, busca la sección **Pages**.
4. En "Source", selecciona la rama `main` (o `master`) y la carpeta `/root`. Guarda los cambios.
5. GitHub te proporcionará un enlace (ej: `https://tu-usuario.github.io/tu-repositorio`). 
6. ¡Listo! Puedes abrir ese enlace desde cualquier dispositivo.

## Notas

*   La versión anterior basada en PHP y MySQL ha sido movida a la carpeta `backend_php/` a modo de respaldo. Para GitHub Pages, solo se utiliza el archivo `index.html` principal.
