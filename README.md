# 📚 Sistema de Biblioteca

Sistema simples de gerenciamento de empréstimos de livros, desenvolvido em Python com Programação Orientada a Objetos.

## 💡 Sobre o projeto

O sistema simula o funcionamento básico de uma biblioteca, permitindo:

- Cadastrar livros com título, autor, ISBN e status de disponibilidade
- Cadastrar usuários e manter um histórico simples de empréstimos
- Emprestar e devolver livros, com controle de disponibilidade

## 🧱 Estrutura

O projeto é organizado em três classes:

- **`Livro`** — representa um livro e controla seu status (`Disponível` / `Emprestado`), com os métodos `emprestar()` e `devolver()`.
- **`Usuario`** — representa o usuário da biblioteca, guardando nome, ID e o último livro emprestado.
- **`Biblioteca`** — orquestra a relação entre livro e usuário, executando os empréstimos e devoluções e exibindo o resultado de cada operação.

## ▶️ Como executar

O projeto foi desenvolvido no Google Colab. Para rodar:

1. Abra o arquivo `Sistema_de_Biblioteca.ipynb` no [Google Colab](https://colab.research.google.com/) ou no Jupyter Notebook
2. Execute a célula de código
3. Veja o resultado do empréstimo e devolução no console

Exemplo de saída:
```
Carlos tentou emprestar '1984': Livro emprestado
Carlos devolveu '1984': Livro devolvido
```

## 🚀 Próximos passos

Algumas ideias para evoluir o projeto:
- Adicionar múltiplos livros e usuários em uma lista
- Impedir empréstimo de livro já emprestado com mensagem de erro tratada
- Criar um histórico completo de empréstimos (não só o último)
- Persistir os dados em arquivo ou banco de dados

## 🛠️ Tecnologias

- Python 3

---
Projeto desenvolvido como prática de Programação Orientada a Objetos.
