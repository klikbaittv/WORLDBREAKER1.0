# 01_how_to_use.txt
# version: 1.1.0
# spellbook_for_writers — onboarding guide

================================================================
WELCOME TO SPELLBOOK FOR WRITERS
================================================================

No setup. No code. No installation. Just files and your AI.

This is a portable writing companion system — plain text files
that turn any AI chat into a structured creative workspace.
Drop some files in, start writing. That's it.

================================================================
WHAT'S IN THE FOLDER
================================================================

  00_spine_of_the_world.txt   The rulebook. The AI reads this first.
                               Everything else defers to this file.

  01_how_to_use.txt           This file. Start here.

  02_latest_save.txt          Your most recent save, always up to date.
                               Load this to catch the AI up instantly.

  03_characters.txt           Your character registry.
                               Add characters by appending at the bottom.

  04_world_notes.txt          Your world: setting, history, atmosphere.
                               Append-only — the history stays intact.

  05_lexicon.txt              Your world's vocabulary.
                               Terms, places, slang, named things.

  06_story_arc.txt            Your plot. Acts, chapters, open threads.

  07_ledger.txt               Living canon document. NOT append-only.
                               Edit freely. Tracks current world state:
                               who's alive, what's true, what has changed.

  tree.txt                    The project map. Update it when you add files.

  summons/                    All writing companion personas live here.
  ├── tree.txt                 Summons roster. Add new summons here.
  ├── the_archivist.txt        Default companion. Ancient, precise.
  └── orc_peon.txt             Alternate companion. Simple, loyal, fun.

  save_files/                 All saves live here.
  ├── save_template.txt        Blank template. The AI fills this on "save."
  └── save_file<N>.txt         Your numbered saves.

================================================================
HOW TO START A SESSION
================================================================

OPTION A — Quick start (minimal):
  Load these 3 files into your AI chat:
    1. 00_spine_of_the_world.txt
    2. A summon from summons/ (e.g. the_archivist.txt)
    3. 02_latest_save.txt

  Then say: "We're continuing [project name]. Here's where we left off."
  The AI will read the files and pick up from your last save.

OPTION B — Full context (recommended):
  Load all root .txt files + your chosen summon from summons/.
  The AI will have access to your full world: characters, world notes,
  lexicon, story arc, and the ledger.

HOW TO LOAD FILES INTO YOUR AI:
  - Claude: use the paperclip / attachment button to upload files
  - ChatGPT: use the attachment button (file upload)
  - Gemini: use the file attachment option
  - Local model (LM Studio, etc.): paste file contents directly
  You can also paste the contents of any file directly into the chat.

================================================================
HOW TO SAVE
================================================================

Just say one of these:
  "save"
  "save my progress"
  "save file"
  "write a save"

The AI will output a completed save block titled save_file<N>.txt.

YOU DO TWO THINGS:
  1. Copy the save block and save it as that filename in your save_files/ folder.
  2. Replace 02_latest_save.txt with the second block the AI outputs.

That's it. Your progress is saved.

================================================================
HOW TO CAMP
================================================================

Camp = end of session. Use it when you're done for the day.

Say one of these:
  "camp"
  "camp at the spine of the world"
  "set up camp"

The AI will:
  1. Write a final save (includes a session summary)
  2. Say: "Camp is set at the spine of the world."

You save the file it outputs, and the session is sealed.
Next time you open a session, load your files and pick up exactly where you left off.

================================================================
HOW TO UPDATE YOUR WORLD FILES
================================================================

APPEND-ONLY FILES (03 through 06):
  These files only grow downward. Old entries stay.
  Never delete or edit above the last entry.

  You can tell the AI:
    "add a character: [name and description]"
    "add to world notes: [something about your world]"
    "add to lexicon: [term — definition]"
    "update story arc: [chapter notes or plot development]"

  The AI will output the new entry. You paste it at the bottom of the right file.

THE LEDGER (07_ledger.txt):
  This is a living document — edit it freely at any time.
  It tracks current world canon: who's alive, what's true, what has shifted.
  Unlike the append-only files, old entries here can be updated or removed.
  Use it to keep a clean picture of your world's current state.

================================================================
SUMMONS
================================================================

Your default companion is The Archivist (summons/the_archivist.txt).
Ancient-feeling, precise, unhurried. Treats your world seriously.

You can customize any summon by appending to the bottom of its file.
You can create new summons — for different writing modes or as characters:
  - A no-nonsense editor persona
  - A brainstorm partner who talks fast
  - A specific character who keeps you in-world voice
  Copy the format from any file in summons/, save the new file there,
  and add it to summons/tree.txt.

================================================================
GLOSSARY
================================================================

  Spine         00_spine_of_the_world.txt — the authority file.
                The AI reads this first. Rules live here.

  Summon        A persona file. Tells the AI who to be this session.
                All summons live in summons/. Default: the_archivist.txt.

  Save          A snapshot of your project state. Numbered and dated.
                Triggered by saying "save."

  Camp          End of session ritual. Writes a save with session summary.
                Triggered by saying "camp."

  Append-only   A file that only grows downward. Old entries stay.
                Never delete or edit above the last entry. (Files 03–06)

  Ledger        07_ledger.txt. Living canon document. Freely editable.
                Tracks current world state — not a history, a snapshot.

  Plain mode    Drops the AI persona. Direct and technical.
                Triggered by saying "plain mode."

================================================================
TIPS
================================================================

  - You don't have to load all files every time.
    A quick brainstorm session? Just load the spine + summon.
    Full writing session? Load everything.

  - The AI doesn't have persistent memory between conversations.
    Your files ARE the memory. The more you keep them updated,
    the better the AI can help.

  - If the AI seems to forget something, paste the relevant file content
    directly into the chat. That always works.

  - Saves are cheap. Camp often.

  - Keep tree.txt updated. The AI uses it to understand your structure.
    When you add files or folders, update the tree.

================================================================
