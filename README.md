# Mixi-Plugins ✦˖ ִֶָ

✦ˎˊ˗ a cozy collection of plugins for modified Discord clients ദ്ദി˶ᵔ ᵕ ᵔ˶)

Made for [TestCord](https://github.com/x2b1/TestCord) (and other Vencord-based clients).

---

## Plugins

### 🖼️ SaveUserGifs

> Right-click any user to save all the GIFs they've sent to your favorites.

**Features:**
- Scans a user's messages for GIFs from Tenor, Giphy, Klipy, and uploaded `.gif` files
- Saves GIFs to your favorites **in real-time** as they are found
- Skips GIFs you already have saved automatically
- Stop the scan at any time from the right-click menu — GIFs found so far are already saved
- Export to JSON file, add to favorites, or both

**Settings:**
| Setting | Description |
|---|---|
| Scan Mode | Scan only the current channel or the entire server |
| Save Mode | Export to JSON, add to favorites, or both |
| Max Messages | Maximum number of messages to scan |

> ⚠️ Due to Discord's search API being non-deterministic, some GIFs may be missed on the first scan. Simply run it again on the same user — already saved GIFs will be skipped automatically.

---

### 📦 GifTransfer

> Export and import all your favorite GIFs between accounts using a JSON file.

Adds **Export**, **Import**, and **Verify** buttons to the GIF picker tab bar.

**Features:**
- 📤 **Export** — saves all your favorite GIFs to a `.json` file
- 📥 **Import** — loads GIFs from a `.json` file, skips duplicates automatically
- 🔍 **Verify** — checks which GIFs from a file are missing from your favorites

**Settings:**
| Setting | Description |
|---|---|
| Skip Duplicates | Skip GIFs already in your favorites when importing |
| Delay Between Imports | Wait time between each import (ms) — prevents Discord rate limits |

> ⚠️ If not all GIFs get imported, increase the **Delay Between Imports** setting and press Import again — it will skip already imported GIFs and only retry the missing ones.

---

## Installation

These plugins are included in [TestCord](https://github.com/x2b1/TestCord). To install TestCord, follow the instructions in that repository.

---

## Author

Made with ♡ by [Mixiruri](https://github.com/Mixiruri)
