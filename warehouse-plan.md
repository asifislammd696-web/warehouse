# Client Flow BD — Warehouse System
## Complete AI Reference Document

> **Owner:** Asif Khan — Founder & CEO of Client Flow BD
> **AI Manager:** SenseNova 6.8 Flash Lite (Hermes Agent)
> **File:** `/home/asif-khan/warehouse.html` (68 KB, single HTML file)
> **Version:** v2 (2026-09-25)
> **Purpose:** Personal AI-powered life + business hub for one CEO + AI workforce

---

## 1. CORE PHILOSOPHY

This warehouse is a **personal AI operating system** — not just a business dashboard. It mirrors Khalid Farhan's "Command Centre" concept:
- AI Agent builds and maintains the dashboard
- CEO (human) just looks at it, gives commands, and approves decisions
- Business + personal life + learning + finance — everything in one hub
- Ever-evolving — new features added weekly based on AI conversations

**Principle:** Human = decision-maker. AI = operator, builder, developer.

---

## 2. ARCHITECTURE (Current — v2)

```
Single HTML file: /home/asif-khan/warehouse.html
├── Pure HTML5 + CSS + Vanilla JavaScript
├── No frameworks, no build step, no dependencies
├── Google Fonts loaded (Space Grotesk, Inter, JetBrains Mono)
├── Data: In-memory JavaScript objects (NOT persisted)
├── Navigation: Top pill nav with active state
└── Interactive: Click nav to switch pages
```

**Future Architecture Plan:**
```
Hermes Agent (Manager) → Telegram → CEO
       ↓
Custom Backend (Node/Python)
       ↓
Warehouse Frontend (HTML/CSS/JS)
       ↓
SQLite Database + External APIs
       ├── Google Calendar
       ├── Gmail (newsletter)
       ├── YouTube (competitor tracking)
       ├── Crypto/Stock APIs
       └── Telegram (commands)
```

---

## 3. DESIGN SYSTEM (Custom — NOT Farhan's colors)

### Color Palette
| Token | Hex | Use |
|---|---|---|
| `--bg` | `#FBF7F0` | Warm cream background |
| `--ink` | `#0A0A0A` | Primary text |
| `--ink-soft` | `#555` | Secondary text |
| `--brand-grad` | `#FF6B4A → #FF8C5A → #FFB64D → #FFD96A` | Header gradient (Coral → Amber → Gold) |
| `--coral` | `#FF6B4A` | Primary brand |
| `--amber` | `#FFB64D` | Warm accent |
| `--gold` | `#FFD96A` | Yellow highlight |
| `--mint` | `#3DDC97` | Positive/growth/CTA |
| `--sky` | `#4EC9F1` | Logo box, "INTEL", calendar |
| `--violet` | `#8B6BD9` | Research, Memory |
| `--rose` | `#FF4F8B` | Alerts, books, loss |
| `--lime` | `#A6E22E` | Weird Knowledge, video ideas |
| `--dark` | `#0F0E17` | Dark cards, net worth hero |

### Neo-Brutalism Style Rules
- **Border:** `3px solid #000` on every card & button
- **Shadow:** `6px 6px 0 #000` (hard, no blur)
- **Border-radius:** `14px` cards, `999px` pills
- **Typography:** Space Grotesk (headings), Inter (body), JetBrains Mono (numbers)
- **Tags:** `2px solid #000` border, `999px` radius, uppercase, small font

### Fonts (Google Fonts)
```html
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
```

---

## 4. SECTIONS (9 total)

### 4.1 Home / Command Centre
**Purpose:** Daily hub — first thing CEO opens each morning.
**Layout:** 2-column grid

- **Calendar** (cyan header): Today + tomorrow events with black left bar
- **To-Do** (yellow header): Task input + task list with checkboxes
- **Weird Knowledge** (lime header): Daily random fact from AI
- **Book Notes** (rose header): Daily rotating book quote + lesson
- **Newsletter Insights** (mint header): 6-hour cycle AI-curated news with source tags

### 4.2 Social Intel
**Purpose:** Track competitor sponsors + own platform reach.
**Sections:**
- **Your Reach:** 4 platform cards (YouTube, LinkedIn, Facebook, Instagram) with brand colors
- **Competitor Channels:** List with Scan/Delete buttons + Add form
- **Sponsor Leads:** Grid of brands sponsoring competitors, color-coded by category (Finance=green, Retail=cyan, SaaS=pink)

**Sample BD competitors:** CodeRising BD, BD Software Hub, TechDhaka
**Sample BD sponsor leads:** Sreem, bKash, Chaldari, Shohoz

