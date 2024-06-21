graph TD
    A[Start] --> B[Customer LLM Bot Initiates Interaction]
    B --> C[Bank LLM Bot Interacts and Records Responses]
    C --> D[Profile Creation and Storage System Analyzes Responses]
    D --> E[Profile Created and Stored]
    
    E --> F[Continuous Monitoring and Challenge-Response Begins]
    F --> G[Bank LLM Bot Issues Dynamic Challenges]
    G --> H[Customer LLM Bot Responds to Challenges]
    
    H --> I[Monitoring and Analysis Engine Verifies Responses]
    I --> J{Responses Consistent?}
    
    J -- Yes --> K[Session Continues Securely]
    K --> F
    
    J -- No --> L[Anomaly Detected]
    L --> M[Security and Anomaly Detection System Alerts]
    M --> N[Appropriate Actions Taken]
    
    N --> O[Logging and Audit System Records Interaction]
    F --> O
    
    O --> F
    M --> F
    
    style A fill:#f9f,stroke:#333,stroke-width:4px
    style E fill:#bbf,stroke:#333,stroke-width:4px
    style K fill:#bbf,stroke:#333,stroke-width:4px
    style N fill:#bbf,stroke:#333,stroke-width:4px
