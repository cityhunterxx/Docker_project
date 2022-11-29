# Docker tutorial
## Architecture

```mermaid
graph TD;
    Proxy--> |3001| Uptime_kuma[Uptime kuma]
    Proxy--> |80| Heimdall
    Proxy--> |80| Citywebsite
    Proxy--> |9443| Portainer
```

