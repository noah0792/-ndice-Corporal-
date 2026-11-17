# Calculadora IMC Pro

App web sencilla y profesional para estimar si estás en sobrepeso con el IMC, con parámetros avanzados y diseño tipo iOS.

## Qué incluye

- Calculadora de IMC con categoría, barra visual y rango de peso normal
- Parámetros profesionales: cintura, cadera, cuello, sexo y actividad
- Estimaciones: relación cintura estatura, relación cintura cadera, grasa corporal con el método de la Marina, metabolismo basal con Mifflin St Jeor y gasto total
- Ajustes: tema claro, oscuro o automático, 6 colores de acento, 4 tipos de letra, unidades métricas o imperiales
- Historial guardado en el navegador con localStorage
- Todo en un solo archivo, sin servidor ni instalación

## Cómo subirlo a GitHub

### Opción 1: desde la web de GitHub

1. Entra a github.com y crea un repositorio nuevo, por ejemplo calculadora-imc
2. Elige que sea público si quieres usar GitHub Pages gratis
3. En la página del repositorio, pulsa Add file y luego Upload files
4. Arrastra index.html, README.md y .gitignore a la ventana
5. Pulsa Commit changes

### Opción 2: desde tu computadora con Git

Usa estos comandos en la carpeta donde guardaste los archivos:

git init
git add index.html README.md .gitignore
git commit -m "Primera versión de Calculadora IMC Pro"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/calculadora-imc.git
git push -u origin main

Cambia TU_USUARIO y calculadora-imc por tu usuario y tu repositorio.

## Cómo publicarlo con GitHub Pages

1. En tu repositorio, entra a Settings y luego a Pages
2. En Build and deployment, elige Deploy from a branch
3. En Branch, elige main y carpeta / (root)
4. Pulsa Save
5. Espera unos segundos y abre el enlace que te da GitHub, será algo como https://TU_USUARIO.github.io/calculadora-imc/

## Archivos

- index.html: toda la app, lista para publicar
- README.md: esta guía
- .gitignore: archivos que Git debe ignorar

## Nota de salud

Es una herramienta informativa, no un diagnóstico. Para menores de 18 años, el IMC se interpreta con percentiles. Si buscas cambiar tu peso, hazlo con acompañamiento profesional.
