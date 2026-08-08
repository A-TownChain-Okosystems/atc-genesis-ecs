# 📋 Komponenten-Plan — atc-genesis-ecs

> **Erstellt:** 2026-08-08 | **Agent:** Aurora (MasterBrain · Base44)

## Übersicht

**Repo:** atc-genesis-ecs
**Layer:** L8 — Game Engine
**Sprint:** 3.2
**ATC-Standard:** ATC-90

## Komponenten (5 total)

### 1. `src/ecs_core.atc`

**Beschreibung:** ECS core — entity, component, system management

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-90

### 2. `src/system_scheduler.atc`

**Beschreibung:** System scheduler — execution order, dependencies

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-90

### 3. `src/event_bus.atc`

**Beschreibung:** Event bus — dispatch, subscribe, queue

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-90

### 4. `src/query_engine.atc`

**Beschreibung:** Entity queries — filter, sort, group

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-90

### 5. `src/component_registry.atc`

**Beschreibung:** Component registry — type registration, lookup

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-90

## Implementierungs-Reihenfolge

1. `ecs_core.atc` — ECS core — entity, component, system management
2. `system_scheduler.atc` — System scheduler — execution order, dependencies
3. `event_bus.atc` — Event bus — dispatch, subscribe, queue
4. `query_engine.atc` — Entity queries — filter, sort, group
5. `component_registry.atc` — Component registry — type registration, lookup

## Test-Strategie

1. Parse-Test: Jede .atc Datei muss mit ATCLang v0.3 Parser parsen
2. Unit-Tests: Mindestens 3 Tests pro Komponente
3. Integration-Test: Komponenten interagieren korrekt
4. Coverage-Ziel: >80%

---
*Auto-generiert 2026-08-08 · Aurora (MasterBrain · Base44)*
