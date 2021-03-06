# Histórico de cambios
>Todos los cambios notables de este proyecto se documentarán en este archivo.

## [v0.5.4] - 2021-07-14
> Revisión
### Añadidos
* Descarga de la librería ***CalendarLinkFunctions.php** en las tareas.
* Configuración para validar algunos archivos ***json***.
* Configuración específica para archivos de ***shell***.
* Añadida extensión ***Code Spell Checker*** con lenguaje español.

### Corrección de errores
* Eliminada extensión PHP Intellisense porque ya no aparece en el repositorio
  de extensiones de VSCode.

---
## [v0.5.3] - 2021-06-21
> Revisión
### Añadidos
* Configuración específica para archivos JSON en ***settings.json***.
* Configuración específica para archivos .env en ***settings.json***.
* Añadida extensión "ENV" y su configuración.
* Añadido snippet "use" para la librería MarkdownParser.
* Añadido archivo ***.editorconfig*** con datos específicos para Drupal
  (se incluye la tarea para la descarga en *tasks.json*).
* Configuración en **launch.json** para ejecutar XDebug dentro de Docker.

### Corrección de errores
* Mejorada la agrupación de las tareas en ***tasks.json***.

---
## [v0.5.2] - 2021-05-31
> Revisión
### Añadidos
* Nuevo snippet para generar la librería de un formulario base.
* Se añade gestión de caché en el snippet para generar la librería de "Blocks".
* Nueva configuración para trabajar con archivos json más grandes.
* Añadida extensión "GitLab Workflow" y su configuración base.

### Corrección de errores
* Error con una coma al generar un campo hidden para los formularios.

---
## [v0.5.1] - 2021-05-07
> Revisión
### Añadidos
* Nueva tarea para descargar MarkdownParser.
* Ahora en cada commit se realiza un push de manera automática.
* Nueva extensión para gestionar Composer (y configuración).
* Nueva extensión "phpcbf" (y configuración).
* Nueva extensión opcional "Remote - Containers".
* Nueva extensión opcional "Json Editor" (y configuración).

### Cambios
* Mejora visual de las tareas en Task Manager.
* Se han movido las configuraciones de ***settings.json*** para encontrar más
  fácilmente aquellas que necesitan ser revisadas por el usuario o que son más
  susceptibles de requerir cambios.
* Eliminación de algunas configuraciones obsoletas.
* Actualización de algunas configuraciones obsoletas para la versión 1.57.0

---
## [v0.5.0] - 2021-04-15
> Revisión
### Añadidos
* Nuevas configuraciones disponibles en la versión 1.55.0 de VSCode.
* Nueva extensión "Remote - SSH".
* Nueva extensión "Commit Message Editor" y configuración para la misma.
* Se añade macro para duplicar línea y comentar la anterior en
  ***settings.json***.
* Nuevos snippets de formulario (***drupal_form.code-snippets***).

### Cambios
* La extensión "Live - SASS" pasa a ser opcional.
* La extensión "Edit CSV" pasa a ser opcional.
* La extensión "Shell launcher" pasa a ser opcional.
* Modificación de ***settings.json*** con pequeñas ayudas para usar phpmd en
  Ubuntu cuando se trabaja vía SSH.
* Modificación de los snippets de javascript (***drupal_js.code.snippets***).

### Corrección de errores
* Reparación de error en ***launch.json*** con el tipo "chrome".

---
## [v0.4.0] - 2021-04-06
> Revisión
### Añadidos
* Se ha creado un nuevo archivo de snippets (***drupal_clases.code-snippets***)
  que permite generar el contenido de algunas clases de forma automática.
* Se han añadido nuevos snippets en ***drupal_uses.code-snippets***.
* Añadida extensión "Git History Diff".
* Añadida extensión opcional "Macros".

---
## [v0.3.5] - 2021-03-29
> Revisión
### Añadidos
* Actualización de la configuración en ***settings.json***.
* Extensión opcional **Draw.io Integration**.
* Excepción en ***sftp.json*** para no subir la configuración del pipeline.

---
## [v0.3.4] - 2021-03-26
> Revisión
### Añadidos
* Extensión Material Icon Theme.
* Más configuraciones para VSCode en ***settings.json***.
* Configuración adicional para la extensión *Bookmarks* (ahora guarda los
  bookmarks en el proyecto y no en VSCode).
* Se han incorporado nuevos snippets al archivo ***drupal_uses.code-snippets***.

### Cambios
* Se han movido algunas extensiones al área de "no recomendar" del archivo
  ***extensions.json*** al no ser extrictamente necesarias para codificar en
  Drupal.
* Se actualiza la información del ***README.md***.
* Se modifican algunos parámetros del archivo ***sftp.json***.
* Se han añadido variables de entorno a las rutas de los ejecutables en
  ***settings.json***.

---
## [v0.3.3] - 2021-03-22
> Revisión
### Añadidos
* Extensión Bookmarks.
* Extensión Bracket Pair Colorizer 2 (y configuración).
* Extensión Color Highlight (y configuración).

### Cambios
* Modificacion de la configuración del módulo TODO Tree.

---
## [v0.3.2] - 2021-03-15
> Revisión
### Añadidos
* Nuevo módulo recomendado ***PHP Server***.
* Nuevo módulo recomendado ***ShellCheck***.

