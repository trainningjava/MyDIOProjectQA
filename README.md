# 🧪 MyDIOProjectQA

Projeto desenvolvido durante os estudos de Quality Assurance (QA), com foco em testes manuais funcionais, documentação de requisitos, criação de User Stories, elaboração de Mind Maps, casos de teste e cenários BDD.

## 🎓 Formação e Contexto do Projeto

Este repositório foi desenvolvido durante minha participação no bootcamp Almaviva Solutions - Back-end com Java & QA, promovido pela DIO (Digital Innovation One).

## 🎯 Objetivo

Aplicar conceitos de QA no contexto ágil, simulando atividades executadas por Analistas de Teste em projetos reais.

O projeto contempla:

* Levantamento de requisitos
* User Stories
* Critérios de Aceitação
* Regras de Negócio
* Mind Maps
* Casos de Teste Manuais
* Cenários BDD
* Gestão de Defeitos

---

## 📂 Estrutura do Projeto

```text
📦 MyDIOProjectQA
 ┣ 📄 Cadastro usuario.png
 ┣ 📄 README.md
 ┣ 📄 Casos de teste.pdf
 ┗ 📄 User story.pdf
```
---

Os artefatos de teste presentes neste repositório foram elaborados utilizando a aplicação SauceDemo como ambiente de prática para testes manuais.

### Ambiente de Testes

* Aplicação: SauceDemo
* URL: https://www.saucedemo.com/
* Tipo: Aplicação web para prática de testes
* Objetivo: Simular cenários reais de autenticação, navegação, carrinho de compras e checkout.

### Credenciais Disponíveis

Usuário padrão:

```text
standard_user
secret_sauce
```

Outros usuários disponíveis no ambiente:

* standard_user
* locked_out_user
* problem_user
* performance_glitch_user
* error_user
* visual_user

### Funcionalidades Exploradas

* Login de usuário
* Validação de credenciais
* Listagem de produtos
* Carrinho de compras
* Checkout
* Fluxo completo de compra

### Referência

Site oficial do ambiente de testes:

[SauceDemo](https://www.saucedemo.com/?utm_source=chatgpt.com)


---

## 📖 User Story

### Cadastro de Usuário

Como um usuário visitante

Quero realizar meu cadastro na plataforma

Para acessar funcionalidades exclusivas do sistema.

### Regras de Negócio

* Nome obrigatório
* E-mail obrigatório e válido
* Senha obrigatória
* Senha entre 8 e 14 caracteres
* Caracteres especiais permitidos: $, # e @

---

## 🧠 Mind Map

O projeto possui um mapa mental para auxiliar na identificação dos cenários de teste do processo de cadastro de usuário.

Principais validações:

* Nome válido e inválido
* E-mail válido e inválido
* Senha válida e inválida
* Mensagens de sucesso e erro

---

## ✅ Casos de Teste

### Cadastro com Sucesso

**Pré-condição**
Usuário na tela de cadastro.

**Passos**

1. Informar nome válido.
2. Informar e-mail válido.
3. Informar senha válida.
4. Clicar em "Cadastrar".

**Resultado Esperado**
Cadastro realizado com sucesso.

---

### Cadastro com E-mail Inválido

**Resultado Esperado**
Exibir mensagem de erro para o e-mail informado.

---

## 🥒 BDD

```gherkin
Funcionalidade: Cadastro de Usuário

Cenário: Cadastro realizado com sucesso
Dado que o usuário está na tela de cadastro
Quando informar dados válidos
E clicar em "Cadastrar"
Então o sistema deve realizar o cadastro com sucesso
```

---

## 🐞 Fluxo de QA

1. Refinamento da User Story
2. Planejamento dos Testes
3. Criação dos Casos de Teste
4. Execução dos Testes
5. Registro de Defeitos
6. Reteste
7. Encerramento

---

## 🚀 Tecnologias e Ferramentas

* Markdown
* Scrum
* BDD
* QA Manual
* Clickup - Mapa mental

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto foram praticados:

* Análise de requisitos
* Escrita de User Stories
* Criação de Critérios de Aceitação
* Técnicas de Particionamento de Equivalência
* Análise de Valor Limite
* Modelagem de Casos de Teste
* Escrita de Cenários BDD

---

