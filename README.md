# 42-Urduliz---Cosillas:

#Para liberar espacio del usuario:

https://42born2code.slack.com/archives/C021XRWD76K/p1625555113026200 - sitio con información en el slack

rm -r ~/Library/Caches/* | rm ~/.zcompdump* | brew cleanup

#Para instalar valgrind:

  1- Instalar brew:

    rm -rf $HOME/.brew && git clone --depth=1 https://github.com/Homebrew/brew $HOME/.brew && echo 'export PATH=$HOME/.brew/bin:$PATH' >> $HOME/.zshrc && source    $HOME/.zshrc && brew update
    
  2- Modificar el goinfree para instalar el valgrind:

    Ir a la siguiente url: 
    
    https://github.com/docgloucester/42homebrew_sgoinfre
    
    Copiar en la terminal: 
    
    curl -fsSL https://raw.githubusercontent.com/docgloucester/42homebrew_sgoinfre/master/install.sh | zsh
    
  3- Instalar el valgrind con los siguientes comandos:
    
    brew tap LouisBrunner/valgrind
    
    brew install --HEAD LouisBrunner/valgrind/valgrind
    
#Cosillas del vim:

  *Para abrir pestañas nuevas: :-tabnew "nombre del archivo"
  
  *Para substitur:(rango de filas) + s + / + (codigo a subsituir) + / + (codigo nuevo) + / + g(para que busque mas en una linea) c(para confirmar cambio)
    Por ejemplo: :13,35 s/i/j/gc
