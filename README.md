# Terminal Graph Blueprints

**Terminal Graph Blueprints** defines the state schemas, spatial node layouts, and blueprint templates for terminal-native graph canvases (`.terminalgraph/state.json`).

---

## 1. Overview

Terminal Graph is a lightweight, spatial canvas for planning software architecture, mapping agent systems, and tracking project states directly within the terminal environment.

Each canvas workspace stores its state in `.terminalgraph/state.json`.

---

## 2. Blueprint Node Types

- **`note`**: Freeform markdown text blocks with automatic word-wrap and sticky sizing.
- **`card`**: Structured metadata cards representing repositories, milestones, or services.
- **`group`**: Visual spatial bounding boxes that cluster related nodes together.
- **`link`**: Edge connector binding two nodes with directional arrows and optional relationship labels.

---

## 3. Schema Reference

See [`schema.json`](./schema.json) for the full JSON Schema validation spec.
