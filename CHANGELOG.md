# Histórico de cambios
>Todos los cambios notables de este proyecto se documentarán en este archivo.

## [v0.8.11] - 2025-06-17
> Revisión
### Cambios
  - Se ha eliminado la extensión UNotes ya que ha dejado de
    estar disponible además de no funcionar muy bien.

---
## [v0.8.10] - 2025-06-13
> Revisión
### Cambios
  - Ajustes en settings.php con los directorios por defecto de ciertas
    herramientas de PHP.
  - Ajustes en configuración para plugin "todo-tree".

---
## [v0.8.9] - 2025-05-13
> Revisión
### Añadidos
  - Archivo de instrucciones para generar commits.
  - Tarea para descargar este archivo.

### Cambios
  - Se ha modificado la extensión para visualizar Markdowns por una más
    completa.

### Corrección de errores
  - El README.md hacía referencia a extensiones que ya no están.

---
## [v0.8.8] - 2025-05-02
> Revisión
### Añadidos
- Configuración para GrumPHP.

### Cambios
- Ajustes en fichero sftp.json para hacerlo compatible con "iniciar-proyecto".
- Ajustes en ficheros de documentación.
- Ajustes en .gitignore.
- Ajustes en documentación.

---
## [v0.8.7] - 2025-04-21
> Revisión
### Añadidos
- Configuración para copiar automáticamente en el terminal.
- Configuraciones adicionales para Copilot.
- FUNDING.yml

### Cambios
- Vuelvo a mostrar la carpeta .github en el explorador de archivos.
- Modificación phpmd.xml para adaptarlo a como lo uso con GrumPHP.
- Modificación phpstan.neon para adaptarlo a como lo uso con GrumPHP.
- Cambio de extensión de Git Graph para una con mejor mantenimiento.
- Refactor total del prompt inicial de Copilot.

### Corrección de errores
- Snippet de formulario, se cambia la inyección de dependencias para inyectar
  el servicio Entity Type Manager en lugar de Current user, ya que este último
  ya viene por defecto.

### Eliminados
- Ya no está disponible el archivo phpdox.xml.
- La extensión SVG Preview ya no es necesaria en VSCode (1.97).
- Limpieza de otras extensiones obsoletas que formaban parte de
  "unwantedRecommendations"
- Se han quitado todas las task de descarga de librerías.

---
## [v0.8.6] - 2024-12-12
> Revisión
### Añadidos
- Configuración para ver iconos en lugar de etiquetas en el panel inferior de la
  consola (config. añadida en versión 1.95).
- Ajustes configuración CSpell y Copilot.
- Extensión para usar DeepL.
- Configuración para Git Blame que ahora viene incluido en VSCode
  (config. añadida en versión 1.96).

### Corrección de errores
- Error en snippet de Block.

### Eliminados
- Extensión Git-Blame (ya no es necesaria a partir de la versión v1.96).
- Ahora desde tasks ya no se descarga el archivo phpdox.xml.

---
## [v0.8.5] - 2024-10-10
> Revisión
### Añadidos
- Descarga de sftp.json.
- Descarga de copilot-instructions.md.

### Cambios
- Ajustes en snippets de clases. Inyección de dependencias en form base.
  Revisión general de como se inyectan las dependencias.

---
## [v0.8.4] - 2024-09-12
> Revisión
### Añadidos
- Configuración adicional para iniciar un proyecto en blanco.
- Nuevos botones en ActibitusBar.
- "declare(strict_types=1);" en los snippets de clases.

### Corrección de errores
- Error en snippet de Controller.

### Eliminados
- Extensión Nyan-mode.

### Cambios
- La configuración para usar el script iniciar-proyecto.sh se ha cambiado a la
  sección de CONFIGURACIÓN DE USUARIO. Tiene mucho más sentido que esté ahí
  ahora que el script permite generar un proyecto a partir del código actual.
- Ajustes para versión v.1.92 => Ver histórico de commits.
- Ajustes para versión v.1.93 => Archivo de instrucciones para copilot.

---
## [v0.8.3] - 2024-07-30
> Revisión
### Añadidos
- Ajustes para versión v.1.91 => Ver histórico de commits.

