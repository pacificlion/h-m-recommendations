Install conda from [here](https://docs.anaconda.com/anaconda/install/linux/)

Download dataset files from [here](https://drive.google.com/drive/folders/1ZRUIx0aF_PISnn-rHIlyQI7suYhbIcsy?usp=sharing) to input

Following structure should be present

```bash

   |-input
   |-working

```

To create conda environment run following command

```
conda create -n cs567 --file requirements.txt
```

To activate environment,

```
conda activate cs567
```

To execute the jupter notebooks, run following command

```
jupyter-notebook
```

Open ensemble.ipynb from working directory available from drive or D2L to build the file. Click on Cell-> Run All
