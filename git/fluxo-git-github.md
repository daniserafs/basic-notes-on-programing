### Pensamentos iniciais com Git

  - git init: começa a controlar o projeto na pasta 
  - master: é a ramificação principal do projeto
  - git status: mostra se arquivos no projeto estão sendo versionados
  - git add 'nome do arquivo': arquivo será rastreado para ir pro ponto da história após git commit -m "alteração do código"
  - git log: mostra pontos na história já criados
  - git diff: verifica as alterações feitas nos arquivos `-` indica remoção de código `+` adição de código
  - git add *.html : adiciona todos arquivos em formato html
  - git add 'nome da pasta'/* : todos os arquivos na pasta 
  - git add . : adiciona todos os arquivos independente de onde eles estão
  - .gitignore: é um arquivo que contém os caminhos de arquivos que não queremos que sejam rastreados
  - git checkout: pula para um ponto na história, o ponto será o código do commmit que vc consegue com git log
  
  ### Pensando em ramificações do projeto
  
  - em projetos com mais de uma pessoa, o git vai trabalhar com branchs
  - git branch: lista as branchs, se existir alguma fora da master aparecerão os nomes delas, se tiver somente master só aparece ela
  - git branch feature/nomequalquer: cria o ramo com o nome dele
  - git checkout feature/nomequalquer: acessa a branch que você deseja 
  - master nao tem acesso aos commits e arquivos na outra branch
  - git merge feature/nomequalquer: integra as alterações da outra branch com a master
  - git branch -D feature/nomequalquer: deleta a branch criada 
  
  ### Uso de Github
  
  - dentro do seu usuario é possivel criar repositorios
  - com a url do repositorio
  - git remote add origin url-do-repositorio.git: adiciona um ponto remoto
  - git remote -v: lista as urls
  - git push origin master: o que está na master para o repositorio remoto
  - git clone url-do-repositorio.git: faz os download dos arquivos que estão no Github
  - git pull origin master: faz download das informações que foram alteradas no Github
