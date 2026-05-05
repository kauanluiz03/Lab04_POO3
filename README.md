 # LAB01 - Sistema de Gerenciamento de Biblioteca

## Descrição
Sistema desenvolvido em TypeScript para o gerenciamento de acervo e empréstimos de livros.

## Como Executar
1. Compile o arquivo TypeScript:
   ```bash
   tsc biblioteca.ts# Guia de Execução - Sistema de Gerenciamento de Biblioteca

Este documento explica como configurar, executar e quais testes foram realizados no sistema desenvolvido em TypeScript[cite: 1].

## 1. Como Executar o Programa

Para rodar a aplicação, siga os passos abaixo no seu terminal:

1.  **Instalação do TypeScript**: Caso ainda não tenha o compilador instalado, execute:
    ```bash
    npm install -g typescript
    ```

2.  **Compilação**: Transforme o arquivo TypeScript em JavaScript:
    ```bash
    tsc biblioteca.ts
    ```

3.  **Execução**: Rode o programa usando o Node.js:
    ```bash
    node biblioteca.js
    ```

## 2. Testes Realizados

Conforme os requisitos do projeto, foram implementados e executados os seguintes testes[cite: 1]:

*   **Cadastro de Livros**: Criamos três instâncias da classe `Livro` e as adicionamos ao acervo através do método `adicionarLivro`[cite: 1].
*   **Registro de Empréstimo**: Realizamos o empréstimo de um livro específico pelo seu código, alterando seu status para indisponível[cite: 1].
*   **Consulta de Disponibilidade**: Verificamos se um livro estava disponível ou não através do seu código único e imprimimos o resultado no console[cite: 1].
*   **Tratamento de Erros**: Testamos o comportamento do sistema ao tentar consultar ou emprestar livros com códigos que não existem no acervo[cite: 1].

## 🛠️ Requisitos Técnicos Aplicados
*   Uso de **Classes** e **Interfaces**[cite: 1].
*   **Encapsulamento** com modificadores de acesso (`public`, `private`)[cite: 1].
*   **Tipagem estática** em todas as variáveis e retornos de funções[cite: 1].
