# Banking System in C - Academic Project

Este projeto foi desenvolvido como parte da disciplina de **Algoritmos** na faculdade. Trata-se de um sistema simples de gerenciamento bancário implementado em linguagem C, utilizando estruturas, controle condicional, loops e manipulação de dados em memória.

## 🎯 Objetivo

Criar um sistema bancário baseado em terminal, com operações básicas de conta e simulação de crédito, utilizando os conhecimentos adquiridos sobre lógica de programação e estrutura de dados.

## 📚 Funcionalidades

- Cadastro de clientes (restrição: maior de idade)
- Abertura de conta corrente ou poupança
- Listagem de contas cadastradas
- Depósito e saque
- Empréstimo com limite baseado no saldo e crédito total da agência
- Encerramento de contas (se saldo for zero)
- Validação de CPF para evitar duplicatas
- Interface em linha de comando (CLI)

## 🧱 Estrutura do Código

- `struct clientes`: Armazena os dados do cliente, incluindo nome, idade, CPF, tipo de conta, status, saldo e ID.
- Módulos e funções:
  - `pegaCadastro()`: Realiza o cadastro inicial do cliente.
  - `segundoMenu()`: Define o tipo de conta.
  - `listarClientes()`: Exibe todos os clientes com contas ativas e inativas.
  - `alteraStatus()`: Fecha a conta se saldo for zero.
  - `validaCpf()`: Verifica duplicidade de CPF.
  - Lógica principal controlada por `switch` no `main()` com menu interativo.

## 🛠️ Tecnologias Utilizadas

- Linguagem: C
- Plataforma: Windows
- Biblioteca: `<stdio.h>`, `<stdlib.h>`, `<stdbool.h>`, `<string.h>`, `<windows.h>`

## 🧪 Requisitos

- Compilador C (ex: GCC, Code::Blocks, Dev-C++)
- Sistema Windows (uso de `SetConsoleOutputCP(65001)` e `cls`)

## 🚀 Como Executar

1. Compile o arquivo `index.c` com o compilador C da sua preferência.
2. Execute o programa no terminal.
3. Utilize as opções do menu para interagir com o sistema.

## 👨‍🏫 Autoria

Projeto realizado como parte da disciplina de **Algoritmos**, na instituição **UP-Positivo**.



