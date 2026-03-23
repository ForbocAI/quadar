<!-- AESTHETIC_PROTOCOL_COMPLIANCE -->

<!-- ᚠ ᚢ ᚦ ᚨ ᚱ ᚲ ᚷ ᚹ -->

```text
    [VOID::WATCHER]

```

SYSTEM_OVERRIDE // NEURAL_LINK_ESTABLISHED // LOG_ERR_CRITICAL



---
# 🌑 FORBOC AI: THE PLATFORM 🌑

`Prócess_Id // Platfórm_Ínit`

**ᚠ ᛫ ᛟ ᛫ ᚱ ᛫ ᛒ ᛫ ᛟ ᛫ ᚲ**

```text
    _________
   /         \
  /  0     0  \
 |      ^      |
  \  \_____/  /
   \_________/
```

The **Forboc AI Platform** is the window into the Neural Grid. It is the flagship consumer of the ForbocAI SDK, providing the high-frequency interface for real-time generative narrative and decentralized agent interaction.

> *Reality is a protocol. We are the architects.*

### ⚡ System Specifications
Built on **Next.js 16** and **Tailwind CSS**, designed for maximum visual impact and sub-millisecond responsiveness.

- **Neural Grid Integration**: Native hook into the `forbocai` SDK via the [multi-round protocol](https://classified.forboc.ai/reference/api/scope-and-glossary.html) — API orchestrates directive, context, and verdict; SDK executes locally.
- **Dynamic Simulation**: Real-time rendering of procedural environments and autonomous NPC behaviors.
- **Vengeance UI**: A high-fidelity, grimdark aesthetic framework.

### 🛠️ Boot Sequence
To initialize the mainframe:

```bash
npm install
npm run dev
```

To preview the static Cloudflare export locally:

```bash
npm run build
npm run preview
```

## Cloudflare Deploy

Pushes to GitHub can deploy this repo to Cloudflare Pages through [deploy-cloudflare-pages.yml](/Users/seandinwiddie/GitHub/Forboc.AI/quadar/.github/workflows/deploy-cloudflare-pages.yml).

Set these repository settings before relying on the workflow:

- GitHub secret `CLOUDFLARE_API_TOKEN`: API token with Cloudflare Pages edit access for the target account.
- GitHub variable `CLOUDFLARE_ACCOUNT_ID`: Cloudflare account ID that owns the Pages project.
- GitHub variable `CLOUDFLARE_PAGES_PROJECT_NAME`: existing Cloudflare Pages project name for Quadar.

The workflow installs dependencies, runs `npm run build` to export the app into `out/`, and uploads that static directory to Cloudflare Pages with `wrangler pages deploy`.

### 🌑 Aesthetic Mandates
Strict adherence to the [Style Guide](./style-guide.md) is expected.
- **Paranoid Reality**: Guided by `Philip K. Dick`.
- **High-Tech Low-Life**: Guided by `William Gibson`.
- **Eldritch Infrastructure**: Guided by `H.P. Lovecraft`.

---
*SYS_LOAD_COMPLETE // VOID_STABLE*

## License
All rights reserved. © 2026 ForbocAI. See [LICENSE](./LICENSE) for full details.
