# Product-ms
## Endpoints
- BaseURL: /products
- POST creat()
- GET getAll()
- GET /{id} getById()
- PUT /{id} update()
- DELETE /{id} delete()

## Model
```json
{
  "id": 1,
  "name": "Iphone 13 Pro Max",
  "description": "Celular de ultima geracao ...",
  "price": 6999.90,
  "isAvailable": "true"
}

```
## Busness Rules
-Nao e permitido a criacao de produtos com o preco negativo. Sempre maior que 0;
-Nao e possivel pesquisar produtos que nao estao disponiveis;
-Nao e possivel inserir descricoes com menos de 50 caracteres;