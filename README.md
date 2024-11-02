# Shortcut-Commands
Create Shortcut Commands (CLI) on linux

### 1- If you’re using the default shell (Bash), open the .bashrc file. If you’re using Zsh, open the .zshrc file.
```sh
nano ~/.bashrc
```
or 
```sh
nano ~/.zshrc
```
### 2- Add Aliases for Common Artisan Commands Scroll to the bottom of the file, and add your desired shortcuts using the alias command. Here are some examples:
```sh
# Basic Artisan Shortcut
alias art="php artisan"

# Specific Artisan Commands
alias artmigrate="php artisan migrate"
alias arts="php artisan serve"
alias ni="npm install"
alias nrd="npm run dev"
```
### 3- Save and Apply the Changes Save the file and close it. Then, reload the shell configuration:
```sh
source ~/.bashrc
```
or 
```sh
source ~/.zshrc
```
### 4- Restart any terminal, or if you are using IDE or any code editor.

