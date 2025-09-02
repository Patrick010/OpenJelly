# OpenJelly 

**Liberate your Jellyfin plugins. Any language. Any platform. Total freedom.**

---

## What is OpenJelly?

OpenJelly is the **ultimate plugin gateway for Jellyfin**, designed to break free from the .NET plugin lock-in. Write plugins in **any language** you love. Python, Rust, Go, Node.js. OpenJelly handles the rest.  

- Minimal dependency on Jellyfin itself.  
- Only one tiny UI bridge plugin inside Jellyfin.  
- Full language-agnostic plugin ecosystem.  
- Event-driven, modular, and scalable.  

Think of it as **Jellyfin, supercharged for developers**.

---

## Why You’ll Love It

- **Freedom** - Code plugins in your favorite language.  
- **Safety** - Isolated plugins crash themselves, not your server.  
- **Stability** - OpenJelly shields plugins from Jellyfin core changes.  
- **Power** - Automate, enhance, extend, or integrate with anything.  
- **UI Injection** - Seamlessly inject menus, panels, and dashboards.  

---

## How It Works

1. **UI Bridge Plugin**: Minimal Jellyfin-native plugin that exposes UI events and injection points.  
2. **OpenJelly Gateway**: Translation layer running externally; handles events, API translation, plugin registry, and messaging.  
3. **External Plugins**: Language-agnostic, event-driven, isolated. Communicate via REST, gRPC, or WebSockets.  

Flow:  
`Jellyfin → UI Bridge → OpenJelly Gateway → Plugins → Gateway → UI Bridge → Jellyfin`  

---

## Plugin Possibilities

- Metadata enrichment and AI tagging.  
- Automated recommendations and notifications.  
- External transcoding helpers or preprocessors.  
- Real-time analytics dashboards.  
- Cross-platform orchestration or cloud-local hybrid plugins.  

**Basically:** If it’s possible in code, OpenJelly lets you plug it into Jellyfin without .NET friction.

---

## Getting Started

**Coming soon:**  
- One-command installation of the gateway.  
- Automatic plugin registration.  
- UI bridge installation in Jellyfin.  
- Prebuilt examples in Python, Rust, Node.js, and Go.  

> Developers, get ready to finally *write Jellyfin plugins the way you want to.*

---

## Join the Revolution

OpenJelly isn’t just a library, it’s a **movement for plugin freedom**.  
Follow, star, and contribute. Let’s liberate Jellyfin together.

---

**OpenJelly - Write plugins without limits.**
