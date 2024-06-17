Este projeto ensina como usar o Git.
Os primeiro passos foram:  
- Baixar e instalar o git na máquina
- *  Verificar a versão com o cmd: (git --version). retornou no dia 17/06/24 -> git version 2.45.2.windows.1
- Criar uma pasta para armazenar os projetos.
- Abrir a pasta com o VSCode
- Salvar o arquivo Readme.md. A extensão md(mark down) é linguagem de marcação. é como uma instrução sobre o projeto.
- Abrir o git bash na pasta onde irá ficar os arquivos, no caso MeusProjetos.
- * Dar o comando (git init) para iniciar o repositório vazio. O (master) quer dizer que estamos dentro da branch master.
- Quando damos este comando é criado dentro da nossa pasta de projeto a pasta git. Não apareceu enquanto ainda editava 
- este arquivo. Tudo que acontece para termos o versionamento está nela. Não apagá-la.
- * Comando (git add). Manda os arquivos para área de staging, "uma área perto do palco, pronto para entrar em cena". O
- palco é o commit. Dai colocamos o nome do arquivo que queremos que vá para esta área.
- * (git status) . Mostra o status do que está ocorrendo.
- * (git commit -m "O primeiro commit") -m é permissão para escrever uma mensagem.
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

- * (git branch -M "main" )para mudar o nome que indica a branch master. As empresas usam main.
- Devemos estrar na nossa conta do Github e criar um repositório com o mesmo nome do repositório que se encontra no nosso - computador.
- * (git remote add origin <>)copiamos o link que foi gerado lá no github no Quick Step.
- remote é a conexão que estamos criando entre a máquina local com o github na nuvem origin é o nome que estamo dando    - para o repositório no github e o link dele.
- * (git push -u origin main) . Comando que coloca o nosso arquivo na nuvem.
- Abre uma aba para autenticarmos a conexão. Podemos os usar o Sign in with your browser, colocamos nossas credenciais e - senha e depois clicamos em: Authorise git-ecosystem.
- Como mensagem de que a conexão foi executada com sucesso aparece a seguinte mensagem:
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 1.36 KiB | 464.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Luizbl03/MeusProjetos.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
- Qualquer arquivo Readme.md aparece na página principal do repositório.
- * (clear) - limpa o git bash.
- (git add . ) Este comando coloca todos os arquivo na área de staging.
 
- * (git merge nome da branch)



