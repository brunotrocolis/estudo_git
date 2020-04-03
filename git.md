# GIT

## Configurações inciais
 
 `` git config --global user.name "<nome do usuário>"``

 Para configurar o nome do usuário

`` git config --global user.email "<email do usuário>"``

Para configurar o e-mail do usuário

`` git config --global core.editor <editor>``

Configurar editor padrão

## Inicializar repositório

`` git init ``

Inicializa repositório

## Ciclo de vida e estados dos arquivos

`` git add ``

Move os arquivos do `UNTRACKED` ou `MODIFIED` para o `STAGED`

`` git commit -m "<Mensagem do commit>" ``

Commitar arquivos

![Imagen 01](./img01.png)

## Visualizar

`` git status ``

Visualizar estado dos arquivos

`` git log ``

Mostra os dados dos commits

`` git log --graph ``

Mostra o historico dos commits em forma de arvore

`` git diff ``

Mostra as mudanças nos arquivos

## Desfazer as coisa

`` git restore --staged "<nome do arquivo>" ``

ou

`` git reset HEAD "<nome do arquivo>" ``

Remove arquivo do `STAGED` para o `MODIFIED`

`` git checkout "<nome do arquivo>" ``

Descarta versão no `MODIFIED` para a última no `STAGED` ou no `UNMODIFIED`  