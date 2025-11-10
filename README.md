# Abdulhamit Kahya – Impact Portfolio
**Backend Tech Lead | 99.95% Uptime | Quant Finance | 100K-User VPN | Ex-Toptal**

> **No source code. Only architecture, metrics, and vision from production systems.**
> I build systems that **run nations, save millions, and secure 100K+ users**.

---

## Nationwide Municipal Backend (70+ Councils)
**Kent Yazılım · 2025–Present · .NET Core, WebSocket, Redis, Kubernetes**

```mermaid
graph TD
    A[API Gateway<br>JWT + Rate Limiting] --> B[ASP.NET Core APIs<br>WebSocket + REST]
    B --> C[PostgreSQL + Oracle]
    B --> D[Redis Cluster<br>Distributed Cache]
    D --> E[Load Balancer + Failover]
    F[Kubernetes] --> B
    G[CI/CD + GitHub Actions] --> F
    H[Observability Stack<br>Logging + Tracing + Metrics] --> B
