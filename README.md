```mermaid
graph LR
    subgraph Frontend
        A[HTML] --> B(CSS)
        B --> C{JavaScript}
    end

    subgraph Backend
        D[Python] --> E(Django)
        E --> F[SQL]
    end

    C --> G{Basic Web Concepts<br>(HTTP, Requests, Responses)}
    G --> E

    C --> H{Frontend Framework<br>(React, Vue, Angular)}
    H --> I[Testing]
    E --> I
    I --> J[Deployment]

    K[Git & GitHub] --> G
    K --> E
    K --> H
    K --> I

    subgraph Other
        L[AI/ML (Optional)]
    end

    J --> M((Continuous Learning &<br>Specialization))
    L --> M

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#ccf,stroke:#333,stroke-width:2px
    style C fill:#aaf,stroke:#333,stroke-width:2px
    style D fill:#faa,stroke:#333,stroke-width:2px
    style E fill:#afa,stroke:#333,stroke-width:2px
    style F fill:#aaf,stroke:#333,stroke-width:2px
    style G fill:#eee,stroke:#333,stroke-width:2px
    style H fill:#fdd,stroke:#333,stroke-width:2px
    style I fill:#ddd,stroke:#333,stroke-width:2px
    style J fill:#ccd,stroke:#333,stroke-width:2px
    style K fill:#eee,stroke:#333,stroke-width:2px
    style L fill:#ccf,stroke:#333,stroke-width:2px
    style M fill:#ccf,stroke:#333,stroke-width:2px

    linkStyle 0,1 stroke:#0a0,stroke-width:2px
    linkStyle 1,2 stroke:#0a0,stroke-width:2px
    linkStyle 3,4 stroke:#a00,stroke-width:2px
    linkStyle 4,5 stroke:#a00,stroke-width:2px
    linkStyle 2,6 stroke:#00a,stroke-width:2px
    linkStyle 6,4 stroke:#00a,stroke-width:2px
    linkStyle 2,7 stroke:#a0a,stroke-width:2px
    linkStyle 7,8 stroke:#0aa,stroke-width:2px
    linkStyle 4,8 stroke:#0aa,stroke-width:2px
    linkStyle 8,9 stroke:#000,stroke-width:2px
    linkStyle 10,6 stroke:#000,stroke-width:2px
    linkStyle 10,4 stroke:#000,stroke-width:2px
    linkStyle 10,7 stroke:#000,stroke-width:2px
    linkStyle 10,8 stroke:#000,stroke-width:2px
    linkStyle 9,11 stroke:#000,stroke-width:2px
    linkStyle 12,11 stroke:#000,stroke-width:2px
```