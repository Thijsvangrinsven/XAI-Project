# XAI-Project
XAI Final Project

small warning: the installs you are about to do require quite a lot of memory, just like running the code.

INSTALLATION STEPS
1. Open Anaconda Prompt.

2. Make a virtual environment:
   a. Create a new environment
      conda create --name myenv python=3.8
      (Follow the prompts and type 'y' when asked to proceed)

   b. Activate the environment:
      conda activate myenv

3. Install packages:
   pip install lime shap matplotlib scikit-learn pandas numpy seaborn torch tqdm scipy -c conda-forge

4. Add the environment as a kernel:
   python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"

5. Open the Jupyter notebook file (Final Project.ipynb.

6. Select the Conda environment Kernel in Jupyter:
   a. At the top, click kernel -> change kernel
   b. Select "Python (myenv)"

7. Run all code in the Jupyter notebook.
