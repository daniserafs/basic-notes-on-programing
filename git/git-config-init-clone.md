### 

    - Existem 3 etapas no git
        * Workspace: código que estamos trabalhando
        * Local Repository: após finalizado que está sendo codado a pessoa faz o commit e envia pro repositório local, na sua máquina!
        * Remote Repository: repositório na nuvem que pode ser consultado por todos da equipe

### Como começar um projeto novo 
    - git init: a partir dele vc já está intregado ao git
    - git clone: já existe um repositório pronto, ele já dá o git init automaticante e também mapeia o deretório remoto

### Git advanced
    - git config --list: configurações do git
    - existem 3 níveis de configuração:
        * sistema: engloba usuários e projetos 
            --> `git config --system --edit` melhor não mexer nesse arquivo
        * usuário: engloba todos os projetos que aquele usuário mexe 
            --> `git config --global --edit` : o default abre o editor do vim se quiser mudar de edtor: `git config --global core.editor code` vai mudar para o Visual Studio Code
        * projeto: engloba apenas aquele projeto
            --> `git config --edit` ou `git config --local --edit`: abre as configurações do arquivo local do projeto 