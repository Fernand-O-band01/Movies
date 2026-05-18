```mermaid
erDiagram
LOBBY ||--o{MESA : "contiene"}
MESA || --o{PEDIDO : "genera"}
PEDIDO || --o{PRODUCTO : "incluye"}

LOBBY {
    int id PK
    string nombre_restaurante
    string estado
}

```
