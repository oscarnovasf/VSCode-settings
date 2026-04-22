Archivos de configuración para VSCode
===

>Configuración que facilita la programación para Drupal 8 o superior en el
>editor Visual Studio Code.

[![version][version-badge]][changelog]
[![Licencia][license-badge]][license]
[![Código de conducta][conduct-badge]][conduct]
[![wakatime](https://wakatime.com/badge/github/oscarnovasf/VSCode-settings.svg)](https://wakatime.com/badge/github/oscarnovasf/VSCode-settings)

[![Donate][donate-badge]][donate-url] <img src="https://img.shields.io/liberapay/patrons/ONovasDev.svg?logo=liberapay">

## Instalación

* ### Requerimientos

  Esta configuración hace uso de una serie de plugins y módulos de uso muy
  recomendado si trabajas con Drupal:

  * [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)
  * [Ansible Vault (No Python)](https://marketplace.visualstudio.com/items?itemName=ipierre1.ansible-vault-vscode)
  * [Auto Hide](https://marketplace.visualstudio.com/items?itemName=sirmspencer.vscode-autohide)
  * [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
  * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    * [Spanish - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-spanish)
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  * [Composer](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.composer-php-vscode)
  * [Drupal Smart Snippets](https://marketplace.visualstudio.com/items?itemName=andrewdavidblum.drupal-smart-snippets)
  * [Drupal Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=marcostazi.VS-code-drupal)
  * [empty-indent](https://marketplace.visualstudio.com/items?itemName=DmitryDorofeev.empty-indent)
  * [ENV](https://marketplace.visualstudio.com/items?itemName=IronGeek.vscode-env)
  * [Env mask](https://marketplace.visualstudio.com/items?itemName=RohitKuinkel.env-mask)
  * [getText](https://marketplace.visualstudio.com/items?itemName=mrorz.language-gettext)
  * [Git Commits](https://marketplace.visualstudio.com/items?itemName=exelord.git-commits)
  * [Git Config User Profiles](https://marketplace.visualstudio.com/items?itemName=onlyutkarsh.git-config-user-profiles)
  * [Git Graph v3](https://marketplace.visualstudio.com/items/?itemName=Gxl.git-graph-3)
  * [Gitflow Actions Sidebar](https://marketplace.visualstudio.com/items?itemName=ardisaurus.gitflow-actions-sidebar)
  * [GitHub Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)
  * [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  * [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  * [jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets)
  * [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass)
  * [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * [Markdown Checkboxes](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-checkbox)
  * [Markdown Execute](https://marketplace.visualstudio.com/items?itemName=hanskre.markdown-execute)
  * [Markdown Footnotes](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-footnotes)
  * [Markdown GitHub Alerts](https://marketplace.visualstudio.com/items?itemName=saeris.markdown-github-alerts)
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete)
  * [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug)
  * [PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker)
  * [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)
  * [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
  * [PHPUnit Test Explorer](https://marketplace.visualstudio.com/items?itemName=recca0120.vscode-phpunit)
  * [phpcs](https://marketplace.visualstudio.com/items?itemName=shevaua.phpcs)
  * [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
  * [px to rem & rpx & vw (cssrem)](https://marketplace.visualstudio.com/items?itemName=cipchk.cssrem)
  * [REST Client Api](https://marketplace.visualstudio.com/items?itemName=donebd.rest-client-api)
  * [Run Terminal Command](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.terminal-commands)
  * [SCSS Formatter](https://marketplace.visualstudio.com/items?itemName=sibiraj-s.vscode-scss-formatter)
  * [SFTP](https://marketplace.visualstudio.com/items?itemName=liximomo.sftp)
  * [Smart Clicks](https://marketplace.visualstudio.com/items?itemName=antfu.smart-clicks)
  * [SSH FS](https://marketplace.visualstudio.com/items?itemName=Kelvin.vscode-sshfs)
  * [SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
  * [Task Manager](https://marketplace.visualstudio.com/items?itemName=cnshenj.vscode-task-manager)
  * [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * [Twig braces helper](https://marketplace.visualstudio.com/items?itemName=zepich.twig-braces-helper)
  * [Twig Language 2](https://marketplace.visualstudio.com/items?itemName=mblode.twig-language-2)

  También se incluyen estas extensiones opcionales:
  * [Claude Code for VS Code](https://marketplace.visualstudio.com/items?itemName=anthropic.claude-code)
  * [Copilot Theme](https://marketplace.visualstudio.com/items?itemName=BenjaminBenais.copilot-theme)
  * [Container Tools](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-containers)
  * [DDEV Manager](https://marketplace.visualstudio.com/items?itemName=biati.ddev-manager)
  * [DDEV PHPMD](https://marketplace.visualstudio.com/items?itemName=OpenForgeProject.vscode-ddev-phpmd)
  * [Fix Json](https://marketplace.visualstudio.com/items?itemName=oliversturm.fix-json)
  * [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
  * [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
  * [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)
  * [Translate with DeepL](https://marketplace.visualstudio.com/items?itemName=soerenuhrbach.vscode-deepl)
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
  * Copiar el archivo ***grumphp.yml*** en la carpeta raíz de tu proyecto.
  * Copiar el archivos ***.gitignore_tasks*** y renombrarlo por ***.gitignore***
    en la raíz de tu proyecto.
    > * Eliminar los comentarios del archivo ***.gitignore*** y añadir lo que
        necesites.
  * Copiar el archivo ***.gitattributes*** en la carpeta raíz de tu proyecto.
  * Si usas la extensión de WakaTime, debes copiar el archivo
    ***wakatime-project_tasks*** y renombrarlo por ***.wakatime-project***,
    luego editarlo y modificar su contenido por el nombre de tu proyecto.

* ### Instalación automática

Todos estos archivos se incorporan a las diferentes instalaciones generadas con
el script [iniciar-proyecto](https://github.com/oscarnovasf/iniciar-proyecto).

* ### Instalación de PHPCs

  >Para instalar PHPCs puedes seguir las instrucciones [aquí](https://oscarnovas.com/blog/usar-la-guia-de-estilo-de-drupal-con-phpcs-y-visual-code)

* ### Instalación de PHPMD

  >Para instalar PHPMD puedes seguir las instrucciones [aquí](https://oscarnovas.com/blog/generando-documentacion-tecnica)

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

[version]: v0.9.1
[version-badge]: https://img.shields.io/badge/Versión-0.9.1-blue.svg

[license]: LICENSE.md
[license-badge]: https://img.shields.io/badge/Licencia-GPLv3+-green.svg "Leer la licencia"

[conduct]: CODE_OF_CONDUCT.md
[conduct-badge]: https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg "Código de conducta"

[changelog]: CHANGELOG.md "Histórico de cambios"
[contributors]: https://github.com/oscarnovasf/vscode_config/contributors "Ver contribuyentes"

[donate-badge]: https://img.shields.io/badge/Donaci%C3%B3n-PayPal-red.svg
[donate-url]: https://paypal.me/oscarnovasf "Haz una donación"
