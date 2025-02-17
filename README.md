# Artificial Junior AI Engineer Assessment

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/StanKarz/artificial_assessment
cd artificial_assessment
```

### 2. Install UV (if not already installed)
```bash
pip install uv
```

### 3. Install Dependencies with UV
```bash
uv pip install notebook
uv pip sync requirements.uv
```

### 4. Set Up the Jupyter Kernel
Once all dependencies are installed, install the current environment as a Jupyter kernel:

```bash
uv pip install ipykernel
python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
```

### 5. Run the Jupyter Notebook
Launch the Jupyter Notebook:
```bash
jupyter notebook
```

In the Jupyter interface, go to **Kernel > Change Kernel** and select `Python (myenv)` to use the correct environment.

---

### Environment Files
- `requirements.uv`: Lock file for UV (ensures exact same dependencies).


