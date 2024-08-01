1. **DESCRIPCIÓN DEL PROYECTO**

Nuestro proyecto se basa en el desarrollo de una aplicación móvil para conectar personas con intereses comunes en hacer ejercicio. Esta aplicación facilitará a los usuarios encontrar compañeros de entrenamiento en gimnasios y otros lugares, satisfaciendo la necesidad de socializar y mantenerse motivados en su rutina de ejercicios. Generará beneficios al crear una comunidad activa de entusiastas del fitness, promoviendo un estilo de vida saludable y ofreciendo una plataforma segura y accesible para formar nuevas amistades y colaboraciones deportivas.

2. **LISTA DE COMANDOS UTILIZADOS Y SU PROPÓSITO**
   Esta lista cubre los comandos esenciales utilizados durante la práctica, así como sus propósitos específicos en el contexto del manejo de Git y GitHub en un entorno colaborativo.

 2.1. Configuración Inicial de Git:
     - `git config --global user.name "Tu Nombre"`: Configurar el nombre de usuario que se asociará con los commits realizados en el repositorio.
     - `git config --global user.email "tu.email@ejemplo.com"`: Configurar la dirección de correo electrónico que se asociará con los commits realizados en el repositorio.

 2.2. Creación y Clonación de Repositorio:
     - `git clone https://github.com/usuario/proyecto_grupo.git`: Descargar una copia completa del repositorio desde GitHub a la máquina local del usuario.
     - `cd [directorio]`: Cambiar al directorio especificado en la línea de comandos, útil para navegar a la carpeta del repositorio local.
     - `touch [archivo]`:  Crear un nuevo archivo vacío con el nombre especificado, o actualizar la fecha de modificación de un archivo existente. 

 2.3. Inicialización del Proyecto:
   - `git add .`: Añadir todos los archivos modificados y nuevos al área de preparación (staging area) para su inclusión en el próximo commit.
   - `git commit -m "Initial commit"`: Guardar los cambios en el repositorio local con un mensaje descriptivo sobre los cambios realizados.
   - `git push origin main`: Enviar los commits realizados en la rama `main` del repositorio local al repositorio remoto en GitHub.

 2.4. Trabajo en Ramas (Branches):
   - `git checkout -b nombre_rama`: Crear una nueva rama con el nombre especificado y cambiar a esa rama para realizar modificaciones independientes.
   - `git add .`:  Añadir los cambios realizados en los archivos a la zona de preparación para su inclusión en el próximo commit.
   - `git commit -m "Descripción de los cambios"`: Guardar los cambios realizados en la rama actual con un mensaje descriptivo.

 2.5. Merge y Resolución de Conflictos:
   - `git push origin nombre_rama`: Enviar los cambios realizados en la rama específica al repositorio remoto en GitHub.
   - `git checkout main`: Cambiar a la rama `main` para preparar la fusión de cambios.
   - `git merge nombre_rama`: Fusionar los cambios de la rama especificada en la rama `main`. Este comando puede generar conflictos si los cambios son incompatibles.
   - `git push origin main`: Enviar los cambios fusionados en la rama `main` al repositorio remoto en GitHub.

 2.6. Colaboración y Pull Requests:
   - `git pull origin main`: Actualizar el repositorio local con los últimos cambios realizados en la rama `main` del repositorio remoto en GitHub.


3. **ENLACE AL REPOSITORIO EN GITHUB**

https://github.com/JuanParias29/proyecto_grupo.git
