# Guía rápida para subir archivos y ramas (local)

## 1. Clonar el repositorio
git clone https://github.com/tuusuario/FinanTienda.git
cd FinanTienda

## 2. Crear y cambiar a la rama de planificación
git checkout -b planificacion

## 3. Copiar el documento al directorio y commitear
cp "/ruta/local/Actividad 1 - Identificar el proyecto tecnológico a trabajar.docx" docs/
git add docs/"Actividad 1 - Identificar el proyecto tecnológico a trabajar.docx"
git commit -m "Agrega documento de planificación"

## 4. Subir la rama al remoto
git push origin planificacion

## 5. Crear Pull Request en GitHub desde 'planificacion' hacia 'main' y hacer merge cuando esté aprobado.
