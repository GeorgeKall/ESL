## ESL Project Repo

### Setup

#### 1. Clone the repository

```bash
git clone <https://github.com/GeorgeKall/ESL.git>
cd <ESL>
```

#### 2. Create a virtual environment

If you don't already have a virtual environment for this project:

```bash
python -m venv .venv
```

#### 3. Activate the virtual environment

**macOS / Linux:**

```bash
source .venv/bin/activate
```

**Windows (PowerShell):**

```powershell
.\.venv\Scripts\Activate.ps1
```

#### 4. Install dependencies

With the virtual environment activated, install the required packages:

```bash
pip install -r requirements.txt
```

#### 5. Start Jupyter

```bash
jupyter notebook
```

Or open the project in VS Code and select the `.venv` Python interpreter as your notebook kernel.
