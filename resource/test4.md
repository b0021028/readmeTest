
```mermaid
erDiagram

    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
ORDER 1--o| LINE-f : contains
```

~~~md
``` mermaid
erDiagram

    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
ORDER 1--o| LINE-f : contains
```
~~~