### 4.3 Content Calendar
**Purpose:** Track content from idea → publish (Trello-style Kanban).
**Columns:** Idea → Recorded → In Edit → Ready to Publish
**Each card:** Title, date, duration, ← → Edit ✕ buttons
**Video Ideas section:** AI-researched daily video ideas (numbered list with rationale)

### 4.4 Investments
**Purpose:** Track net worth across crypto, stocks, gold, FD, land.
**Hero:** Black card with estimated net worth + VS INVESTED comparison
**Currency breakdown:** USD / BDT / EUR holdings (3-column)
**Portfolio cards:** Crypto, Stocks BD, Stocks Intl, FD+Gold
**Position table:** Full list of all positions with current value, invested, % change

**Auto-update:** Crypto + stocks daily, Land manual.

### 4.5 Clients
**Purpose:** CRM for Client Flow BD.
**Tabs:** Active | Expired | All (with counts)
**Client card structure:**
- Company name + Status badge (AUTO=green / MANUAL=yellow)
- Contact person name
- Service tags: SAAS (cyan), REACT (violet), PAYMENT (yellow), MOBILE (rose), FLUTTER (mint), E-COM (rose), SHOPIFY (cyan), UI/UX (violet), DEV (cyan), API (yellow), NODE (mint), AWS (violet)
- MRR (Monthly Recurring Revenue) + LTV (Lifetime Value)
- Tenure: "Since [date] · [duration]"

**Current clients (sample data):**
- Acme Corp — SAAS, React, Payment — ৳850,000/mo
- Nexus Ltd — Mobile, Flutter — ৳450,000/mo
- Bonolota Fashion — E-Com, Shopify, UI/UX — ৳350,000/mo
- TechDhaka BD — Dev, API — ৳120,000/mo
- Chaldari Digital — SaaS, Node, AWS — ৳650,000/mo

**Total MRR:** ৳2,850,000

### 4.6 Leads / Pipeline
**Purpose:** Sales pipeline from prospect → won.
**Stages (4-column Kanban):**
1. 🔍 Focus (gold) — Priority leads
2. 📞 Prospect (blue) — Initial contact
3. 💬 Interested (violet) — Positive response
4. ✅ Won (mint) — Closed deal

**Sample leads:** Zomato BD, Shohoz HR, Foodpanda BD, Bikroy.com, Pickaboo

### 4.7 Research
**Purpose:** AI-powered deep research with 4 modes.
**Modes:**
- 🎬 YouTube Script (15-20 min narration)
- 💡 Business Idea (validation, competitor analysis)
- ⚖️ Tech Comparison (stack decisions)
- 📊 Market Analysis (market sizing)

**Features:**
- Textarea input + mode toggle
- "Research Now" button (disabled until input)
- Recent research list with View button
- Helper: "⌘ + Enter to run"

### 4.8 Memory Vault
**Purpose:** Digital journal + long-term memory (10-20 year horizon).
**Layout:**
- **Constellation visualization:** Dark navy background with connected glowing dots (orange, green, gold, violet, cyan, rose) — network metaphor for memories
- **Composer:** Dark card with textarea + Save button (⌘ + Enter)
- **Search:** Quick search + Natural language query (purple border = active)
- **Date-wise memory list:** Entries grouped by month, color-coded tags (PROJECT=cyan, SETUP=cyan, DECISION=yellow, MILESTONE=rose)

**Sample memories (Sep 2026):**
- Bonolota Fashion bug fixes complete
- Hermes Desktop + Docker setup working
- Warehouse Phase 1 visual UI complete
- Client Flow BD day 100 milestone

### 4.9 Team
**Purpose:** AI agent team management.
**5 Agent Cards:**
1. 🥎 **Manager Agent** (coral avatar) — SenseNova 6.8 Flash · CEO assistant, delegates tasks
2. 🧪 **Research Agent** (violet header) — Claude Sonnet · Competitor tracking, market analysis
3. 💻 **Developer Agent** (mint header) — Claude Opus · Code, debug, ship
4. 🎙️ **Marketing Agent** (rose header) — GPT-5 · Content, social, outreach
5. 🧪 **QA Agent** (yellow header) — GPT-4o · Testing, verification

**Each card shows:**
- Role name + model used
- Function description
- Capability tags (3 per agent)
- Status (Online/Idle) with color
- Tasks today count
- Telegram handle

---

## 5. CURRENT PHASE STATUS

