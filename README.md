# MISIÓN MARTE 🚀

Sitio web del bootcamp **MISIÓN MARTE**: aprende **Microsoft Agent Framework** construyendo
agentes de IA a lo largo de una expedición de 8 fases, del encendido al aterrizaje en Marte.

**Web en vivo:** https://mars-expedition.github.io/mars-mission/

El código de los retos de cada fase vive en su propio repositorio:
[mars-mission-labs](https://github.com/mars-expedition/mars-mission-labs).

## Fases

| # | Fase | Tema | Estado |
|---|------|------|--------|
| 01 | IGNITION | Fundamentos: primer agente, streaming y sesiones | ✅ |
| 02 | LAUNCH | Tools y MCP | 🔒 |
| 03 | ORBIT | Sesiones y middleware | 🔒 |
| 04 | TRANSIT | RAG y conocimiento | 🔒 |
| 05 | APPROACH | Memoria persistente | 🔒 |
| 06 | ENTRY | Observabilidad y evaluación | 🔒 |
| 07 | DESCENT | Workflows multi-agente | 🔒 |
| 08 | LANDING | HITL y frontend | 🔒 |

Las fases se desbloquean conforme avanza el bootcamp.

## Desarrollo

Sitio estático puro (HTML/CSS/JS, sin build). Para previsualizar en local:

```bash
python3 -m http.server 8000
```

y abre http://localhost:8000. Cada push a `main` despliega automáticamente a GitHub Pages.
