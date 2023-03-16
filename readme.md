```mermaid
flowchart TD
    A[Start] --> B[User]
    B --> C{Already a User}
    C --> |Yes| D[Login]
    C ----> |Go To| E[End]
    D --> |No| E[Register User]
    D ----> |Go To| E[End]
    B ---->|No| E[End]
```
