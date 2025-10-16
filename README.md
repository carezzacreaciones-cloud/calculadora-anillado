# Carezza — Calculadora de Anillado (Shell Canva + GitHub Pages) Ana

Este es un *shell* HTML minimalista que:
- Muestra tu diseño de **Canva** incrustado (como vista previa).
- Incluye un botón **Abrir Calculadora** que lleva a tu app funcional alojada en **GitHub Pages**.

## Cómo usar
1. Edita `index.html` y reemplaza la constante `APP_URL` por el enlace público de tu app, por ejemplo:
   ```js
   const APP_URL = "https://tuusuario.github.io/calculadora-anillado/";
   ```
2. Sube este archivo `index.html` a tu repositorio (puede ser el mismo de la app o uno distinto).
3. Activa GitHub Pages para este repo (Branch: `main`, carpeta `/`).
4. ¡Listo! Tu página mostrará el embed de Canva y el botón abrirá tu calculadora real.

> Nota: Canva no permite ejecutar el HTML externo dentro de su propio dominio. Este *shell* mantiene tu estética y vincula a la app funcionando al 100%.
