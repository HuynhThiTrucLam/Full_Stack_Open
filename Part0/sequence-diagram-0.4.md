```mermaid
sequenceDiagram
    participant User
    participant App
    participant Server

    User->>App: Click "Get Data"
    App->>Server: Send Request
    Server-->>App: Response
    App-->>User: Show Results
```
