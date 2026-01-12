# Leetcode Notebook Tutorials

A lightweight collection of Jupyter notebooks that walk through common data structures and algorithms (DSA) and how they map to LeetCode-style problems. Each notebook pairs concepts with worked examples and practice prompts so you can build intuition and pattern recognition.

## Repo Layout

```
.
├── heap/
│   └── heap_intro.ipynb
├── searching/
│   ├── backtracking/
│   │   └── backtracking_intro.ipynb
│   └── dfs/
│       └── dfs_intro.ipynb
└── stack_queue/
    ├── queue_intro.ipynb
    └── stack_intro.ipynb
```

## Getting Started

1. **Clone the repo**
   ```bash
   git clone <your-fork-or-repo-url>
   cd Leetcode_starter
   ```

2. **Create and activate a virtual environment (recommended)**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   # .venv\Scripts\activate   # Windows (PowerShell)
   ```

3. **Install Jupyter**
   ```bash
   pip install jupyter
   ```

4. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

## Notebooks

- **Heap**
  - `heap/heap_intro.ipynb`

- **Searching**
  - Backtracking: `searching/backtracking/backtracking_intro.ipynb`
  - Depth-First Search (DFS): `searching/dfs/dfs_intro.ipynb`

- **Stack & Queue**
  - Stack: `stack_queue/stack_intro.ipynb`
  - Queue: `stack_queue/queue_intro.ipynb`

## Suggested Learning Path

If you are new to DSA, consider this progression:

1. Stack → Queue
2. DFS
3. Backtracking
4. Heap

## Contributing

If you want to add a new tutorial notebook:

1. Create a new folder under the relevant topic (or create a new topic folder).
2. Name the notebook with a clear `*_intro.ipynb` or `*_tutorial.ipynb` suffix.
3. Add the notebook to the **Repo Layout** and **Notebooks** sections above.

## License

Add a license if you plan to share this repository publicly.
