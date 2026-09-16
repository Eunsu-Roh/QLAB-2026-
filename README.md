## 🚀 Quick Start / How to Run

Follow the steps below in your terminal to set up the environment and run the pipeline:

### 1. Create and Activate Conda Environment (Recommended)
```bash
conda create -n eunsu python=3.11
conda activate eunsu
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Training and Pipeline
```bash
python src/main.py
```

### 4. Verification and Submission Generation
- Once training on the 16 samples completes, **two evaluation plot windows** will pop up.
- **Close both plot windows** to allow the script to finalize and generate `submission.json`.
- Verify the generated `submission.json` file in your project directory (or `outputs/` folder).
