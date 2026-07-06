'''mermaid
flowchart TD
    A([Start])
    B[/Input Price1 and Quantity1/]
    C[/Input Price2 and Quantity2/]
    D[/Input Price3 and Quantity3/]
    E[subtotal1 = price1 * quantity1]
    F[subtotal2 = price2 * quantity2]
    G[subtotal3 = price3 * quantity3]
    H[totalBill = subtotal1 + subtotal2 + subtotal3]
    I[/Display Total Bill/]
    J([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
'''