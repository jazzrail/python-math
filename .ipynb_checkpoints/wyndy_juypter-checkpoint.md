Ctrl + enter - runs and outputs in cell
shift + enter - runs and provides a new cell


## Starting up
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