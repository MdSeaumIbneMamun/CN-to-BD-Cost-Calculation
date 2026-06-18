========================================================================
🚢 CN ➤ BD SHIPPING COST CALCULATOR & LEDGER DASHBOARD
========================================================================

[DEVELOPMENT MODEL]
⚡ Project Type   : Vibe Coding Project
🤖 AI Model       : Gemini 3.1 Flash
💡 Framework      : Asynchronous AI-Assisted Prompt Engineering
📱 Responsiveness : Made for Desktop screen only.

[CREATOR INFORMATION]
👤 Developer    : Md. Seaum Ibne Mamun
🏫 Institution  : Dhaka International University (DIU)
🎓 Department   : Bachelor of Science in Computer Science and Engineering

[OFFICIAL REPOSITORY]
🌐 Link         : github.com/MdSeaumIbneMamun/CN-to-BD-Cost-Calculation

========================================================================
1. PRODUCT ARCHITECTURE & OVERVIEW
========================================================================
The CN-to-BD-Cost-Calculation platform is a production-grade, high-performance
standalone desktop logistics application engineered to handle complex cross-border
supply chain financial matrices between China (CN) and Bangladesh (BD).

By binding a modern React frontend with a secure, lightweight Tauri v2 Rust runtime
shell environment, this application bypasses traditional browser sandbox constraints.
This unlocks low-overhead, client-side spreadsheet compilation alongside secure, direct
operating system native file system input/output (IO) architectures.

The interface is built completely around Google's Material 3 Expressive design specifications,
enforcing highly responsive structural layouts, fluid canvas-scaling transformations,
and smooth desktop transitions.

========================================================================
2. CORE FEATURES & FUNCTIONAL MATRIX
========================================================================
* CLIENT-SIDE EXCEL INGESTION & PIPELINES
  Leverages SheetJS (XLSX) processing layers to seamlessly parse and map uploaded
  .xlsx, .xls, or .csv shipment ledger data using client-side streaming data buffers.

* REAL-TIME HEADER VALIDATION SENSORS
  Scans uploaded document structures instantly to cross-examine column criteria. 
  Throws a robust "Upload Blocked" UI modal if mandatory headers are missing, 
  preventing corrupted matrices from polluting active state scopes.

* ON-DEMAND SPREADSHEET COMPILERS
  Generates clean, structure-perfect blank ledger templates or pre-populated 
  sample workbooks dynamically from pure memory tables—removing the need for 
  hardcoded static file resources inside the production package build.

* MULTI-TIER LANDED COST CALCULATION ENGINES
  Synchronizes calculation workflows to process baseline parameters concurrently without drift:
  - Real-time conversion mapping for foreign to local currency nodes (CNY → BDT).
  - Item mass metrics tracking (Weight in KG combined with freight coefficients).
  - Multi-layered logistics layers (Base Cost, Customs Duties, Insurance, Handling Fees).
  - Visual color thresholds for live profit margin yield markers.

* TAURI V2 DESKTOP WRAPPER OPTIMIZATIONS
  - Native Frame Control: Retains native Minimize and Close operational buttons 
    while graying out/locking the Maximize mechanism to keep layouts crisp.
  - Geometry Isolation: Application boots strictly into a prioritized full-screen 
    maximized state while fully restricting manual window resizing.
  - Sandboxed Path System: Transforms compiled zip/xlsx data blocks into binary arrays 
    and bridges them out of the container to spawn native Windows "Save As" file prompts.

========================================================================
3. TECHNICAL SPECIFICATIONS STACK
========================================================================
* Shell Container   : Tauri v2 Core Architecture (Rust Kernel Layer)
* Frontend Engine   : React.js (Functional components, Hooks context, Memoized masks)
* Build Toolchain   : Vite Development Server & Module Resolution Bundle
* Core Binary Parser: SheetJS Core Library Engine
* Visual System     : Google Material 3 Expressive Structural System Guidelines

========================================================================
4. CONFIGURATION COMPONENT ARCHITECTURE
========================================================================

--- [A] WINDOW ENVIRONMENT STATE (src-tauri/tauri.conf.json) ---
{
  "productName": "CN-BD Shipping Calculator",
  "version": "0.1.2",
  "identifier": "com.shippingcalculator.app",
  "app": {
    "windows": [
      {
        "title": "CN ➤ BD Shipping Dashboard",
        "resizable": false,
        "maximized": true,
        "decorations": true,
        "maximizable": false,
        "fullscreen": false
      }
    ]
  }
}

--- [B] PRIVILEGED CAPABILITIES ACCESS (src-tauri/capabilities/default.json) ---
Restricts system access directories recursively strictly to native folder boundaries 
to prevent malicious runtime exploits while enabling secure local file printing:
* dialog:default   -> Authorizes custom system save-file popup selectors.
* fs:allow-write   -> Authorizes binary array file streaming directly to disk.
* Directory Scopes -> Enforced exclusively recursively inside:
                      - $DOWNLOADS/**
                      - $DOCUMENT/**
                      - $DESKTOP/**

========================================================================
5. LOCAL ARCHITECTURE DEVELOPMENT & INSTALLATION FLOW
========================================================================
Prerequisites: Node.js (v18+), Rustup Engine Toolchain, C++ Build Tools Workload.

1. Clone Vibe Coding Repo:
   git clone https://github.com/MdSeaumIbneMamun/CN-to-BD-Cost-Calculation.git
   cd CN-to-BD-Cost-Calculation

2. Fetch Frontend Package Bundles:
   npm install

3. Run Hot-Reload Dev Interface:
   npx tauri dev

4. Compile Production Single Executable Application (.exe):
   npx tauri build

* Output distribution setup path:
📁 src-tauri/target/release/bundle/nsis/

========================================================================
6. COPYRIGHT REGISTRY & CODE LICENSE
========================================================================
Distributed completely under the open-source MIT License terms. This logistics 
ledger platform engine is open, free to copy, clone, fork, or redistribute 
to fit global multi-currency supply chain analytics frameworks.
========================================================================
