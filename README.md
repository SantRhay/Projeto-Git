![Last Commit](https://img.shields.io/github/last-commit/SantRhay/Projeto-Git)
![Languages](https://img.shields.io/github/languages/count/SantRhay/Projeto-Git)
![Repo Size](https://img.shields.io/github/repo-size/SantRhay/Projeto-Git)

# 🚀 Projeto Git - Controle de Versionamento

> 🚀 Projeto prático focado em simular cenários reais de versionamento utilizando Git e GitHub.

![Git](https://img.shields.io/badge/Git-Controle_de_Versão-orange)
![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Linux](https://img.shields.io/badge/Linux-terminal-blue)
![CI](https://github.com/SantRhay/Projeto-Git/actions/workflows/ci.yml/badge.svg)


## 📌 Navegação

- [📌 Sobre o projeto](#-sobre-o-projeto)
- [🛠️ Ferramentas](#️-ferramentas-utilizadas)
- [⚙️ Comandos](#️-comandos-utilizados)
- [🔄 Pipeline CI/CD](#-pipeline-cicd)
- [💡 Prática](#-o-que-foi-praticado)
- [📚 Aprendizados](#-aprendizados)
- [📌 Conclusão](#-conclusão)

---

## 📌  Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de aplicar conceitos fundamentais de Git e controle de versionamento, utilizando comandos essenciais e simulando situações reais do dia a dias de desenvolvimento.

Foram abordadas práticas como criação de branches,  resolução de conflitos, versionamento de código e manipulação de histórico.)

---

## 🛠️ Ferramentas utilizadas
 
- 🐧 Linux (ambiente de desenvolvimento)
- 🌿 Git (controle de versão)
- 💻 GitHub (repositório remoto)
- ⚙️ GitHub Actions (CI/CD)

---

## ⚙️ Comando Utilizados

### 👤 Configurando o usuário  
Definição  das credenciais globais do Git
   
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu-email@exemplo.com"
```

---

### 📁 Criando o repositório
Criação de um novo repositório local

```bash
mkdir meu-repo
git init
```
### 📄 Criando do arquivo README
Criação do arquivo principal do projeto

```bash 
touch README.md
```

### ✏️ Editando o arquivo

```bash
vim README.md
``` 

### ➕ Adicionando ao stage
![Banner DevOps](https://img.shields.io/badge/Projeto-Git%20Versionamento-blue?style=for-the-badge)

```bash
git add README.md
```
---

```md
### 💾 Adicionando o primeiro commit

```bash
git commit -m "feat: Inicialização do projeto Git com README estruturado"
```
---

### 📊 Verificando o status

```bash
git status
``` 
---

### 📜 Verifcando Histórico

```bash
git log 
```

---

## 🌿 Criando uma nova Branch

Criei uma nova branch para desenvolver uma feature isolada do código principal.

```bash
git checkout -b nova-branch
```
---

# 🔗 Repositório Remoto do GitHub

```bash
git remote add origin https://github.com/SantRhay/Projeto-Git
git branch -M main
git push -u origin main
``` 
---

# ⚠️ Resolvendo confitos de merge

```bash
git merge nova-branch
```
---

# 🔄 Teste de reset

```bash
git restore README.md
git reset --hard HEAD~1
``` 
---

# 📦 Configurando .gitignore

```bash
touch .gitignore
git add .gitignore
git push -u origin main
```
---

```md id="d2k91x"

## 🚀 Comandos utilizados

```

### 🌿  Criando uma nova branch
Criação de uma branch para desenvolvimento isolado

```bash
git checkout -b feature/login
```

### 🔀 Merge
Integração de alterações entre branches

```bash
git merge nova-branch
```

### 🔄 Rebase básico
Reorganização do histórico de commits

```bash
git checkout -b feature/rebase-teste
git rebase main 
```

---

### 🐛 Correção de Bug

Criando uma nova branch:  

```bash
git checkout -b fix:README
```
---

### ⚠️ Simulação de conflito em merge

Criando a branch:
  
```bash
git checkout -b conflito-teste
```
---

### 🌿 Criando um Rebase básico

Criando a branch:

```bash
git checkout -b feature/rebase-teste
``` 

---

```md

---

## 🔄 Pipeline CI/CD

Este projeto utiliza GitHub Actions para automação de integração contínua.

### ✔️ O pipeline executa:

- Validação automática do projeto
- Simulação de testes
- Verificação de arquivos essenciais
- Execução a cada push na branch main

📌 Resultado:
- Feedback imediato
- Garantia de qualidade
- Simulação de ambiente DevOps real

### 📸 Execução do Pipeline
![Pipeline](./assets/pipeline.png)

---

# 💡 Práticas Aplicadas:
- 🌿 Criação de branches
- ⚠️ Resolução de conflitos
- 🔄 Versionamento de código
- ♻️ Teste com reset e rebase
 
## 🧠 Aprendizados Técnicos

- Uso de branches para isolar funcionalidades
- Resolução de conflitos de merde na prática
- Controle de histórico com git (reset e restore)
- Integração com repositório remoto (GitHub)
```

---

## 📌 Conclusão

Este projeto foi essencial para consolidar meus conhecimentos em Git e controle de versionamento, permitindo aplicar na prática conceitos como criação de branches, resolução de conflitos e gerenciamento de histórico;

Simulei cenários reais de desenvolvimento, aplicando práticas utilizadas no mercado e fortalecendo minha base em versionamento e CI/CD

---

## 📊 Resultados

- Pipeline CI/CD funcional com GitHub Actions
- Automatização de validações a cada push
- Simulação de fluxo real de desenvoltimento
- Aplicação de boas práticas de versionamento

## 👤 Autora

Feito por **Rayane Santana**
💻 Em transição para área de tecnologia / DevOps