### Cambios
- Mejora en snippet de Bloque para inyección de dependencias.

---
## [v0.8.2] - 2024-01-24
> Revisión
### Añadidos
- Extensión para usar PHPStan.
- Configuración para PHPStan.
- Tarea para añadir la descarga de phpstan.neon con la documentación.
- Pequeños ajustes en gitignore.
- Extensión "Run Terminal Command" y configuración para usar [mi script de
  instalación](https://github.com/oscarnovasf/iniciar-proyecto)
- Modificaciones en launch.json para debug en phpunit.

### Corrección de errores
* Problema de visualización con el snippet añadido en la versión v0.8.0.

---
## [v0.8.1] - 2023-11-16
> Revisión
### Corrección de errores
* Problema de visualización con el snippet añadido en la versión v0.8.0.

---
## [v0.8.1] - 2023-11-16
> Revisión
### Añadidos
* Snippet para generar el campo "range" en los formularios.

### Corrección de errores
* Problema de visualización con el snippet añadido en la versión anterior.

---
## [v0.8.0] - 2023-11-13
> Revisión
### Añadidos
* Nuevo snippet para librería con inyección de dependencias.
* Nuevas excepciones en el archivo sftp.json.

### Cambios
* Se agrega inyección de dependencias al snippet de Controlador.

---
## [v0.7.26] - 2023-10-20
> Revisión
### Añadidos
* Extensión opcional SVG Preview.

---
## [v0.7.25] - 2023-10-18
> Revisión
### Añadidos
* Configuraciones nuevas para la versión 1.83.
* Snippet nuevo para formulario (reset).

---
## [v0.7.24] - 2023-09-17
> Revisión
### Añadidos
* Mejora en la documentación de las extensiones.

### Eliminados
* Tareas en tasks.json que no uso.

---
## [v0.7.23] - 2023-08-27
> Revisión
### Añadidos
* Extensión REST Client Api para sustituir a Thunder Client.

### Cambios
* Establecida rama "main" como principal al usar gitflow.
* En la configuración de SFTP eliminamos el watcher porque estaba dando
  problemas.

### Eliminados
* Extensión Thunder Client porque ahora es de pago.

---
## [v0.7.22] - 2023-07-19
> Revisión
### Añadidos
* Ajustes para formatear PHP.
* Extensión Git Graph.
* Extensión GitFlow Actions Sidebar.
* Extensión opcional GitHub Copilot.
* Extensión Smart Clicks.

### Cambios
* Modificaciones en Activitusbar para eliminar atajos que ya no uso y añadir
  otros que si necesito.

### Eliminados
* Extensión Git History, sustituido por Git Graph.
* Extensión Commit Message Editor, ya no lo uso.
* Extensión Replace Rules, ya no lo uso.

### Corrección de errores
* Elimino del Live Sass Compiler los directorios de módulos contrib y la
  carpeta vendor.
* Ajustes de formato en el archivo settings.json.

---
## [v0.7.21] - 2023-07-05
> Revisión
### Añadidos
* Nuevas configuraciones para v1.79.0.
* Módulo px to rem & rpx & vw (cssrem).
* Tema "Copilot Theme" por defecto.
* Ajustes para "json.schemas".

### Eliminados
* Extensión CSS Peek porque no se mantiene.

### Corrección de errores
* Corrección en la asociación de archivos twig.html.
* Eliminación de documentación errónea.

---
## [v0.7.20] - 2023-06-03
> Revisión
### Añadidos
* Configuración para que el archivo .env.example sea tratado como una archivo de
  variables de entorno.
* Extensión "Auto Rename Tag".
* Extensión opcional "Nyan-mode".

### Cambios
* Muevo la sidebar a la derecha por comodidad.

---
## [v0.7.19] - 2023-04-17
> Revisión
### Añadidos
* Extensión opcional "SQLTools".
* Extensión "Lando UI".
* Extensión "Composer".

### Eliminados
* Extensión "JS & CSS Minifier (Minify)" por no tener mantenimiento.

### Corrección de errores
* Eliminar documentación obsoleta.

---
## [v0.7.18] - 2023-03-21
> Revisión
### Añadidos
* Nuevos snippets de formulario.
* Nueva extensión "AutoHide".

### Corrección de errores
* Solucionado problema con la extensión SASS que compilaba archivos dentro de
  la carpeta "libraries".

---
## [v0.7.17] - 2023-02-10
> Revisión
### Añadidos
* Twig braces helper.
* PHP Intelephense.
* PHPUnit Test Explorer.
* Función para redireccionar a "destination" en el snippet de Controller.
* Ampliación de restricciones en el gitignore de los proyectos.
* Extensión UNotes.
* Extensión opcional Lando UI (añadida también como icono a la toolbar).
* Extensión platform-settings que nos permite gestionar diferentes
  configuraciones según el SO... (reestructura de settings para su uso).

### Cambios
* Arreglos menores de configuración para los snippets de twig.
* Adaptación de configuración para v1.75

---
## [v0.7.16] - 2022-12-20
> Revisión
### Añadidos
* Nuevas excepciones al listar las tareas en `Task Manager`.
* Git History.
* Git Blame.
* Git Commits.
* Nuevas configuraciones añadidas en VSCode 1.74.

### Cambios
* Mejoras en la configuración de Live Sass Compiler.

### Eliminados
* Git Lens (módulo de pago que ya no me interesa).
* Git Link (realmente no lo estoy usando).

---
## [v0.7.15] - 2022-11-30
> Revisión
### Añadidos
* Nuevos snippets de uses.
* Configuración para sftp para cuando se trata de un proyecto completo de
  Drupal (también se modifica .gitignore).
* Extensión `Git Config User Profiles`.
* Extensión Git Lens.
* Extensión Yet Another PHPUnit.
* Plantilla para WakaTime.

### Cambios
* Modificación de `launch.json` con mejoras para XDebug en Lando y supresión de
  lanzadores que no uso.
* Eliminación de algunas de las extensiones opcionales.
* Ajustes en archivo `.gitignore_tasks`.
* Mejora y ampliación de la documentación.

### Eliminados
* Tareas y archivos relacionados con standard-version y dependencias npm.
* Extensiones Git History y Git History Diff.

---
## [v0.7.14] - 2022-11-03
> Revisión
### Añadidos
* Configuraciones para npm.
* Extensión Code Runner.

### Cambios
* Ampliación del snippet para "text_format".
* Cambio del módulo "Git Graph" por el módulo "Git History".
* Se cambia el módulo "Drupal 8 Snippets" por "Drupal Smart Snippets".
* Actualización de algunas configuraciones propias para Drupal.

### Eliminados
* Tareas para Docker compose.
* Módulo "Drupal 8 Twig Snippets".

---
## [v0.7.13] - 2022-10-10
> Revisión
### Añadidos
* Extensión "Jenkins Doc"

### Cambios
* Adaptación de configuraciones a la versión 1.71.0 de VSCode.
* Eliminación de configuraciones obsoletas.
* Limpieza de extensiones que ya no uso/recomiendo.

### Corrección de errores
* Error en snippet de librería de formulario.
* Parámetros en funciones de snippets de algunas clases.

---
## [v0.7.12] - 2022-08-26
> Revisión
### Añadidos
* Exclusión de /private_files/ en el gitignore.
* Exclusión de .DS_Store en el gitignore.
* Módulo "Open Folder Context Menus for VS Code".
* Nuevas exclusiones para "Task Manager".
* Extensión "Live Sass Compiler" y configuración básica.
* Módulo "Git Graph".

### Cambios
* Modificación de tareas para añadir comandos específicos para MAC.
* Reemplazo del módulo de SFTP (liximomo) por el fork de Natizyskunk.

### Eliminados
* Se elimina la extensión SVG Viewer porque ha desaparecido del repositorio de
  VSCode.

---
## [v0.7.11] - 2022-07-27
> Revisión
### Añadidos
* Nuevas configuraciones visuales.
* Adaptación de tasks.json a la versión v1.69 de vscode.
* Ejecución de XDebug en LANDO.

---
## [v0.7.10] - 2022-06-17
> Revisión
### Añadidos
* Tareas y Snippets relacionados con mi nueva librería DrupalLog.
* Nuevos Snippet de utilidades.

### Cambios
* Nuevas propiedades en los snippets de formulario para el tipo select
  (ordenación).
* Pequeños ajustes en los snippets de clases y javascript.

### Eliminados
* Extensión recomendada HTML Snippets por incompatibilidad con la nueva versión
  de VSCode.

---
## [v0.7.9] - 2022-06-03
> Revisión
### Añadidos
* Nuevo módulo ***Activitus Bar*** y configuración.
* Nuevas configuraciones para módulos relacionados con la instalación anterior.

### Cambios
* Mejora de visualización de algunas de las tareas.

### Eliminados
* Extensión recomendada Shell Launcher.
* Extensión recomendada PowerShell.
* Extensión ESLint.

---
## [v0.7.8] - 2022-05-19
> Revisión
### Añadidos
* Nueva tarea para descargar archivos de configuración vinculados con los
  paquetes npm.
* Añado al gitignore los archivos generados por el script de enviar-proyecto:
  - archivo .zip
  - archivo *_pass.txt
* Añadidas extensiones "Replace Rules" y "Editor Macros".
* Asociación de los archivos .env.docker como archivos .env.

### Cambios
* Ahora se sincronizan vía sftp.json los manuales generados con phpdox y se
  añaden también a git.

### Corrección de errores
* Snippet para obtener la ruta actual mal formado.
* Snippet para crear FormBase mal formado.
* Snippet para crear WebFormHandlers mal formado.

### Eliminados
* Extensión de macros usada hasta el momento.
* Extensión de mysql porque ahora tiene funciones de pago.

---
## [v0.7.7] - 2022-04-25
> Revisión
### Añadidos
* Nueva extensión recomendada ***CSS Peek***
* Nuevo snippet de formulario ***Entity Autocomplete***.
* Nuevo snippet para obtener el nombre de la ruta actual.
* Nuevos snippets parar generar rutas en fichero .routing.yml
  (***drupal_routing.code-snippets***)

### Cambios
* Ampliación del snippet para crear formularios asignando plantilla por defecto.
* Simplificación del archivo ***sftp.json***.

---
## [v0.7.6] - 2022-04-11
> Revisión
### Añadidos
* Nuevas palabras en ***cspell.json***.
* Nuevos snippets de formulario.
* Nuevos snippets de cláusulas use.
* Nueva tarea para descargar la librería MultiValue.php (elemento de formulario
  que permite generar elementos múltiples).
* Nueva extensión recomendada ***JS & CSS Minifier (Minify)*** y configuración.
* Configuración para que no se sincronice la carpeta ".well-known".
* Nuevo snippet para obtener la url del sitio de Drupal.

### Cambios
* Adaptación del archivo phpmd.xml
* Cambio de plantilla por defecto en phpdox.xml [phpdox-template](https://github.com/oscarnovasf/phpdox-template)

### Corrección de errores
* Configuración para multi-línea del módulo TODO-TREE.
* Error en snippet para generar traits.
* Error tipográfico en task.json

---
## [v0.7.5] - 2022-04-01
> Revisión
### Corrección de errores
* Error en ***tasks.json*** al actualizar.

---
## [v0.7.4] - 2022-03-30
> Revisión
### Añadidos
* Configuración para forzar que la configuración de vscode se abra en formato
  json.
* Snippet para generar Traits.

### Cambios
* Modificación del launch para XDebug en Docker.
* Activar las tareas parar Docker.
* Modificar plantilla .gitignore para los proyectos en los que uso docker.
* Se han movido algunas configuraciones para categorizarlas mejor.

---
## [v0.7.3] - 2022-02-27
> Revisión
### Añadidos
* Configuración específica para archivos XML.
* Nuevas configuraciones para la versión 1.64
* Nueva configuración para Task Manager y ocultar alguna tarea que ya está
  incluida como dependencia de otra.
* Nueva tarea para eliminar archivos *.*e que por alguna razón se generan en
  MAC al descargar alguna de las librerías.
* Añadidos nuevas exclusiones al gitignore (el que se descarga vía tasks.json).
* Añadidas las mismas exclusiones anteriores al archivo ***sftp.json***.

### Cambios
* Redistribución de configuraciones en settings.json.
* Se modifica el ***launch.json*** con mejoras para XDebug sobre Docker.

---
## [v0.7.2] - 2022-02-02
> Revisión
### Añadidos
* Nueva extensión para "ordenar" los archivos SCSS (SCSS Formatter).
* Nueva extensión para lanzar conexiones ssh en la terminal de VSCode.
* Añadido watch en el módulo sftp para los archivos de javascript.
* Asignación de theme para Draw.io.

### Cambios
* Modificación de la extensión de PHP Debug (la anterior ha desaparecido del
  repositorio).
* Pequeñas modificaciones en los comentarios de archivo settings.json para
  facilitar su comprensión.

### Corrección de errores
* Modificación de la ruta al ejecutable de shellcheck para evitar error
  recurrente de que no encuentra dicho ejecutable.
* Modificación de la ruta al ejecutable phpcbf (mismo problema que el anterior)

---
## [v0.7.1] - 2022-01-14
> Revisión
### Añadidos
* Nuevos snippets de utilidades.

### Cambios
* Actualización de configuraciones obsoletas en la versión 1.63.0 de VSCode.
* Configuraciones específicas para MAC.

---
## [v0.7.0] - 2021-11-26
> Revisión
### Añadidos
* Configuraciones nuevas en la versión 1.62 de vscode.
* Configuraciones especiales para archivos CSV.
* Nuevos snippets de formulario.
* Nuevos snippets de utilidades.
* Extensión para scripts en PowerShell (opcional) y configuración.
* Extensión GitLink para crear enlaces al repo (con configuración).
* Extensión Project Manager para optimizar la gestión de proyectos.
* Extensión MySQL y configuración.
* Extensión FIX Json (opcional).

### Cambios
* Mejora del snippet para crear form_base.

### Corrección de errores
* Error en el snippet de formulario: managed_file.

### Eliminados
* Configuración y extension opcional "Live Sass Compiler".

---
## [v0.6.0] - 2021-10-27
> Revisión
### Añadidos
* Nuevo snippet para generar la clase de un formulario de configuración
  (FormConfig).
* Nuevo snippet para generar la clase WebformHandler.
* Nuevos snippets para los formularios.
* Manipulación de la caché del formulario.
* Form API de Checkboxes.
* Nueva librería de snippets de carácter general.

### Cambios
* Se elimina la extensión de Bootstrap 4 por otras más completa.

---
## [v0.5.7] - 2021-10-05
> Revisión
### Añadidos
* Añadidos parámetros a las tareas de las librerías para poder utilizar las
  descargas en proyectos que no son módulos.
* Módulo ESLint y su configuración.

### Cambios
* Modificación del snippet de formulario para las fechas.

---
## [v0.5.6] - 2021-09-15
> Revisión
### Añadidos
* Nuevas palabras para ***cspell.json***
* Extensión para formatear archivos XML.
* Configuración especial para archivos ***yml***.
* Nuevos snippets para cláusulas *use*.
* Código de conducta para contribuyentes al proyecto.
* Tarea para descargar archivo ***.gitignore***.

### Cambios
* Mejora de la documentación.
* Eliminadas extensiones descontinuadas o innecesarias.
* Adaptada configuración para la versión 1.60.0 de VSCode.

### Eliminados
* Extensión Bracket Pair Colorizer 2.

---
## [v0.5.5] - 2021-07-21
> Revisión
### Añadidos
* Configuración especial para ***Code Spell Checker***.
* Tarea para descargar ***cspell.json***.
* Pequeñas modificaciones en ***phpcs.xml***.
* Nuevo módulo "Thunder Client" para test de APIs.
* Nuevos snippets de formulario.

### Cambios
* Más opciones en algunos snippets de formularios.
* Elimino extensión de Composer (me marca error en composer.json).

### Corrección de errores
* Error al ejecutar tareas con dependencias.
* Limpieza de configuraciones obsoletas.

---
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
