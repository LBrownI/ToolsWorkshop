# 🛠️ Git Comandos Esenciales

## ⚙️ Configuración Inicial
*(Normalmente se hace solo una vez por computador)*

* `git config --global user.name "Tu Nombre"`: Define el nombre que quedará registrado en tus commits.
* `git config --global user.email "tu@email.com"`: Define el correo electrónico asociado a tus commits.

## 🚀 Iniciar un Proyecto

* `git init`: Transforma una carpeta normal de tu PC en un repositorio Git local.
* `git clone <url-del-repo>`: Descarga una copia exacta de un repositorio desde GitHub a tu computador.

## 🔄 El "Ciclo de Oro" (Flujo de trabajo diario)

* `git status`: Muestra el estado de tu repositorio (qué archivos cambiaste, cuáles están listos para guardar, etc.). **¡Úsalo todo el tiempo!**
* `git add <nombre-archivo>`: Prepara un archivo específico para ser guardado (lo pasa al *staging area*).
* `git add .`: Prepara **todos** los archivos modificados de una sola vez.
* `git commit -m "Mensaje de lo que hiciste"`: Guarda una "foto" definitiva de los cambios preparados. El mensaje debe ser breve y claro.
* `git push`: Sube tus commits locales al repositorio en la nube (GitHub).
* `git pull`: Descarga los últimos cambios de la nube (si alguien más trabajó en el código) y los fusiona con tu código local.

## 🌿 Ramas (Branches) y Colaboración

* `git branch`: Muestra una lista de todas las ramas en tu repositorio local.
* `git branch <nombre-rama>`: Crea una rama nueva para trabajar en una funcionalidad sin romper el código principal.
* `git switch <nombre-rama>`: Cambia tu entorno de trabajo a la rama especificada (también puedes usar `git checkout <nombre-rama>`).
* `git merge <nombre-rama>`: Fusiona el código de la rama especificada hacia la rama en la que estás parado actualmente.

## 🔍 Historial y Solución de Problemas

* `git log`: Muestra el historial completo de commits realizados en el proyecto.
* `git diff`: Muestra línea por línea qué código exacto agregaste o borraste antes de hacer el `commit`.