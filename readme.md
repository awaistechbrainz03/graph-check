```mermaid
flowchart TD
    A[Start] --> B[User]
    B --> C{Already a User}
    C --> |Yes| D[Login] 
    C --> |No| E[Register User]
    C ----> |Go To| F[End]
    D ----> |Go To| F[End]
```
