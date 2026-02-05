# 🛠️ Fundamentos de Git e GitHub - Rocketseat

Este repositório contém anotações, exercícios e projetos práticos desenvolvidos durante o curso de **Git e GitHub** da [Rocketseat](https://www.rocketseat.com.br/). O objetivo foi dominar o fluxo de trabalho de versionamento de código, desde os conceitos básicos até a integração com repositórios remotos no GitHub.

## 📁 Estrutura do Repositório

O conteúdo está dividido em módulos lógicos para facilitar a consulta:

* **`como-instalar/`**: Guia de instalação e configuração inicial do Git (user.name e user.email).
* **`como-funciona/`**: Entendimento do funcionamento interno do Git (Working Directory, Staging Area e Repository).
* **`comandos-basicos/`**: Exploração dos comandos essenciais para o dia a dia.
* **`iniciando-repositorio/`**: Como transformar uma pasta comum em um repositório git (`git init`).
* **`adicionando-modificacoes-ao-stage-area/`**: Fluxo de preparação de arquivos para o commit (`git add`).
* **`criando-primeiro-commit/`**: Como salvar versões do código com mensagens claras (`git commit`).
* **`alterando-e-commitando/`**: Práticas de modificação contínua e novos registros.
* **`navegando-pelos-commits/`**: Como visualizar o histórico (`git log`) e entender as versões.
* **`recuperando-um-arquivo/`**: Técnicas para desfazer alterações ou recuperar arquivos perdidos.
* **`github/`**: Integração do repositório local com a nuvem, uso de chaves SSH e comandos `push`/`pull`.
* **`cerificado-curso/`**: Registro da conclusão desta etapa de aprendizado.

## 🚀 Comandos Principais Praticados

Durante os estudos, foram exercitados comandos como:

```bash
# Iniciar repositório
git init

# Verificar status dos arquivos
git status

# Adicionar arquivos ao stage
git add .

# Criar um commit
git commit -m "mensagem descritiva"

# Visualizar histórico
git log --oneline

# Conectar ao repositório remoto
git remote add origin <url-do-repositorio>

# Enviar alterações
git push origin main