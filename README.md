# Desafio: Sistema de Controle de Estoque

## Proposta

Desenvolver um programa que gerencie o estoque de uma loja. O programa deve permitir que o usuário adicione produtos ao estoque, consulte a quantidade disponível de um produto e exiba todos os produtos em estoque.

### Requisitos

O programa deve permitir ao usuário:

- Adicionar um produto, informando o nome e a quantidade.
- Consultar a quantidade disponível de um produto pelo nome.
- Listar todos os produtos em estoque com suas quantidades.
- O estoque deve ser armazenado em uma estrutura de dados apropriada (como um dicionário ou uma lista de objetos).
- O programa deve lidar com entradas inválidas (por exemplo, consultar um produto que não está no estoque).

### Exemplo de Interação

> O programa apresenta um menu com as opções:
>
> - adicionar produto, consultar produto, listar produtos e sair.
> - O usuário pode adicionar produtos e consultar suas quantidades.
> - Ao final, o programa exibe a lista de produtos em estoque.

#### ⚠️ Dicas:

- Considere usar uma estrutura de repetição para o menu de opções.
- Implemente funções para cada operação (adicionar, consultar, listar).
- Lembre-se de tratar entradas inválidas de maneira amigável.

#### Exemplo:

```bash
1. Adicionar produto
2. Consultar produto
3. Listar produtos
4. Sair
```

```bash
Escolha uma opção: 1
Digite o nome do produto: Camiseta
Digite a quantidade: 10
```

```bash
Escolha uma opção: 2
Digite o nome do produto: Camiseta
Quantidade disponível: 10
```

```bash
Escolha uma opção: 3
Produtos em estoque:
Camiseta: 10
Calça: 5
```

## Desenvolvimento
