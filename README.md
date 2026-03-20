# Meu projeto
Este é meu primeiro projeto usando Git e GitHub!

# Sobre o Projeto
Aplicando meus conhecimentos de comandos Git, com comandos Básicos de aplicação!

# Ferramentas utilizadas
 - Linux
 - Git
 - GitHub
# Comando Utilizados

Utilizei cada um dos comandos abaixo para iniciar esse projeto.

1. Atualização de lista pacotes
   sudo apt update

2. Instalação do Git
   sudo apt install git

3. Verificar instação
   git --version

4. Configurando o usuário
   git config --global user.name "Rayane Santana"
   git config --global user.email "rayane.santana_@hotmail.com"

5. Criando o repositório

   mkdir meu-repo

6. Iniciando o git
   criando o repotório local
   git init

7. Criando um arquivo
   touch README.md

6. Editando o arquivo
   vim README.md

7. Adicionando o conteúdo pelo editor
   ##Meu primeiro projeto...

8. Adicionando o arquivo
   git add README.md
   
10. Adicionando o primeiro commit
    git commit -m "Primeiro commit"

11. Verificando o status
    git status

12. Verifcando Histórico
    git log 

13. Adicionei uma nova Branch
    git checkout -b nova-branch

14. Repositório Remoto do GitHub
    git remote add origin https://github.com/SantRhay/Projeto-Git

15. Resolvendo confitos de merge
    git merge nova-branch
    ## conflito detectado
    ## resolução manual no VS Code (Accept both Changes)
    git add .
    git commit -m "Resolvendo conflito de merge"
    git push

16. Teste de reset
    ##teste de linha
    git restore README.md
   

17. Test de reset
    Outra linha de teste