Este projeto ensina como usar o Git.
Os primeiro passos foram:  
- Baixar e instalar o git na máquina
- *  Verificar a versão com o cmd: git --version. retornou no dia 17/06/24 -> git version 2.45.2.windows.1
- Criar uma pasta para armazenar os projetos.
- Abrir a pasta com o VSCode
- Salvar o arquivo Readme.md. A extensão md(mark down) é linguagem de marcação. é como uma instrução sobre o projeto.
- Abrir o git bash na pasta onde irá ficar os arquivos, no caso MeusProjetos.
- * Dar o comando git init para iniciar o repositório vazio. O (master) quer dizer que estamos dentro da branch master.
- Quando damos este comando é criado dentro da nossa pasta de projeto a pasta git. Não apareceu enquanto ainda editava 
- este arquivo. Tudo que acontece para termos o versionamento está nela. Não apagá-la.
- * Comando git add. Manda os arquivos para área de staging, "uma área perto do palco, pronto para entrar em cena". O
- palco é o commit. Dai colocamos o nome do arquivo que queremos que vá para esta área.
- * git status . Mostra o status do que está ocorrendo.
- * git commit -m "O primeiro commit" -m é permissão para escrever uma mensagem.
- Deu um erro:
   Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'llima@LimaSlave.(none)')
- 7:34
- Para resolver o problema abri o "Open Git GUI here" -> Edit -> Option e inseri o meu nome e email nos MeusProjetos Repository e no Global(all Repository).





