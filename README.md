<p align="center">
  <img src="assets/logo.svg" alt="Foldy for Antigravity CLI" width="120" />
</p>

<h1 align="center">Foldy for Antigravity CLI (<code>/foldy</code>)</h1>

<p align="center">
  <a href="#-english">🇺🇸 English</a> · <a href="#-español">🇪🇸 Español</a> · <a href="https://github.com/dsaez27/Foldy">🌐 Foldy Browser Extension</a>
</p>

---

## 🇺🇸 English

**Foldy for Antigravity CLI** (`foldy-agy`) is a native plugin for **Google Antigravity CLI (`agy`)** that brings smart folders, keyword auto-classification, a Quick Prompt Vault with `{{variable}}` templates, lock protection (`🔒`), safe bulk deletion, Markdown (`.md`) export, and **full `foldy1:` Sync Code compatibility** with the [Foldy browser extension](https://github.com/dsaez27/Foldy).

### 🎯 `/foldy` Slash Commands

| Command | Description |
| :--- | :--- |
| `/foldy` | Opens the interactive Foldy dashboard & menu |
| `/foldy chats [page\|all]` | Opens the unified tabular arrow+Space multi-select conversation picker |
| `/foldy folders` | Lists smart folders, colors, keywords, and chat counts |
| `/foldy new <name> [keywords...]` | Creates a new smart folder with auto-classification rules |
| `/foldy auto` | Auto-classifies all unassigned conversations by keywords |
| `/foldy search <query>` | Searches conversation titles, folders, and full transcripts |
| `/foldy prompts` | Opens the Quick Prompt Vault (`{{variable}}` support) |
| `/foldy prompt <id or name>` | Renders and runs a saved prompt template |
| `/foldy sync` | Exports a `foldy1:` Sync Code for Foldy browser extension |
| `/foldy sync foldy1:...` | Imports & merges a `foldy1:` Sync Code from Foldy Web |
| `/foldy lock` / `/foldy unlock` | Locks/unlocks a conversation (`🔒`) against bulk deletion |
| `/foldy export` | Exports conversation(s) to a clean Markdown (`.md`) file |
| `/foldy clean` | Safe bulk deletion (dry-run preview first, skips `🔒` chats) |

---

## 🇪🇸 Español

**Foldy for Antigravity CLI** (`foldy-agy`) es un plugin nativo para **Google Antigravity CLI (`agy`)** que incorpora carpetas inteligentes, auto-clasificación por palabras clave, Bóveda de Prompts Rápidos con variables `{{var}}`, protección con candado (`🔒`), borrado masivo seguro, exportación a Markdown (`.md`) e **interoperabilidad total mediante Sync Code `foldy1:`** con la [extensión de navegador Foldy](https://github.com/dsaez27/Foldy).

### 🎯 Comandos `/foldy`

| Comando | Descripción |
| :--- | :--- |
| `/foldy` | Abre el panel y menú interactivo de Foldy |
| `/foldy chats [página\|all]` | Abre la tabla interactiva seleccionable con flechas (`↑`/`↓`) y `Espacio` |
| `/foldy carpetas` (o `folders`) | Lista tus carpetas inteligentes, colores, palabras clave y conteos |
| `/foldy new <nombre> [keywords...]` | Crea una carpeta nueva con reglas automáticas |
| `/foldy auto` | Auto-clasifica todas las conversaciones sin carpeta |
| `/foldy buscar <texto>` (o `search`) | Busca por título, carpeta y contenido completo de transcripts |
| `/foldy prompts` | Abre la Bóveda de Prompts Rápidos (`{{variable}}`) |
| `/foldy prompt <id o nombre>` | Rellena variables y ejecuta un prompt guardado |
| `/foldy sync` | Genera tu Sync Code `foldy1:` para llevarlo a Foldy Web |
| `/foldy sync foldy1:...` | Importa y fusiona un Sync Code copiado desde Foldy Web |
| `/foldy lock` / `/foldy unlock` | Protege o desprotege una conversación con candado (`🔒`) |
| `/foldy export` | Exporta conversaciones a un archivo Markdown (`.md`) |
| `/foldy clean` | Limpieza segura (siempre muestra vista previa y omite chats `🔒`) |

### 🔗 Sincronización con Foldy Web (`foldy1:`)

1. Abre el popup de **Foldy** en Chrome, Edge, Brave o Firefox y haz clic en **Copiar código** (`foldy1:...`).
2. En Antigravity CLI escribe:
   ```text
   /foldy sync foldy1:H4sI...
   ```
3. Tus carpetas, auto-reglas y Bóveda de Prompts quedan sincronizados al instante. También funciona en sentido inverso con `/foldy sync`.

---

<p align="center">
  © 2026 Foldy · All rights reserved.
</p>
