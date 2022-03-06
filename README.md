# Tensor Flow Extended Tutorials

First, we need to ensure you have a recent version of **Anaconda** installed: 

- 1. If you don't have Anaconda, follow this [Anaconda installation tutorial](https://kirenz.github.io/codelabs/codelabs/anaconda-install/#0). 

- 2. If you already have Anaconda: On *Windows* open the Start menu and open an Anaconda Command Prompt. On *macOS* or *Linux* open a terminal window:


```bash
conda update --all
```

- 3. In your terminal: `cd` into a folder you want to install all demos.

```bash
cd your-path
```


- 4. Clone the repository containing all demos

```bash
git clone https://github.com/kirenz/tfx
```

- 5. cd into the tfx folder

```bash
cd tfx
```

- 6. Now we install all needed Python libraries from the `environment.yml` file to create a virtual environment named `tfx-env`. This includes the latest version of Tensor Flow and Tensor Flow Extended: 

```bash
conda env create -f environment.yml
```

- 7. Activate the `tfx-env` environment:

```bash
conda activate tfx-env
```

- 8. Check your version of TFX with `tfx_check.ipynb`.

- 9. Go to the folder `penguin_template` and use the starter code in `penguin_simple.ipynb` to build your TFX-pipeline.

- 10. The folder `penguin_solution` includes a succesfull run of the `penguin_simple.ipynb` file. 

