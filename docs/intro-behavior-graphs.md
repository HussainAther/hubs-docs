### ✅ `docs/intro-behavior-graphs.md`

```md
# 🧠 Introduction to Behavior Graphs

**Behavior Graphs** are a visual node-based system for defining interactivity in Hubs scenes. They allow creators to build logic into objects using a simple and intuitive interface—no coding required.

Behavior Graphs are authored in [Blender](https://www.blender.org/) and exported as part of `.glb` files, which are then used in Spoke or directly in Hubs scenes.

---

## 📌 Why Use Behavior Graphs?

Behavior Graphs empower creators to:

- Define interactions (e.g., clicking an object triggers animation)
- Respond to user presence or events (e.g., proximity triggers)
- Modify object states (e.g., show/hide elements)
- Trigger sound or visual effects
- Chain together logic and create reusable interaction patterns

They provide a **low-code or no-code alternative** to writing raw JavaScript or scripting logic manually.

---

## 🎛️ Core Concepts

| Concept             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Nodes**           | Represent logic units like triggers, conditions, actions, or modifiers.    |
| **Connections**     | Arrows between nodes define the flow of execution or data.                  |
| **Inputs/Outputs**  | Nodes have ports for incoming/outgoing signals, numbers, text, etc.         |
| **Graphs**          | Each object in the scene can include one or more graphs for behavior.       |

---

## 🛠️ Authoring Behavior Graphs

1. **Open Blender**
2. **Import the Hubs Behavior Graph Add-on** (if not pre-installed)
3. **Select an object**, then open the Behavior Graph Editor
4. **Create nodes** from the Add menu (e.g., `OnClick`, `PlayAnimation`)
5. **Connect nodes** to define the logic
6. **Export the object** as a `.glb` with the graph embedded

These exported models can be imported into Spoke or placed directly in your Hubs scene.

---

## 📦 Supported Node Types

- **Triggers**: OnClick, OnHover, OnStart, OnProximity
- **Actions**: Show, Hide, PlaySound, Animate, MoveTo
- **Logic**: If, Delay, Repeat, Random
- **Variables**: SetValue, GetValue, Compare

The available nodes may vary slightly depending on the Blender plugin version.

---

## 🔎 Viewing and Debugging Graphs

While authored in Blender, exported `.glb` files include the behavior graph data in the metadata.

Future add-ons (in development) will allow you to:

- Inspect graphs in Hubs
- Export behavior graphs to readable JSON
- Visualize connections and errors during runtime

---

## 📚 Additional Resources

- [Hubs Blender Exporter Repo](https://github.com/MozillaReality/hubs-blender-exporter)
- [Spoke Editor](https://hubs.mozilla.com/spoke)
- [Blender Behavior Graph Docs](https://github.com/MozillaReality/hubs-blender-exporter/wiki/Behavior-Graphs)
- [Hubs Docs Main Page](../README.md)

---

_For contributions to this document, please follow our [Pull Request Guidelines](https://github.com/Hubs-Foundation/policies-procedures-guidelines-public/blob/main/pull-request-guidelines.md) and [Commit Message Standards](https://github.com/Hubs-Foundation/policies-procedures-guidelines-public/blob/main/commit-message-guidelines.md)._

