# STATUS
1. Forma Normal
git status
  
3. Forma Abreviada de ver el Status
git status --short

# LOG
1. Foma Normal
git log

2. Forma Corta
git log --oneline

# Creación de Alias
1. s = al nombre del alias que le asignaras al comando
2. Lo que esta entre "" es el comando a ejecutar con el alias
3. Alias de Status
  git config --global alias.s "status --short"
4. Alias de Log
  git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

# Editar Configuración de Alias
1. Ingresar a Configuracion para Edicion
   git config --global -e
2. Guardar la configuracion se presiona la tecla ESC + : + w + q + !
