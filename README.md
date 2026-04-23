# Truc4

Full-stack software developer obsessed with game design, language implementation, and low-level systems. Spend my free time building engines, experimenting with programming languages, and exploring data-oriented design.

## Projects

### [arche](https://github.com/Truc4/arche)

**Data-Oriented Programming Language**

- Think about data as groups, not objects
- Columnar arrays with fixed, static memory allocation, no dynamic growth
- No handle/pointer nesting in data structures; everything laid out flat and explicit
- Prioritizes fast, predictable memory access over having a minimal memory footprint

Currently in alpha with lexer, parser, semantic analysis, and LLVM code generation.

---

### [oflecs](https://github.com/Truc4/oflecs)

**Flecs Bindings for Odin**

Native Flecs ECS framework bindings for the Odin programming language. Uses odin-c-bindgen for low-level binding generation paired with a handwritten wrapper layer that emphasizes data-oriented design over object-oriented patterns. Explicit world ownership through struct-based handles, automatic component registration on first use, and minimal hidden state.

---

### [contextual-resume-renderer](https://github.com/Truc4/contextual-resume-renderer)

**Automated Resume & Cover Letter Tailoring Tool**

Template-based system that filters and reorganizes your existing resume content to match specific job postings. Eliminates manual copy-paste work by automatically selecting relevant material, reordering sections, and generating polished PDFs.

**What it does:**

- Parse job requirements into importance-weighted categories
- Filter pre-written resume content against requirements
- Generate tailored PDFs via deterministic Jinja2 templates and CSS

**What it doesn't do:**

- Does not generate or rewrite your text (you provide source material)
- No LLMs or generative models involved

---

### [dynamic-relationship-chart](https://github.com/Truc4/dynamic-relationship-chart)

**Interactive Relationship Visualization Web App**

Force-directed graph visualization (Cytoscape.js) for exploring networks of people and connections. Supports custom relationship types, real-time layout control, bulk image uploads, and optional Discord guild integration.

**Key Features:**

- Drag-to-pan, zoom, and drag images directly onto nodes
- Toggle visibility by relationship type or group
- Search with automatic dimming of non-matches
- Export as PNG/JPEG
- Discord bot integration (optional): auto-populate people from server members

---

### [gaming-degree-site](https://github.com/Truc4/Gaming-Degree-Site)

**Game Achievement Tracker & Novelty Degree Generator**

Track your game accomplishments and earn a novelty "gaming degree" that certifies you've played the essential titles. Playful take on gamification and achievement systems.
