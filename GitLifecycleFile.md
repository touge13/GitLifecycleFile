```mermaid
flowchart TD
    A["untracked (не отслеживаемый)"] -->|git add| B["staged (в списке на коммит) + tracked"]
    B -->|git commit| C["tracked (отслеживаемый)"]
    B -->|изменения| D["modified (измененный)"]
    C -->|изменения| D
    D -->|git add| B

```
