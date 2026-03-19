# AI Learning Notes

activate environment - conda activate {ai} - environment name

## Phase 1 — Math Foundations + Python for AI

### Week 1 — NumPy & Linear Algebra

#### Day 1 — Arrays, Shapes, Dot Product, Reshape, Slicing

- **numpy.array()** — Creates an array (like a list, but built for fast math operations)
- **Multi-dimensional arrays** — Arrays can have rows and columns, just like a table. e.g. `[[1,2,3],[4,5,6]]` is 2 rows, 3 columns
- **shape** — Tells you the size of an array. `(3, 4)` means 3 rows and 4 columns
- **Dot product** — Multiply two arrays element by element, then add everything up. e.g. `[1,2,3] · [4,5,6] = (1×4)+(2×5)+(3×6) = 32`. This is the core operation inside every neural network
- **Matrix multiply** — Extends dot product to 2D arrays. Every neural network layer does this: `output = input · weights`
- **Reshape** — Change the shape of an array without changing its data. e.g. 6 numbers → 2 rows of 3. Use `-1` to let NumPy figure out the size automatically
- **Slicing** — Extract parts of an array. `m[0, :]` = first row, `m[:, 0]` = first column, `m[1:, 2:]` = from row 1 onwards, column 2 onwards
- **In ML:** Data is always stored as arrays. 100 images of 784 pixels = shape `(100, 784)`

#### Day 2 — Matplotlib & Broadcasting

- **Matplotlib** — Library for plotting graphs and visualizing data
- **plt.plot(x, y)** — Draws a line chart. Add `plt.title()`, `plt.xlabel()`, `plt.ylabel()` to label it
- **np.linspace(start, stop, num)** — Generates `num` evenly spaced numbers between `start` and `stop`. e.g. `np.linspace(0, 1, 5)` → `[0, 0.25, 0.5, 0.75, 1.0]`. More points = smoother curves
- **Why it matters:** Loss functions in ML are curves (like y = x²). Visualizing them helps you understand how training works
- **Broadcasting** — NumPy can do math between arrays of different shapes automatically. e.g. adding `[10,20,30]` to a matrix applies it to every row. No loops needed. Used heavily in feature scaling
- **Common ML curve shapes:**
  - x² (U-shape) → loss functions. Training = finding the bottom of this cup
  - |x| (V-shape) → MAE loss function
  - x³ (S-shape) → similar to activation functions like tanh used in neural networks

## Phase 2 — Machine Learning Fundamentals

<!-- Add your notes here -->

---

## Phase 3 — Deep Learning with PyTorch

<!-- Add your notes here -->

---

## Phase 4 — NLP & Transformers

<!-- Add your notes here -->

---

## Phase 5 — Large Language Models

<!-- Add your notes here -->

---

## Phase 6 — Projects & Capstone

<!-- Add your notes here -->

---

## Key Concepts (Quick Reference)

<!-- Jot down concepts you want to remember quickly -->

---

## Questions / Things to Revisit

<!-- Note down anything you're unsure about -->
