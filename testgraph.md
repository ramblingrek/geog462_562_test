```mermaid


graph TD
    A[Start] --> B[Check if second argument equals square of first argument]
    A --> C[Check if second argument equals cube of first argument]
    B --> D{Is either condition True?}
    C --> D
    D -->|Yes| E[Return True]
    D -->|No| F[Return False]
