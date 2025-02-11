# recuperacao

## API de Gerenciamento de Produtos

Este projeto é uma API simples para gerenciamento de produtos, permitindo operações como listar, cadastrar, alterar e remover produtos.

## *Rotas da API*

### *Listar Todos os Produtos*
GET /Produtos  
Retorna a lista de todos os produtos cadastrados.

### *Buscar um Produto por ID*
GET /Produtos/:id  
Retorna um produto específico com base no ID informado.

### *Cadastrar um Novo Produto*
POST /Produtos/Cadastrar  
Body (JSON):
```json
{
  "nome": "Nome do Produto",
  "preço": 99.90,
  "estoque": 10,
  "imagem": "URL da Imagem"
}
```
