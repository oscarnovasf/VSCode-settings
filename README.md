Archivos de configuración para VSCode
===

>Configuración que facilita la programación para Drupal 8 o superior en el
>editor Visual Studio Code.

[![version][version-badge]][changelog]
[![Licencia][license-badge]][license]
[![Código de conducta][conduct-badge]][conduct]
[![Donate][donate-badge]][donate-url]

## Instalación

* ### Requerimientos

  Esta configuración hace uso de una serie de plugins y módulos de uso muy
  recomendado si trabajas con Drupal:

  * [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  * [BookMarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
  * [Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)
  * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    * [Spanish - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-spanish)
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  * [Commit Message Editor](https://marketplace.visualstudio.com/items?itemName=adam-bender.commit-message-editor)
  * [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
  * [Drupal 8 Snippets](https://marketplace.visualstudio.com/items?itemName=dssiqueira.drupal-8-snippets)
  * [Drupal 8 Twig Snippets](https://marketplace.visualstudio.com/items?itemName=tsega.drupal-8-twig-snippets)
  * [Drupal Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=marcostazi.VS-code-drupal)
  * [empty-indent](https://marketplace.visualstudio.com/items?itemName=DmitryDorofeev.empty-indent)
  * [ENV](https://marketplace.visualstudio.com/items?itemName=IronGeek.vscode-env)
  * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * [getText](https://marketplace.visualstudio.com/items?itemName=mrorz.language-gettext)
  * [Git History Diff](https://marketplace.visualstudio.com/items?itemName=huizhou.githd)
  * [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  * [GitLink](https://marketplace.visualstudio.com/items?itemName=qezhu.gitlink)
  * [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  * [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)
  * [jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets)
  * [JS & CSS Minifier (Minify)](https://marketplace.visualstudio.com/items?itemName=olback.es6-css-minify)
  * [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
  * [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete)
  * [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug)
  * [PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker)
  * [PHP Mess Detector](https://marketplace.visualstudio.com/items?itemName=ecodes.vscode-phpmd)
  * [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
  * [phpcbf](https://marketplace.visualstudio.com/items?itemName=persoderlind.vscode-phpcbf)
  * [phpcs](https://marketplace.visualstudio.com/items?itemName=shevaua.phpcs)
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
  * [Twig Language 2](https://marketplace.visualstudio.com/items?itemName=mblode.twig-language-2)
  * [VsCode Editor Macros](https://marketplace.visualstudio.com/items?itemName=jpsnee.vscode-editor-macros)

  También se incluyen estas extensiones opcionales:
  * [Apache Conf](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-apache)
  * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)
  * [Edit CSV](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv)
  * [Fix Json](https://marketplace.visualstudio.com/items?itemName=oliversturm.fix-json)
  * [GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
  * [GitLab Workflow](https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow)
  * [Json Editor](https://marketplace.visualstudio.com/items?itemName=nickdemayo.vscode-json-editor)
  * [PHP Server](https://marketplace.visualstudio.com/items?itemName=brapifra.phpserver)
  * [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
  * [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)
  * [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
  * [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  * [Shell launcher](https://marketplace.visualstudio.com/items?itemName=Tyriar.shell-launcher)
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
    > * En el *settings.json* deberás cambiar el nombre y correo en el apartado
        de configuración del ***PHP DocBlocks***.
    > * Sigue las instrucciones que se encuentran en *settings.json*
  * Copiar el archivo ***phpcs.xml*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***phpmd.xml*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***.editorconfig*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***.versionrc*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***phpdox.xml*** en la carpeta raíz de tu proyecto.
    > * Crear una carpeta ***.tmp-doc*** en la raíz de tu proyecto.
  * Copiar el archivo ***package.json*** en la carpeta raíz de tu proyecto.
  * Copiar los archivos ***.gitignore*** y ***.gitattributes*** en la carpeta
    raíz de tu proyecto.
    > * Eliminar los comentarios del archivo ***.gitignore*** y añadir lo que
        necesites.

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

[version]: v0.7.8
[version-badge]: https://img.shields.io/badge/Versión-0.7.8-blue.svg

[license]: LICENSE.md
[license-badge]: https://img.shields.io/badge/Licencia-GPLv3+-green.svg "Leer la licencia"

[conduct]: CODE_OF_CONDUCT.md
[conduct-badge]: https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg "Código de conducta"

[changelog]: CHANGELOG.md "Histórico de cambios"
[contributors]: https://github.com/oscarnovasf/vscode_config/contributors "Ver contribuyentes"

[donate-badge]: https://img.shields.io/badge/Donaci%C3%B3n-PayPal-red.svg
[donate-url]: https://paypal.me/oscarnovasf "Haz una donación"
