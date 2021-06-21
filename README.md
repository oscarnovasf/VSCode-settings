Archivos de configuración para VSCode
===

>Configuración que facilita la programación para Drupal 8 o superior en el
>editor Visual Studio Code.

[![version][version-badge]][changelog]
[![Licencia][license-badge]][license]
[![Donate][donate-badge]][donate-url]

## Instalación

* ### Requerimientos

  Esta configuración hace uso de una serie de plugins y módulos de uso muy
  recomendado si trabajas con Drupal:

  * [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  * [BookMarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
  * [Bootstrap v4 Snippets](https://marketplace.visualstudio.com/items?itemName=Zaczero.bootstrap-v4-snippets)
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  * [Commit Message Editor](https://marketplace.visualstudio.com/items?itemName=adam-bender.commit-message-editor)
  * [Composer](https://marketplace.visualstudio.com/items?itemName=ikappas.composer)
  * [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
  * [Drupal 8 Snippets](https://marketplace.visualstudio.com/items?itemName=dssiqueira.drupal-8-snippets)
  * [Drupal 8 Twig Snippets](https://marketplace.visualstudio.com/items?itemName=tsega.drupal-8-twig-snippets)
  * [Drupal Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=marcostazi.VS-code-drupal)
  * [empty-indent](https://marketplace.visualstudio.com/items?itemName=DmitryDorofeev.empty-indent)
  * [ENV](https://marketplace.visualstudio.com/items?itemName=IronGeek.vscode-env)
  * [gettext](https://marketplace.visualstudio.com/items?itemName=mrorz.language-gettext)
  * [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  * [Git History Diff](https://marketplace.visualstudio.com/items?itemName=huizhou.githd)
  * [GitLab Workflow](https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow)
  * [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  * [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)
  * [jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets)
  * [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
  * [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete)
  * [PHP Debug](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-debug)
  * [PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker)
  * [PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)
  * [PHP Mess Detector](https://marketplace.visualstudio.com/items?itemName=ecodes.vscode-phpmd)
  * [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
  * [phpcbf](https://marketplace.visualstudio.com/items?itemName=persoderlind.vscode-phpcbf)
  * [phpcs](https://marketplace.visualstudio.com/items?itemName=shevaua.phpcs)
  * [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
  * [SFTP](https://marketplace.visualstudio.com/items?itemName=liximomo.sftp)
  * [SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
  * [Task Manager](https://marketplace.visualstudio.com/items?itemName=cnshenj.vscode-task-manager)
  * [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * [Twig Language 2](https://marketplace.visualstudio.com/items?itemName=mblode.twig-language-2)

  También se incluyen estas extensiones opcionales:
  * [Apache Conf](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-apache)
  * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)
  * [Edit CSV](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv)
  * [GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
  * [Json Editor](https://marketplace.visualstudio.com/items?itemName=nickdemayo.vscode-json-editor)
  * [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
  * [Macros](https://marketplace.visualstudio.com/items?itemName=geddski.macros)
  * [PHP Server](https://marketplace.visualstudio.com/items?itemName=brapifra.phpserver)
  * [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
  * [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
  * [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  * [Shell launcher](https://marketplace.visualstudio.com/items?itemName=Tyriar.shell-launcher)
  * [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)
  * [WakaTime](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime)

  ---

  >Para facilitar su instalación se ha incluído un archivo ***extensions.json***
  >dentro de la carpeta .vscode.

  ---

* ### Instalación manual

  * Copiar el directorio ***.vscode*** en la carpeta raíz de tu proyecto.
    > * Una vez copiada deberás cambiar los valores del archivo ***sftp.json***
        para que se conecten con tus servidores.
    > * En el *settings.json* deberás cambiar el nombre y correo en el apartado
        de configuración del ***PHP DocBlocks***.
  * Copiar el archivo ***phpcs.xml*** en la carpeta raíz de tu proyecto.
  * Copiar el archivo ***phpmd.xml*** en la carpeta raíz de tu proyecto.
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

[version]: v0.5.3
[version-badge]: https://img.shields.io/badge/version-0.5.3-blue.svg

[license]: LICENSE.md
[license-badge]: https://img.shields.io/github/license/oscarnovasf/vscode_config "Leer la licencia"

[changelog]: CHANGELOG.md "Histórico de cambios"
[contributors]: https://github.com/oscarnovasf/vscode_config/contributors "Ver contribuyentes"

[donate-badge]: https://img.shields.io/badge/Donate-PayPal-green.svg
[donate-url]: https://paypal.me/oscarnovasf "Haz una donación"
