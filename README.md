# Legend Releases

Release artifacts and the auto-update endpoint for Legend — a fast, keyboard-native
markdown editor that treats every file the same.

Downloads live under [Releases](https://github.com/MortalPastry/legend-releases/releases).

## Report a bug or request a feature

File an issue here — [New issue](https://github.com/MortalPastry/legend-releases/issues/new/choose).
There are templates for bugs, feature requests, and questions. Inside Legend, the
**Report a bug** command (open the command palette and type "report") pre-fills the
version, OS, and vault-size for you.

Prefer email? Write to **support@alegend.io**.

## FAQ

**What is Legend?**
A fast, keyboard-native markdown editor. It opens a folder of `.md` files, indexes the
whole vault, and gets out of your way — no accounts, no formats it imposes, no opinion
about what your notes are for. Everything stays as plain `.md` files on disk.

**How do I install it?**
Download the latest build from [Releases](https://github.com/MortalPastry/legend-releases/releases)
and run it. (Detailed per-platform steps land here as the beta builds ship.)

**Does it change my files?**
No. Legend opens your vault in place and never rewrites, renames, or deletes your files.
It keeps its own derived index (search, backlinks) in a `.legend/` folder it can rebuild
from scratch at any time — that cache is never the source of truth; your `.md` files are.

**Can I open my existing Obsidian vault?**
Yes — point Legend at the folder and it opens as-is. `[[wiki-links]]`, callouts
(`> [!NOTE]`), and embeds render. Nothing in `.obsidian/` is touched.

**The keyboard basics?**
- `Ctrl+P` — go to a file by name
- `Ctrl+Shift+F` — full-text search
- `Ctrl+B` — toggle the file browser
- `Ctrl+N` — new file in the current folder
- `Ctrl+E` — toggle source / live preview
- `Ctrl+Shift+P` — command palette (every command, searchable)

**How do I report a bug?**
See the section above. The in-app **Report a bug** command is the fastest path.

---

The Legend source is not hosted here.
