# Controle de Despesas

Este é um aplicativo simples de controle de despesas que permite que os usuários registrem receitas e despesas, visualizem o saldo atual e vejam a lista de transações. Os dados são armazenados no `localStorage` do navegador, o que significa que as transações são preservadas mesmo após o recarregamento da página.

## Funcionalidades

- Adicionar transações de receitas e despesas
- Exibir o saldo atual, receitas totais e despesas totais
- Remover transações individuais
- Salvar as transações no `localStorage` para persistência

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página
- **CSS3**: Estilização do layout
- **JavaScript**: Lógica da aplicação, manipulação do DOM, e integração com o `localStorage`

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/controle-despesas.git
   ```

2. Abra o arquivo `index.html` no navegador para rodar a aplicação.

## Estrutura do Projeto

- `index.html`: Contém a estrutura básica da aplicação, com o formulário para entrada de dados e elementos onde os valores são exibidos.
- `style.css`: Estiliza os elementos para proporcionar uma interface visualmente agradável.
- `script.js`: Gerencia a lógica da aplicação, incluindo a adição, remoção e persistência de transações no `localStorage`.

## Funcionalidades de JavaScript

- **Adicionar transações**: O usuário insere o nome e o valor da transação (positiva para receita, negativa para despesa). Após clicar em "Adicionar", a transação é salva e o saldo é atualizado automaticamente.
- **Remover transações**: Cada transação tem um botão de "Excluir" que permite removê-la.
- **Persistência**: As transações são salvas no `localStorage`, de forma que, mesmo ao recarregar a página, os dados não são perdidos.

## Como Funciona

- O formulário captura os dados inseridos pelo usuário, e uma nova transação é criada com um ID único.
- As transações são renderizadas dinamicamente no DOM e os valores de saldo, receitas e despesas são atualizados com base nos valores inseridos.
- As transações são armazenadas no `localStorage` para garantir que elas persistam após o recarregamento da página.
- Ao clicar no "x" de uma transação, ela é removida da lista e os dados no `localStorage` são atualizados.
