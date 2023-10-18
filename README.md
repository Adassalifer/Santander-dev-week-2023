# Santander-Dev-Week-2023
Java RESTfull API criada para a Santander Dev week 2023.

## Diagrama de Classes

```mermaid
classDiagram
  class Usuario {
    -id: int
    -nome: string
    -cpf: string
    -endereco: Endereco
    -contas: Conta[]
  }
  class Endereco {
    -rua: string
    -cidade: string
    -estado: string
    -cep: string
  }
  class Conta {
    -numero: string
    -tipo: string
    -saldo: float
  }

  Usuario --|> Endereco
  Usuario --|> Conta
```
