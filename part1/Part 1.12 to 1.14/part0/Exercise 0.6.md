```mermaid
sequenceDiagram
participant browser
participant server

browser ->>server: POST new note
activate server
server -->>browser: 201 new note created
deactivate server

Note right of browser: browser updates display locally and inserts the new note

```
