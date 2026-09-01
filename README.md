# AppHipertrofia — Hypertrophy Science

Aplicación web para maximizar la **hipertrofia muscular en atletas naturales**, basada en evidencia científica (Brad Schoenfeld, Eric Helms, Mike Israetel, Chris Beardsley, Stuart Phillips).

## Características

- **Rutinas Full Body** predefinidas (A y B) optimizadas para principiantes/sedentarios en fase Ramp-Up.
- **Modelo de Doble Progresión**: alerta automática cuando se alcanza el tope de reps con RIR ≤ 2.
- **Temporizador adaptativo** de descanso (suma +30s si RIR ≤ 1 para resíntesis de PCr).
- **Dashboard de Volumen Semanal** con marcos MEV / MAV / MRV.
- **Catálogo de ejercicios Tier S/A** orientados a stretch-mediated hypertrophy.
- **Racha de consistencia** y creación de ejercicios personalizados.
- Persistencia local con `localStorage` (funciona offline en el gimnasio).

## Datos originales

Esta versión standalone incorpora los datos de la base Google Sheets `AppHipertrofia_Database` y la lógica del proyecto original en Google Apps Script.

La versión original en Google Apps Script (conectada a Sheets en tiempo real) está disponible en:
https://script.google.com/macros/s/AKfycbzPOhOYabPYNvH32bfVwddcdhg9R-K7309eueWLdryw0ecCUOuPsHYH4Xq8NAyTrntQ/exec

## Despliegue

Esta versión se despliega automáticamente en Vercel / Netlify como sitio estático.

## Uso

Abre `index.html` o la URL de despliegue. Todos los datos se guardan en el navegador del usuario.
