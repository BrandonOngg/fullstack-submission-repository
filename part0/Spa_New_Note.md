# 0.6 Single Page App New Note DIagram
```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: [{ "content": "Single page app does not reload the whole page", "date": "2019-05-25T15:15:59.905Z" }]
    deactivate server