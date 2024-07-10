```mermaid
graph TD
    A[Server Hardware] --> B[Operating System]
    B --> C[Virtualization Layer]
    C --> D[Windows VM]
    C --> E[Docker VM]
    C --> F[Kubernetes Cluster]
    B --> G[NAS]
    B --> H[Web UI]

    C --> I[Docker Host]
    I --> J[Plex with HW Transcoding]
    I --> K[Deluge]
    I --> L[Nginx Proxy Manager / SWAG]
    I --> M[Pi-hole]
    I --> N[Paperless-ngx]
    I --> O[Scrypted]
```
