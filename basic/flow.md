```mermaid
graph TD
    A[注文受け付け] --> B{在庫確認}
    B -->|在庫あり| C[出荷準備]
    B -->|在庫なし| D[在庫不足通知]
    C --> E[配送]
    E --> F[注文完了]
```