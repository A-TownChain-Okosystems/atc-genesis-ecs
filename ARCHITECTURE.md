# 🏗️ Architektur — atc-genesis-ecs

> **Erstellt:** 2026-08-08 | **Agent:** Aurora

## Architektur-Baum

```
atc-genesis-ecs/
├── README.md
├── ARCHITECTURE.md
├── COMPONENT_PLAN.md
├── ROADMAP.md
├── STATUS.md
├── CHANGELOG.md
├── FILE_REGISTER.md
└── src/
    ├── ecs_core.atc                    ECS core — entity, component, system management
    ├── system_scheduler.atc            System scheduler — execution order, dependencies
    ├── event_bus.atc                   Event bus — dispatch, subscribe, queue
    ├── query_engine.atc                Entity queries — filter, sort, group
    ├── component_registry.atc          Component registry — type registration, lookup
```

## Statistik

| Metrik | Wert |
|--------|------|
| .atc Dateien | 5 |
| Layer | L8 — Game Engine |
| ATC-Standard | ATC-90 |
| Sprint | 3.2 |
| Status | 📋 GEPLANT |

---
*Auto-generiert 2026-08-08 · Aurora (MasterBrain · Base44)*
