# .dosfiles
Spinoff of my personal .dotfiles with a little play on words 🤓 See my original [.dotfiles](https://github.com/larrybarker/.dotfiles) for inspiration.

# Setting up Windows

- [ ]  Install chocolatey ([https://chocolatey.org/install](https://chocolatey.org/install))
- [ ]  Install git `choco install git`
- [ ]  Create ssh key ([https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent))
- [ ]  Install composer `choco install composer`
- [ ]  `composer global require hirak/prestissimo` (optional)
- [ ]  Install source tree `choco install sourcetree` (optional)
- [ ]  Install vscode `choco install vscode`
- [ ]  Install laravel `composer global require laravel/installer`
- [ ]  Install mysql workbench `choco install mysql.workbench`
- [ ]  Install Insomia (or other REST client) `choco install insomnia-rest-api-client`

## Development Environment

We have two options for setting up our development environment on Windows. Option A is to install Laravel Homestead, and the prerequisite requirements for it (Virtualbox & Vagrant). This option has traditionally been used to provide quick setup without needing to install additional dependencies on your machine.

Option B is to use Laragon, which is similar to XAMPP. This option is relatively new and has not been tested by our team yet. Choosing this option is fine, just know that some of the process and results are unknown to us. 

### Option A - Laravel Homestead

- [ ]  Install virtual box `choco install virtualbox`
- [ ]  Install vagrant `choco install vagrant`
- [ ]  Install homestead ([https://laravel.com/docs/6.x/homestead](https://laravel.com/docs/6.x/homestead))

### Option B - Laragon

- [ ]  Install Laragon `choco install laragon`

# VS Code Extensions

- DotENV
- Laravel intellisense
- PHP Debug
- PHP DocBlocker
- PHP Intelephense
- PHP Intellisense
