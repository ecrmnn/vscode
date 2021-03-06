# vscode
My personal VS Code setup

## Extensions
#### General
- Atom One Dark Theme `akamud.vscode-theme-onedark`
- Case-Sensitive Add Next Occurence `jacobkantzer.case-sensitive-add-next`
- DotENV `mikestead.dotenv`
- TOML `be5invis.toml`
- Global Config `gruntfuggly.global-config`
  - See [apply global config](#apply-global-config)

#### JavaScript
- ES Lint `dbaeumer.vscode-eslint`
- Vetur `octref.vetur`

#### PHP
- PHP Intelephense `bmewburn.vscode-intelephense-client`
- PHP Namespace Resolver `mehedidracula.php-namespace-resolver`
- Laravel Blade Snippets `onecentlin.laravel-blade`
- phpcs `ikappas.phpcs`
  - Remember to add `"phpcs.standard": "PSR2"` in `settings.json`

## Apply global config
Make your tasks global by copying and pasting `tasks.json` in `~/.vscode`.
If you use my `settings.json` file you can symlink your global tasks to any project by clicking `shift + cmd + p` and triggering `Copy Global Config`

## CLI
#### PHP
- [php-cs-fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
