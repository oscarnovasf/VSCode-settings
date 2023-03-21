Archivos de configuración para VSCode
===

>Configuración que facilita la programación para Drupal 8 o superior en el
>editor Visual Studio Code.

[![version][version-badge]][changelog]
[![Licencia][license-badge]][license]
[![Código de conducta][conduct-badge]][conduct]
[![wakatime](https://wakatime.com/badge/github/oscarnovasf/VSCode-settings.svg)](https://wakatime.com/badge/github/oscarnovasf/VSCode-settings)
[![Donate][donate-badge]][donate-url]

## Instalación

* ### Requerimientos

  Esta configuración hace uso de una serie de plugins y módulos de uso muy
  recomendado si trabajas con Drupal:

  * [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)
  * [Auto Hide](https://marketplace.visualstudio.com/items?itemName=sirmspencer.vscode-autohide)
  * [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * [BookMarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
  * [Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)
  * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    * [Spanish - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-spanish)
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  * [Commit Message Editor](https://marketplace.visualstudio.com/items?itemName=adam-bender.commit-message-editor)
  * [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
  * [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
  * [Drupal Smart Snippets](https://marketplace.visualstudio.com/items?itemName=andrewdavidblum.drupal-smart-snippets)
  * [Drupal Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=marcostazi.VS-code-drupal)
  * [empty-indent](https://marketplace.visualstudio.com/items?itemName=DmitryDorofeev.empty-indent)
  * [ENV](https://marketplace.visualstudio.com/items?itemName=IronGeek.vscode-env)
  * [getText](https://marketplace.visualstudio.com/items?itemName=mrorz.language-gettext)
  * [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame)
  * [Git Commits](https://marketplace.visualstudio.com/items?itemName=exelord.git-commits)
  * [Git Config User Profiles](https://marketplace.visualstudio.com/items?itemName=onlyutkarsh.git-config-user-profiles)
  * [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
  * [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  * [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  * [jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets)
  * [JS & CSS Minifier (Minify)](https://marketplace.visualstudio.com/items?itemName=olback.es6-css-minify)
  * [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass)
  * [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
  * [Open Folder Context Menus for VS Code](https://marketplace.visualstudio.com/items?itemName=chrisdias.vscode-opennewinstance)
  * [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete)
  * [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug)
  * [PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker)
  * [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)
  * [PHP Mess Detector](https://marketplace.visualstudio.com/items?itemName=ecodes.vscode-phpmd)
  * [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
  * [PHPUnit Test Explorer](https://marketplace.visualstudio.com/items?itemName=recca0120.vscode-phpunit)
  * [phpcbf](https://marketplace.visualstudio.com/items?itemName=persoderlind.vscode-phpcbf)
  * [phpcs](https://marketplace.visualstudio.com/items?itemName=shevaua.phpcs)
  * [platform-settings](https://marketplace.visualstudio.com/items?itemName=runarsf.platform-settings)
  * [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
  * [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
  * [Replace Rules](https://marketplace.visualstudio.com/items?itemName=bhughes339.replacerules)
  * [SCSS Formatter](https://marketplace.visualstudio.com/items?itemName=sibiraj-s.vscode-scss-formatter)
  * [SFTP](https://marketplace.visualstudio.com/items?itemName=liximomo.sftp)
  * [SSH FS](https://marketplace.visualstudio.com/items?itemName=Kelvin.vscode-sshfs)
  * [SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
  * [Task Manager](https://marketplace.visualstudio.com/items?itemName=cnshenj.vscode-task-manager)
  * [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
  * [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * [Twig braces helper](https://marketplace.visualstudio.com/items?itemName=zepich.twig-braces-helper)
  * [Twig Language 2](https://marketplace.visualstudio.com/items?itemName=mblode.twig-language-2)
  * [UNOTES - Markdown Notes WYSIWYG](https://marketplace.visualstudio.com/items?itemName=ryanmcalister.Unotes)
  * [VsCode Editor Macros](https://marketplace.visualstudio.com/items?itemName=jpsnee.vscode-editor-macros)

  También se incluyen estas extensiones opcionales:
  * [Apache Conf](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-apache)
  * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)
  * [Edit CSV](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv)
  * [Fix Json](https://marketplace.visualstudio.com/items?itemName=oliversturm.fix-json)
  * [GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
  * [GitLab Workflow](https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow)
  * [Jenkins Doc](https://marketplace.visualstudio.com/items?itemName=Maarti.jenkins-doc)
  * [Json Editor](https://marketplace.visualstudio.com/items?itemName=nickdemayo.vscode-json-editor)
  * [Lando UI](https://marketplace.visualstudio.com/items?itemName=jixabon.lando-ui)
  * [PHP Server](https://marketplace.visualstudio.com/items?itemName=brapifra.phpserver)
  * [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)
  * [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
  * [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  * [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)
  * [WakaTime](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime)
  * [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)

  ---

  >Para facilitar su instalación se ha incluido un archivo ***extensions.json***
  >dentro de la carpeta .vscode.

  ---

* ### Instalación manual

  * Copiar el directorio ***.vscode*** en la carpeta raíz de tu proyecto.
    > * Una vez copiada deberás cambiar los valores del archivo ***sftp.json***
        para que se conecten con tus servidores.
    > * Sigue las instrucciones que se encuentran en *settings.json*
  * Copiar el archivo ***phpcs.xml*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***phpmd.xml*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***.editorconfig*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***.versionrc*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***phpdox.xml*** en la carpeta raíz de tu proyecto.
    > * Crear una carpeta ***.tmp-doc*** en la raíz de tu proyecto.
  * Copiar el archivo ***package.json*** en la carpeta raíz de tu proyecto.
  * Copiar el archivos ***.gitignore_tasks*** y renombrarlo por ***.gitignore***
    en la raíz de tu proyecto.
    > * Eliminar los comentarios del archivo ***.gitignore*** y añadir lo que
        necesites.
  * Copiar el archivo ***.gitattributes*** en la carpeta raíz de tu proyecto.
  * Si usas la extensión de WakaTime, debes copiar el archivo
    ***wakatime-project_tasks*** y renombrarlo por ***.wakatime-project***,
    luego editarlo y modificar su contenido por el nombre de tu proyecto.

* ### Instalación de PHPCs

  >Para instalar PHPCs puedes seguir las instrucciones [aquí](https://oscarnovas.com/blog/usar-la-guia-de-estilo-de-drupal-con-phpcs-y-visual-code)

* ### Instalación de PHPDOX y PHPMD

  >Para instalar PHPDOX y PHPMD puedes seguir las instrucciones [aquí](https://oscarnovas.com/blog/generando-documentacion-tecnica)

## Autor(es)
- Óscar Novás - [OscarNovas.com][mi-web]

## Créditos
Aquí puedes comprobar la lista de [contribuyentes][contributors]
a este repositorio.

## Histórico de cambios
Aquí puedes comprobar la lista de [cambios][changelog] efectuados hasta el
momento.

---
⌨️ con ❤️ por [Óscar Novás][mi-web] 😊

[mi-web]: https://oscarnovas.com "for developers"

[version]: v0.7.18
[version-badge]: https://img.shields.io/badge/Versión-0.7.18-blue.svg

[license]: LICENSE.md
[license-badge]: https://img.shields.io/badge/Licencia-GPLv3+-green.svg "Leer la licencia"

[conduct]: CODE_OF_CONDUCT.md
[conduct-badge]: https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg "Código de conducta"

[changelog]: CHANGELOG.md "Histórico de cambios"
[contributors]: https://github.com/oscarnovasf/vscode_config/contributors "Ver contribuyentes"

[donate-badge]: https://img.shields.io/badge/Donaci%C3%B3n-PayPal-red.svg
[donate-url]: https://paypal.me/oscarnovasf "Haz una donación"
