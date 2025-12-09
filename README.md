# paint_app
An app to map colours in an image to various miniature paint product lines


### Getting Started
1. Make sure you have [Python 3.12](https://www.python.org/) installed.

2. Clone the repository
    ```bash
    git clone (https://github.com/mezzX/paint_app.git)
    ```
    
3. Use [Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) to create a new environment and install dependencies. <br>[Click Here](https://nbviewer.jupyter.org/github/johannesgiorgis/school_of_ai_vancouver/blob/master/intro_to_data_science_tools/01_introduction_to_conda_and_jupyter_notebooks.ipynb) if you need a detailed guide on using conda.

    - __Linux__ or __Mac__: 
    ```bash
    conda create --name paint python=3.12
    conda activate sliding
    pip install -r requirements.txt
    ```
  
    - __Windows__: 
    ```bash
    conda create --name paint python=3.12 
    conda activate paint
    pip install -r requirements.txt
    ```

### Instructions
Navigate to the directory and open paint_app.ipynb

    jupyter lab paint_app.ipynb

## TODO
- Implement the colour extractor to get the hex code of the dominant colours
- Develop the mobile shell to link the colour extractor with the KD tree graph
- connect the colour extractor to the phone's camera/photo library
