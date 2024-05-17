# Nuevo diagrama de nota

```mermaid
flowchart TD
    A[User] -->|Write message| B(Click Save button)
    B -->|POST https://studies.cs.helsinki.fi/exampleapp/new_notes| C(Server)
    C -->|Redirect to /notes| D[Browser]
```
