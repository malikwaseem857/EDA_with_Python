## EDA with Python
### 1. Pandas Profiling for EDA
#### 1.1 Pandasa Profiling / ydata-profiling installation
To install Pandas Profiling, you can use pip. Open your terminal or command prompt and run the following command:

```bash
conda create -n ydata_profiling
conda activate ydata_profiling
conda install python=3.11 -y
pip install ydata-profiling
pip install ipykernel
```bash
#### 2. dtale
To install dtale, you can use pip. Open your terminal or command prompt and run the following command:

```bash
conda create -n dtale python=3.11 -y
conda activate dtale
pip install dtale
# if you want to also use "Export to PNG" for charts
pip install kaleido ipykernel
```


### 3. pyGwalker
To install pyGwalker, you can use pip. Open your terminal or command prompt and run the following command:

```bash
conda create -n pygwalker python=3.11 -y
conda activate pygwalker
pip install pygwalker ipykernel seaborn
pip install runcell
```


#### 4. Sweetviz
To install Sweetviz, you can use pip. Open your terminal or command prompt and run the following command:

```bash
conda create -n sweetviz -y python==3.10
conda activate sweetviz
pip install sweetviz pandas openpyxl ipykernel
pip uninstall numpy -y
conda install numpy==1.23.4 -y
```

#### 5. skimpy
To install skimpy, you can use pip. Open your terminal or command prompt and run the following command:

```bash
conda create -n skimpy python=3.10 -y
conda activate skimpy
pip install skimpy jupyterlab notebook ipython pandas openpyxl 
pip install polars-lts-cpu # only if the system has a CPU with ARM architecture
```
#### 6. Dataprep
To install Dataprep, you can use pip. Open your terminal or command prompt and run the following command:


```bash
conda create -n dataprep python=3.10 -y
conda activate dataprep
pip install dataprep
```

#### 7. LIDA from Microsoft
To install LIDA, you can use pip. Open your terminal or command prompt and run the following command:

```bash
conda create -n lida python=3.10 -y
conda activate lida
pip install -U lida llmx openai
pip install llmx[transformers]
```

#### 8. Pandas-AI
To install Pandas-AI, you can use pip. Open your terminal or command prompt and run the following command:

```bash
conda create -n pandas_ai python=3.10 -y
conda activate pandas_ai
pip install pandasai
pip install pandasai-litellm
pip install ipykernel
```

