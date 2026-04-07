# Running main.ipynb

Quick instructions to run the notebook locally.

Prerequisites:
- Python 3.8 or newer
- Git (optional)

Recommended (create isolated env):

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

PyTorch note:
- PyTorch binaries vary by OS and CUDA support. For most macOS users (CPU-only), you can use:

```bash
pip install --index-url https://download.pytorch.org/whl/cpu torch torchvision
```

If you need GPU/CUDA support, follow the selector and install command at https://pytorch.org.

Running the notebook:

```bash
jupyter notebook main.ipynb
# or
jupyter lab
```

Open `main.ipynb` in your browser or directly in VS Code (opens with the Jupyter extension).