| Phase | Description | Status |
|---|---|---|
| ✅ Phase 1 | Visual UI (9 sections, Neo-Brutalism design) | DONE |
| ❌ Phase 2 | Data persistence (localStorage / JSON) | NOT STARTED |
| ❌ Phase 3 | Real data integration (Client Flow BD actual data) | NOT STARTED |
| ❌ Phase 4 | Agent integration (Telegram auto-update) | NOT STARTED |
| ❌ Phase 5 | Backend + Database (SQLite) | NOT STARTED |
| ❌ Phase 6 | Hosting (Cloudflare Pages / Vercel) | NOT STARTED |
| ❌ Phase 7 | Authentication (login/password) | NOT STARTED |
| ❌ Phase 8 | Mobile PWA / React app | NOT STARTED |

---

## 6. NEXT STEPS (Roadmap)

### Priority 1 — Data Persistence
- Convert all in-memory sample data to `localStorage`
- Add export/import JSON functionality
- Backup/restore system

### Priority 2 — Agent Integration
- Manager Agent auto-updates sections via API calls
- Telegram command → Warehouse update
- Cron jobs for daily refresh (newsletter every 6h, competitor scan daily 9AM)

### Priority 3 — Backend
- Node.js + SQLite backend
- REST API endpoints for each section
- Data validation layer

### Priority 4 — Real Data
- Client Flow BD actual client data (replace sample)
- Real investment positions
- Real calendar integration (Google Calendar API)

### Priority 5 — Deployment
- Host on Cloudflare Pages (free)
- Custom domain: warehouse.clientflowbd.com
- Set up password auth

---

## 7. KEY FILES & LOCATIONS

```
/home/asif-khan/
├── warehouse.html              # Main warehouse (v2, 68KB)
├── Bonolota-Website-FIXED.zip  # Fixed website ZIP (separate project)
├── bonolota/                   # Bonolota source code
└── farhan-screenshots/         # Khalid Farhan screenshots (reference)
```

---

## 8. AI AGENT TEAM — ROLE MATRIX

| Agent | Model | Responsibility | Telegram |
|---|---|---|---|
| Manager | SenseNova 6.8 Flash | CEO assistant, delegates, approvals | @clientflow_manager |
| Research | Claude Sonnet | Competitors, markets, newsletters | @clientflow_research |
| Developer | Claude Opus | Code, bugs, deployments | @clientflow_dev |
| Marketing | GPT-5 | Content, LinkedIn, outreach | @clientflow_marketing |
| QA | GPT-4o | Testing, verification | @clientflow_qa |

**Future agents to add:**
- Project Manager Agent (task tracking)
- Finance Agent (invoices, payments)
- Legal Agent (contracts, compliance)

---

## 9. BENGALI CONTEXT

This warehouse serves a **Bangladesh-based software company** (Client Flow BD).

**Language rules:**
- AI assistant always speaks Bangla (professional, natural)
- Technical terms in Bangla transliteration (এপিকেআই = API, ডকার = Docker)
- CEO addresses AI as "Manager"; AI addresses CEO as "Boss"

**Business type:** Software company (NOT digital marketing like Farhan)
- Clients: Software projects, SaaS, mobile apps, e-commerce
- Not YouTube sponsor tracking → SaaS/Software competitor tracking
- Not SEO/Ads services → Custom software development

---

## 10. INSPIRATION SOURCE

This design is inspired by **Khalid Farhan's Warehouse** (Bangladeshi YouTuber) but with:
- ✅ Same architecture (9 sections, AI-driven, personal hub)
- ✅ Same philosophy (AI builds, CEO uses)
- ✅ Same style (Neo-Brutalism, thick borders, hard shadows)
- ❌ Different colors (Coral-Amber-Gold instead of Farhan's Pink-Yellow)
- ❌ Different business context (Software company vs Digital Marketing)
- ❌ Client Flow BD-specific data (real BD clients, SaaS stack tags)

---

## 11. HOW TO EXTEND

### Add a New Section
1. Add nav button in `#nav`
2. Add new `<section class="page" id="page-xxx">`
3. Use existing card/header/tag classes
4. JS already handles navigation automatically

### Change Colors
1. Edit `:root` CSS variables at top of file
2. All components use variables automatically

### Add New Data
- Currently: Edit HTML manually
- Future (Phase 2): Via localStorage UI
- Future (Phase 4): Via Agent API calls

---

## 12. SECURITY NOTES

- No authentication currently (Phase 7 pending)
- All data local (no server, no cloud)
- Future: Add password auth before hosting publicly
- Vault for any future API keys: Hermes Vault (never hardcode)

---

## 13. CONTACT / OWNER

- **Owner:** Asif Khan — CEO of Client Flow BD
- **AI Manager:** SenseNova 6.8 Flash Lite via Hermes Agent
- **Location:** `/home/asif-khan/warehouse.html`
- **Last Updated:** 2026-09-25

---

*This document is a living reference. Update as the warehouse evolves. New AI agents reading this file should understand the full system, design language, and roadmap.*
