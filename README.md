```mermaid
graph TD;
    A[Start] --> B{Decision?};
    B -->|Yes| C[Proceed];
    B -->|No| D[Stop];
    C --> E[End];
