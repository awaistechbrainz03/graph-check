```mermaid
flowchart TD
    A[Start] --> B[User]
    B --> C{Already a User}
    C --> |Yes| D[Login] 
    C --> |No| E[Register User]
    E ----> |Go To| F[End]
    D ----> |Go To| F[End]
```
