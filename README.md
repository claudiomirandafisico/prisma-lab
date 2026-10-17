# Prisma Lab — simulador de dispersión de la luz

Simulador educativo responsive para visualizar cómo un prisma separa la luz blanca según la longitud de onda.

## Ejecutarlo localmente
Abre `index.html` en un navegador moderno. No necesita instalación ni dependencias.

## Publicarlo gratis con GitHub Pages
1. Crea un repositorio en GitHub, por ejemplo `prisma-lab`.
2. Sube `index.html` y `README.md` a la raíz del repositorio.
3. Entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
6. GitHub mostrará la URL pública cuando termine la publicación.

## Modelo físico
El simulador usa un modelo didáctico simplificado: `n(λ) = n₀ + D · (550/λ − 1)` y `v = c/n`. La trayectoria se calcula mediante la ley de Snell en las superficies del prisma. No modela absorción, reflexión parcial, aberraciones ni un vidrio comercial específico; úsalo para divulgación, no para diseño óptico profesional.
