## How to launch the exercise ?
* We can execute this exercise on Colab
    * Click or scan the QR-code <a href="https://colab.research.google.com/github/patrickhaddadteaching/codepin1/blob/main/codepin1_binder.ipynb"><img src="qr-code-pin1-collab.png" style="width:100px;height:100px;"></a>  
    * Then press Ctrl+F9 or click on Runtime/Run All
* We can execute this exercise on Binder
    * Click or scan the QR-code <a href="https://mybinder.org/v2/gh/patrickhaddadteaching/codepin1/main?urlpath=voila%2Frender%2Fcodepin1_binder.ipynb"><img src="qr-code-pin1.png" style="width:100px;height:100px;"></a>
* The exercise is a jupyter notebook compatible with voila.
The following library is required:
    * numpy
  
## Examples of procedures to execute the exercise with different systems.
1. Windows
    * First of all, Let clone this repositorie
    ```
     git clone https://github.com/patrickhaddadteaching/codepin1
    ```
    * [Download and install the latest Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links).
    * Open the Anaconda Powershell Prompt associated to Miniconda3 and type the following commands to install  to install all the dependencies required by this exercise.
     ```
        conda install jupyter
        conda install numpy
        conda install -c conda-forge voila    
    ```
    * Now, you can either launch the notebook by executing the folowing command in the directory where you cloned this repositorie.
    ```
    jupyter-notebook.exe .\TRNG_ex3_nb.ipynb
    
    ```
    
    * Or, you can directly launch it with voila  by executing the folowing command in the directory where you cloned this repositorie.
    ```
    voila.exe .\TRNG_ex3_nb.ipynb
    ```
2. Linux
3. Mac OS X
