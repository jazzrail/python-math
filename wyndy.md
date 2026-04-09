Good evening, Alan! You can install Jupyter Notebooks without Anaconda by using Python's package manager, `pip`. Here’s a step-by-step guide to get you started:

### 1. **Install Python and Pip**

Since you're on macOS, Python is likely already installed, but it’s a good idea to ensure you have an updated version and `pip` (the Python package installer).

- Check your Python version:

  ```bash
  python3 --version
  ```

- If Python isn’t installed, you can install it via Homebrew:
  ```bash
  brew install python
  ```

### 2. **Install Jupyter Using Pip**

Once you have Python and `pip` ready, you can install Jupyter directly:

```bash
pip3 install jupyter
```

### 3. **Run Jupyter Notebook**

After installing, you can start Jupyter Notebook by running:

```bash
jupyter notebook
```

This will open Jupyter in your default web browser. From here, you can create and work on your notebooks.

### 4. **Optional: Create a Virtual Environment (Recommended)**

To keep your projects clean and avoid dependency issues, it’s good to use a virtual environment:

- Create a virtual environment in your project folder:

  ```bash
  python3 -m venv myenv
  ```

- Activate the virtual environment:

  ```bash
  source myenv/bin/activate
  ```

- Install Jupyter inside the virtual environment:

  ```bash
  pip install jupyter
  ```

- Run Jupyter from the virtual environment:
  ```bash
  jupyter notebook
  ```

This way, the Jupyter installation and its dependencies won’t interfere with other projects on your system.

Let me know if you need any further assistance!

Yes, that's correct! Before running `jupyter notebook`, you'll need to activate the virtual environment (`myenv`) every time you work on that project. Here's how:

1. **Activate the Virtual Environment**:

   - Navigate to your project directory (where you created `myenv`):

     ```bash
     cd path/to/your/project
     ```

   - Activate the environment:
     ```bash
     source myenv/bin/activate
     ```

2. **Run Jupyter Notebook**:
   Once the virtual environment is active (you’ll see `(myenv)` in your terminal prompt), you can run Jupyter:

   ```bash
   jupyter notebook
   ```

3. **Deactivate When Done**:
   When you're finished, you can deactivate the virtual environment:
   ```bash
   deactivate
   ```

This will return you to the global environment, ensuring all dependencies stay isolated in `myenv`.

Let me know if you hit any bumps along the way!
