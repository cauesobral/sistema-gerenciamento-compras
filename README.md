# Sistema de Gerenciamento de Compras

Sistema desenvolvido em **C** para gerenciamento de compras e estoque, executado via terminal. O projeto permite o cadastro e autenticação de usuários, controle de produtos em estoque e criação de listas de compras, utilizando arquivos de texto para armazenamento das informações.

## Funcionalidades

- Cadastro de usuários
- Login com autenticação
- Gerenciamento de estoque
  - Visualizar produtos
  - Adicionar produtos
  - Remover produtos
  - Consultar informações do estoque
- Criação de listas de compras
- Persistência de dados utilizando arquivos `.txt`

## Tecnologias Utilizadas

- Linguagem C
- Manipulação de arquivos
- Estruturas de dados básicas
- Modularização do código
- Code::Blocks (projeto original)

## Estrutura do Projeto

```
Prj_Lista_de_compras/
├── main.c
├── backend.c
├── banco_de_dados.c
├── sistema.h
├── usuarios.txt
├── estoque.txt
├── lista_compras.txt
└── ...
```

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/sistema-gerenciamento-compras.git
```

2. Abra o projeto no **Code::Blocks** ou compile utilizando um compilador C, como GCC.

Exemplo com GCC:

```bash
gcc main.c backend.c banco_de_dados.c -o sistema
```

3. Execute o programa:

```bash
./sistema
```

No Windows:

```bash
sistema.exe
```

## Objetivos do Projeto

Este projeto foi desenvolvido para praticar conceitos importantes da linguagem C, incluindo:

- Organização de projetos em múltiplos arquivos
- Modularização
- Manipulação de arquivos
- Entrada e saída de dados
- Estruturas condicionais e de repetição
- Funções
- Desenvolvimento de aplicações em terminal

## Melhorias Futuras

- Interface gráfica
- Banco de dados relacional (SQLite ou PostgreSQL)
- Criptografia de senhas
- Controle de níveis de acesso
- Relatórios de estoque
- Histórico de compras
- Melhor tratamento de erros

## Licença

Este projeto foi desenvolvido para fins de estudo e aprendizado.
