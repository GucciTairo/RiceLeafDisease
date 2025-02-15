#Treo  
 Here is my approach to rice leaf disease detection. I utilized UV Astral to create a virtual environment, running the entire process directly in VS Code without relying on Colab or any other external tools.  
My dataset have 5 class with "Rice Blast, Rice Brown Spot, Rice Healthy, Rice Hispa, Rice Scald".   
Here is my dataset use for training model. After considering for best model training. I decided to divide Training model to train validation and test  
You can get dataset from the link below (Already image preprocessing):  
https://www.kaggle.com/datasets/tairoooo/rice-leaf-disease-dataset


If you consider using Jupyter Notebook (in VS Code) instead of Colab, I recommend you to use UV Astral.  
Docs to install UV Astral on Linux, Mac, Windows:  
https://docs.astral.sh/getting-started/installation/  

After installation you can create virtual environment to run for jupyternotebook, run python code,...  
`uv venv`  
`source .venv/bin/activate`: Activate virtual environment to add extra library, dependencies,...  
`uv add ipykernel`

Add any packages you want to run in your project like numpy, scipy, pandas, pytorch,...  
Add ipykernel to run to you project:  
`uv run ipython kernel install --user --name=uv`  

**_Remember must install cuda and cuDNN to suitable to work for tensorflow, keras, pytorch. Download right version to have best performance_**  
Download link: https://developer.nvidia.com/  
Using commands:  
`nvidia-smi`  
`nvidia-detector`    
to check for the version of cuda and cuDNN

Enable GPU usage commands:  
`nvidia-settings`  
`watch -n 1 nvidia-smi`
Unlock the power usage of nvidia. change number 60 depend on the W usage of ur GPU  
`sudo nvidia-smi -pl 60` 
Check for power usage:  
`nvidia-smi -q -d POWER`   
You can watch your model using how much power of GPU  
`htop`  
**_MUST REMEMBER RESTART YOUR VSCODE_**  


**_ENJOYINGGG THE BEST PACKAGES EVERRRRRRRRRR!!_**
