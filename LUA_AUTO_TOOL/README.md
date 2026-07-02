═══════════════════════════════════════════════════════
                🚀 HACKER420 AUTO LUA TOOL
          ELITE LUA INJECTOR & SMART MERGER v2
          📞 Contact: 03313553052
          👨‍💻 Credit: @hacker420official
═══════════════════════════════════════════════════════

🔥 WHAT IS THIS?
This is a professional-grade Lua injection and merging tool
designed for PUBG Mobile modding. It understands function
structure, handles nested blocks, fixes syntax issues, and
safely merges code from .txt snippets or other .lua files
into your target files — WITHOUT breaking existing logic.

✨ MAIN FEATURES
• 🔐 Online Login System – Validate your key via GitHub.
• 🧠 Smart PUBG Feature Injection – Auto-detects NetworkRPC
  and DeclareFeature modules, adds core code + tick hooks.
• ⚙️ Generic Snippet Inject – Works with any Lua snippet.
• 📁 Merge Lua Functions – Import specific functions from
  other .lua files into your target.
• 🔍 Deep Syntax Analysis – Catches real errors, not just
  strings.
• ✅ Auto Safe Fix – Automatically adds missing `end` blocks.
• 📊 Batch Scan – Check all files in all folders at once.
• 📄 Generate Reports – Save analysis as .md file.

═══════════════════════════════════════════════════════

📂 FOLDER STRUCTURE (Auto-created)
~ / lua_editor /
├── original/      ← Put your TARGET .lua files here
├── code/          ← Put your PUBG FEATURE .txt snippets here
├── lua_code/      ← Put your SOURCE .lua files here (for merging)
├── backups/       ← Auto-backups before saving
└── reports/       ← Generated analysis reports

═══════════════════════════════════════════════════════

📋 MENU OPTIONS BREAKDOWN

[1] SMART INJECT (PUBG Feature)
    • Select a .lua target (from original/)
    • Select a .txt snippet (from code/)
    • Auto-detects if it's a PUBG feature (CONFIG + OnTick).
    • Injects core code at the right place (before class).
    • Adds Tick hook in ReceiveTick or StartAdvancedSystems.
    • Adds DeclareFeature entry automatically.

[2] INJECT ALL .txt FEATURES
    • Picks ONE target .lua file.
    • Scans ALL .txt files inside code/.
    • Merges every valid PUBG feature into that target.
    • Saves time for bulk updates.

[3] ANALYZE FILE
    • Check syntax, function count, block closure.
    • Shows detailed warnings (empty functions, missing self).
    • Optional PUBG-style hints (super calls, etc.).

[4] MERGE LUA FUNCTIONS ✨ NEW
    • Select a target .lua (from original/).
    • Select a source .lua (from lua_code/).
    • Displays a list of ALL functions in the source file.
    • You select which ones to import (e.g., 1,3,5 or 'all').
    • Handles conflicts (append, prepend, replace, skip).
    • Injects the ENTIRE function code (from `function` to `end`).

[5] BATCH SCAN
    • Scans original/, code/, and lua_code/ simultaneously.
    • Shows file type, kind (PUBG/snippet/etc.), and status.
    • Identifies broken syntax files.

[6] FIX SYNTAX ONLY (Safe)
    • Analyzes the file.
    • Adds missing `end` statements safely.
    • Does NOT modify logic, only balances blocks.

[7] PREVIEW INJECT (Dry Run)
    • Same as Option 1, but only shows the result.
    • Does NOT save to file. Perfect for testing.

[8] GENERATE REPORT
    • Creates a detailed .md report of the selected file.
    • Contains syntax status, all functions, and issues.

[9] FILE STRUCTURE / FOLDERS
    • Displays a beautiful tree view of your lua_editor folder.

[0] HELP
    • Shows quick reference for directives and PUBG logic.

[x] EXIT
    • Close the tool.

═══════════════════════════════════════════════════════

🛠️ REQUIREMENTS & INSTALLATION

Make sure Python 3.8+ is installed on your system.

▶️ Install required Python packages:
─────────────────────────────────
pip install rich
─────────────────────────────────

(Optional: If you want syntax checking via `luac`, ensure
Lua is installed. The tool has a fallback parser anyway.)

═══════════════════════════════════════════════════════

▶️ RUN COMMAND
─────────────────────────────────
[👈 cd LUA_AUTO_TOOL
chmod +x loader
./loader]
─────────────────────────────────

📝 FIRST TIME LOGIN:
The tool will ask for a KEY on startup. 
key 🗝️ = @hacker420official

⚠️ IMPORTANT:
• Always back up your files (tool does it automatically).
• If a function already exists, you'll be asked how to merge.
• Syntax errors are shown BEFORE saving. Review carefully.

─────────────────────────────────────────────────────────
         ❤️ Made with precision by @hacker420official
                 Join the Elite Modding Circle
═══════════════════════════════════════════════════════
