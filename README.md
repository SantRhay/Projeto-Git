# Projeto Git - Controle de Versionamento
Este é meu primeiro projeto usando Git e GitHub!

# Sobre o Projeto
Aplicando meus conhecimentos de comandos Git, com comandos Básicos de aplicação, com inclusão de fluxo de branches, resoluções de conclitos, merge e rebase!

# Ferramentas utilizadas
  - Linux
  - Git
  - GitHub

# Comando Aplicados
  - Instalação do Git
  - Inicialização de repositório
  - Controle de versão com Git
  - Criação e gerenciamento de Branches (feature, fix)
  - Merge e resolição de conflitos
  - Rebase
  - Commits 
  - Uso do GitHub (push, pull request)

# Fluxo inicial do projeto

```bash
    git init

    Criando um arquivo
    touch README.md

    Editando o arquivo
    vim README.md

    Adicionando o conteúdo pelo editor
    ##Meu primeiro projeto...

    Adicionando o arquivo
    git add README.md
   
    Adicionando o primeiro commit
    git commit -m "Primeiro commit"

    Verificando o status
    git status

    Verifcando Histórico
    git log 

    Adicionei uma nova Branch
    git checkout -b nova-branch

    Repositório Remoto do GitHub
    git remote add origin https://github.com/SantRhay/Projeto-Git

    Resolvendo confitos de merge
    git merge nova-branch
    ## conflito detectado
    ## resolução manual no VS Code (Accept both Changes)
    git add .
    git commit -m "Resolvendo conflito de merge"
    git push

    Teste de reset
    ##teste de linha
    #Cancelando antes do commit
    git restore README.md
   
    Test de reset
    ## Outra linha de teste
    ## Criando commit -m "teste reset"
    git add .
    git commit -m "Teste de reset"
    ## Voltando o commit
    git reset --hard HEAD~1

    # Criando Gitignore
    touch .gitignore
     ## Adicionei o conteúdo (base padrão)
    git add .gitignore
    git commit -m "Adicionando .gitignore"
    git push

# Criando uma nova branch
  git checkout -b feature/login
  git checkout -b fix/README
  git add README.md
  git commit -m "Adicionando login"
  git push

# Correção de Bug
  criando uma nova branch
  git checkout -b fix/README
<<<<<<< HEAD

  Linha Criada na Main = teste-conflito
  git add .
  git coomit -m "Feat alteração na main"
=======
  git add README.md
  git commit -m "corrigindo erro no README"
  git push

# Simulação de conflito em merge
  criando a branch
  git checkout -b conflito-teste
  git add README.md
  git commit -m "alteração na branch conflito-teste"
  git push

   Correção do conflito de merge
   git commit -m "feat: corrigindo o conflito de merge"
   git merge conflito-teste
   git push

#  Criando um Rebase básico
   criando a branch
   git checkout -b feature/rebase-teste
   git add README.md
   git commit -m "feat: teste rebase 1"
   git push