---
## [v0.3.1] - 2021-02-09
> Revisión
### Añadidos
* Nuevas configuraciones para la versión ^1.53.0 de VSCode.
* Añadidas exclusiones de directorios para que no se muestren en el
  explorador aquellos que no son necesarios.
* Añadida tarea para descargar la librería Mailing en ***tasks.json***.

---
## [v0.3.0] - 2021-02-03
> Revisión
### Añadidos
* Exclusiones de directorios en ***phpmd.xml***.
* Nuevos snippets para los formularios.
* Añadidas nuevas excepciones a ***.gitignore***.
* Añadido archivo ***extensions.json** para ayudar a descargar todos los
  módulos que yo uso.
* Añadida configuración para ***Better Comments***.
* Añadida configuración para poder usar el "Cmder" que viene con Laragon.

### Cambios
* Mejora de la información del ***README.md***.
* Se han simplificado los nombres de los snippets de formularios.
* Aunque se mantienen las tareas para Docker, se ha decidido dejarlas
  comentadas.

### Corrección de errores
* Algunos snippets de formularios estaban mal formateados.
* Eliminadas algunas extensiones que ya no existen en el repositorio de VSCode.
* Reparación de algunas tareas en ***tasks.json** que no funcionaban
  correctamente.

---
## [v0.2.3] - 2021-01-30
> Revisión
### Añadidos
* Configuración para usar ***Shell Launcher*** (bajo Windows).
* Añadida tarea para descargar una nueva librería (*DateTimeFunctions*).
* Nueva tarea npm para crear una primera versión con standard-version.

### Cambios
* Modificación en el orden de las configuraciones de ***settings.json***.

---
## [v0.2.2] - 2021-01-25
> Revisión
### Añadidos
* Configuración específica para resolver un problema con el lenguaje
  Markdown y los saltos de línea.
* Nuevos scripts en ***package.json*** para trabajar con standard-version.
* Configuración para usar ***phpmd*** en la documentación.
* Añadida a ***settings.json** la configuración para el módulo PHP Mess
  Detector.

---
## [v0.2.1] - 2021-01-22
> Revisión
### Añadidos
* Archivo ***.versionrc*** para la generación personalizada del CHANGELOG.md
  con standard-version.

### Cambios
* Cambiado en ***phpdox.xml*** el tipo de archivo generado a HTML en lugar de
  XHTML.
* Cambiado el nombre de las tareas relacionadas con standard-version en el
  archivo ***package.json***

---
## [v0.2.0] - 2021-01-20
> Revisión
### Añadidos
* Nuevos snippets en ***drupal_form.code-snippets***.
* Configuración para generar documentación técnica (**phpdox** y **phploc**).

### Cambios
* Ampliación de módulos importantes y mejora de la configuración para XDebug.
* Mejora en la configuración de PHP DocBlocker.

---
## [v0.1.1] - 2021-01-08
> Revisión
### Añadidos
* Nuevas tareas en ***tasks.json*** para descargar o actualizar la configuración
  desde GitHub.
* Nuevas tareas en ***tasks.json*** para descargar o actualizar mis librerías
  desde GitHub.
* Nuevos snippets en ***drupal_form.code-snippets***.
* Nuevas exclusiones en el archivo ***sftp.json***.
* Añadido ***package.json** para usar standard-version.

### Corrección de errores
* Problema de duplicado en los snippets de formularios.

### Eliminados
* Se han quitado las tareas de git por no ser necesarias en VSCode.

---
## [v0.1.0] - 2021-01-04
> Revisión
### Añadidos
* Módulo GitHub Pull Requests and Issues para VSCode.
* Módulo Rainbow CSV.
* Módulo WakaTime.
* Módulo jQuery Code Snippets.
* Archivo .gitattributes para Drupal.
* Se han incorporado snippets para javascript ***drupal_js.code-snippets***.

### Cambios
* Pequeñas modificaciones en los snippets en ***drupal_form.code-snippets***.
* Ampliar excepciones en ***sftp.json***.
* Modificación del salto de línea de los snippets.
* Ampliación del archivo .gitignore.

---
## [v0.0.4] - 2020-12-11
> Revisión
### Añadidos
* Se han incorporado nuevos snippets al archivo ***drupal_uses.code-snippets***.
* Se han añadido snippets en el archivo ***drupal_form.code-snippets***.
* Se ha incluído la configuración de sftp para conexiones a servidores vía ssh.

### Cambios
* Se excluye el archivo ***phpcs.xml** del envío automático por ftp en el
  archivo ***sftp.json***.

---
## [v0.0.3] - 2020-11-09
> Revisión
### Añadidos
* Archivo ***phpcs.xml** con algunas excepciones para la codificación en
  Drupal que a mí me son de utilidad.

### Cambios
* Se han ampliado algunos valores de los snippets de formulario.
* Añadidos varios servidores para el módulo sftp.

---
## [v0.0.2] - 2020-10-28
> Revisión
### Añadidos
* Se han incorporado nuevos snippets al archivo ***drupal_uses.code-snippets***.
* Se han añadido snippets en el archivo ***drupal_form.code-snippets***.
* Se han añadido tareas para docker-compose en **tasks.json**.

### Corrección de errores
* Reparados todos los snippets del archivo ***drupal_form.code-snippets*** que
  les faltaba un ";" para cerrar cada elemento de formulario.

---
## [v0.0.1] - 2020-10-08
> Primera versión.
