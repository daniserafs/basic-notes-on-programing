### Versionamento de código com Git
    - manter histórico de todas as alterações do código
    - permite trabalhar com mais desenvolvedores no mesmo projeto
    - quem criou o git?

### Usando o Git
    - para conferir se o download deu certo no terminal: git --version 
    - configuração global para nome e e-mail no terminal:
        * git config --global user.name "seu nome"
        * git config --global user.email "seu e-mail"

### Criando um repositório
    - dentro da pasta use o comando no terminal: 
        * git init
    - crie um arquivo na pasta, pode ser um arquivo de texto
    - edite o arquivo
    - adicionando ao git com o comando: 
        * git add nome do arquivo
    - a partir do add o git sabe que esse arquivo deve ser monitorado
    - ao usar no terminal o comando: 
        * git status 
    - é possível ver que o git já reconhece que um novo arquivo foi criado no projeto
    - se você não usar o commando `git add` ele ficará como `untracked files` ou seja o git não o reconhece que deve monitorar mudanças no arquivo
    - é possível adicionar todos os arquivos não monitorados de uma vez só usando o comando no terminal: 
        * git add .
    - para criar um ponto na história use o comando no terminal: 
        * git commit -m "first commit"
    - o parâmetro -m significa a mensagem do ponto na história
    - depois do commit ser realizado a área de estágio fica limpa e pronta para uma nova versão/ponto na história 
    - ao usar o comando no terminal: 
        * git diff
    - é possível ver as alterações que foram feitas em todos os arquivos do projeto, com isso é possível comparar se a nova versão está programada da forma correta
    - o commando no terminal: 
        * git log 
    - dá a possibilidade de ver o histórico de commits do projeto juntamente com as mensagens que outras programadores fizeram para explicar os pontos na história do projeto