```mermaid
sequenceDiagram
    participant browser
    participant server
    
    browser->> server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: [{"content": "baby tu sabe", "date": "date": date: "2024-05-12T20:43:17.533Z" }]
    deactivate server
```
  
  
