# Exercise 0.4 - New Note

```mermaid
sequenceDiagram
    participant Browser
    participant Server

    Browser->>Server: POST new note
    Server-->>Browser: Redirect to /notes
    Browser->>Server: GET /notes
    Server-->>Browser: HTML
```
