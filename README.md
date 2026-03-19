# 📅 Agenda de Sesiones — Educación Especial

Aplicación web para gestionar turnos y sesiones de atención en Educación Especial.  
Funciona completamente en el navegador, sin necesidad de servidor ni base de datos externa.

---

## ✨ Funcionalidades

- **Gestión de estudiantes**: Agregar, editar y eliminar estudiantes con datos como edad, modalidad de atención e institución.
- **Asignación de turnos**: Asignar horarios a cada estudiante por día de la semana, con opción de repetición semanal.
- **Agenda semanal**: Vista de lunes a viernes con navegación por semanas. Soporte para impresión.
- **Disponibilidad**: Panel visual que muestra los bloques horarios libres y ocupados de la semana actual, con resumen de horas y sesiones.

---

## 🚀 Cómo usar

1. Descargar o clonar el repositorio.
2. Abrir el archivo `index.html` directamente en el navegador.
3. ¡Listo! No requiere instalación.

```bash
git clone https://github.com/tu-usuario/agenda-sesiones.git
cd agenda-sesiones
# Abrir index.html en el navegador
```

---

## 💾 Almacenamiento de datos

Los datos se guardan automáticamente en el **localStorage** del navegador. Esto significa que:
- Los datos persisten entre sesiones en el mismo navegador y dispositivo.
- No se envía información a ningún servidor externo.
- Si limpiás los datos del navegador, se perderán los registros.

> 💡 Para hacer un respaldo, podés copiar los datos desde la consola del navegador con:
> ```js
> JSON.stringify(localStorage)
> ```

---

## 🏗 Estructura del proyecto

```
agenda-sesiones/
└── index.html      # Aplicación completa (HTML + CSS + JS en un solo archivo)
```

---

## 🛠 Tecnologías

- HTML5, CSS3, JavaScript puro (Vanilla JS)
- Sin dependencias externas de JS
- Fuentes: Google Fonts (Fraunces + DM Sans)

---

## 📋 Modalidades de atención soportadas

- Consultorio
- Escuela (itinerancia)
- Domicilio
- Virtual

---

## 📌 Notas

- Los turnos marcados como "recurrentes" aparecen en todas las semanas.
- Los turnos no recurrentes solo aparecen en la semana seleccionada.
- Haciendo click en un turno en la agenda semanal se puede eliminar.

---

## 📄 Licencia

MIT — libre para usar, modificar y compartir.
