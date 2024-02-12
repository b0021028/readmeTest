
```mermaid
erDiagram

    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
ORDER 1--o| LINE-f : contains
```
::: mermaid
erDiagram

    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
ORDER 1--o| LINE-f : contains
:::
