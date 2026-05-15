# DSA Forge ⚡

> **Interactive Data Structures & Algorithms learning platform** — visualise, step through, and master every major pattern used in tech interviews.

🌐 **Live demo:** `https://<your-username>.github.io/dsa-forge/`

---

## ✨ What's inside

| Topic | Patterns covered |
|---|---|
| **Arrays & Strings** | Two Pointers, Sliding Window, Prefix Sum, Kadane's |
| **Sorting Algorithms** | Bubble, Selection, Insertion, Merge, Quick, Heap — all animated |
| **Trees & BST** | Pre/In/Post-order, BFS, BST insert & search |
| **Graphs** | BFS, DFS, Dijkstra, Topological Sort, Union-Find |
| **Dynamic Programming** | Memoization, 0/1 Knapsack, LCS, Coin Change |
| **Linked Lists** | Reversal, Floyd's Cycle, Find Middle, Merge Sorted |
| **Stack & Queue** | Valid Parens, Monotonic Stack, Sliding Window Max |
| **Binary Search** | Classic, First & Last Position, Rotated Array, Answer-Space |

- **40+ famous LeetCode problems** with full approach explanations
- **Step / Play / Reset** controls on every visualization
- **100% static** — no server, no build step, no dependencies

---

## 🚀 Deploy to GitHub Pages in 3 steps

### Step 1 — Create a new repository

```bash
# On GitHub, create a new repo called:  dsa-forge
# Then clone it locally:
git clone https://github.com/<your-username>/dsa-forge.git
cd dsa-forge
```

### Step 2 — Add the file

Copy `dsa-forge.html` into the repo root and rename it `index.html`:

```bash
cp dsa-forge.html index.html
git add index.html
git commit -m "feat: initial DSA Forge SPA"
git push origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main`, Folder: `/ (root)`
5. Click **Save**

Your site will be live at:
```
https://<your-username>.github.io/dsa-forge/
```
*(usually takes 1–2 minutes to deploy)*

---

## 🗂 Repo structure

```
dsa-forge/
├── index.html      ← the entire app (single file, self-contained)
└── README.md
```

That's it. One file. Zero dependencies. Zero build step.

---

## 🛠 Local development

No build tools needed. Just open the file directly:

```bash
# Option 1 — open directly in browser
open index.html

# Option 2 — serve with Python (avoids any CORS issues)
python3 -m http.server 8080
# then visit http://localhost:8080
```

---

## 🔗 URL routing

The app uses **hash-based routing** (`#arrays`, `#graphs`, etc.) so every page is deep-linkable and browser back/forward works correctly.

```
https://yourname.github.io/dsa-forge/#arrays
https://yourname.github.io/dsa-forge/#graphs
https://yourname.github.io/dsa-forge/#dp
https://yourname.github.io/dsa-forge/#sorting
```

---

## 📸 Pages

| Page | URL hash |
|---|---|
| Home | `#home` |
| Arrays & Strings | `#arrays` |
| Trees & BST | `#trees` |
| Graphs | `#graphs` |
| Dynamic Programming | `#dp` |
| Sorting | `#sorting` |
| Linked Lists | `#linkedlist` |
| Stack & Queue | `#stack-queue` |
| Binary Search | `#binary-search` |

---

## 🤝 Contributing

Pull requests welcome! The entire app is in `index.html` — each topic's HTML, CSS, and JS is clearly commented with section headers like `/* ===== ARRAYS ===== */`.

---

## 📄 License

MIT — free to use, share, and modify.

---

*Built with vanilla HTML, CSS, and JavaScript. No frameworks. No bundlers. Just the web.*
