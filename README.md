# DFE-design
This repository contains the design implementation of a multistage Digital Front End (DFE) for the SI-Clash competition, powered by IEEE SSCS AUSC.

## Project Structure

```
DFE-design/
│
├── RTL/                      # RTL source code (SystemVerilog/Verilog/VHDL)
├── testbench/                # Testbench and verification scripts
├── python/                   # Python reference models and analysis
├── .gitignore
└── README.md
```

---

## Setup Branching Strategy

- **Main branch:** `main` — stable and deployable project version.
- **Development branch:** `develop` — integrate feature branches here.
- **Feature branches:** `feature/<feature-name>` — for individual tasks or components.

## Team Workflow: Step-by-Step Instructions

### 1. Clone the Repository

```bash
git clone <repo-url>
cd DFE-design
```

### 2. Checkout the Latest Develop Branch

```bash
git checkout develop
git pull origin develop
```

### 3. Create Your Feature Branch

Choose your assigned feature and create a branch using one of these names:

- feature/cic-decimator
- feature/fractional-decimator
- feature/notch-filter
- feature/python_golden_model
- feature/testbench

Create and switch to your feature branch:
```bash
git checkout -b feature/<feature-branch-name>
```

### 4. Work on Your Feature

- Add code, modules, scripts, or docs for your assigned block.
- Stage and commit your changes regularly:
  ```bash
  git add .
  git commit -m "Describe your contribution"
  ```

### 5. Push Your Branch to the Remote Repository

```bash
git push origin feature/<feature-branch-name>
```

### 6. Open a Pull Request (PR) on GitHub

- Go to the repository on GitHub.
- Click "Compare & pull request" for your branch.
- Set the base branch as develop and compare branch as your feature branch.
- Add a clear title and description for your changes.
- Request a review.

## Best Practices

- **Work in your assigned branch only:** Do not mix work across branches.
- **Use clear commit messages and PR descriptions.**
---

