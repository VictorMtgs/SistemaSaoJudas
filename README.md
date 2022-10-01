# Sistema São Judas Lanches
 Um sistema web desenvolvido para realizar pedidos de consumos de comanda de mesas,  e armazenar seus dados em um json de uma API REST, facilitando o gerenciamento da lanchonete
## Endpoints
### GET /games
Esse endpoint é reponsavel por retornar a listagem de todos os pedidos realizados no sistema.

Exemplo de resposta:

```
        {
            id: 01,
            title: "MESAS",
            year: 2002,
            price: "CONSUMOS"
        }
```

#### Parametros
Nenhum
#### Respostas
##### OK! 200
Caso essa resposta aconteça você vai receber a listagem de pedidos
##### Falha na autenticção! 401
Caso essa resposta aconteça, isso significa que aconteceu alguma falha durante o processo de autenticação.Motivos, TOKEN INVALIDO! TOKEN EXPIRADO.
