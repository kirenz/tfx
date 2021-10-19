# Tensor Flow Extended Tutorials

- Ensure you have a recent version of Anaconda Python installed.

  - On *Windows* open the Start menu and open an Anaconda Command Prompt. 
  - On *macOS* or *Linux* open a terminal window.

```bash
conda update python
```

```bash
conda update --all
```

- In your terminal: `cd` into a folder you want to install all demos.


- Clone the repository containing all demos

```bash
git clone https://github.com/executablebooks/quantecon-mini-example
```

- cd into the folder

```bash
cd tfx
```

- Now we install all needed Python libraries from the `environment.yml` file. This includes the latest version of Tensor Flow and Tensor Flow Extended: 

```bash
conda env create -f environment.yml
```

- Now activate the environment (tfx-env):

```bash
conda activate tfx-env
```


