---
description: Run streamlit code in Jupyter Notebooks
---

# Streamlit Code Running from Jupyter Notebook

#### Run Streamlit Code in Jupyter Notebook

* Open command prompt
* Run the command,
  * jupyter nbconvert –to script JupyterNotebookName.ipynb
  * awk ‘!/ipython/’ JupyterNotebookName.py &gt; temp.py && mv temp.py app.py && rm JupyterNotebookName.py
  * streamlit run app.py
* Open the url [http://localhost:8501](http://localhost:8501/) \(Browser\)

**References**

Notebook – [https://github.com/SurendraRedd/StreamlitProjects/blob/master/Streamlit.ipynb](https://github.com/SurendraRedd/StreamlitProjects/blob/master/Streamlit.ipynb)

App – [https://github.com/SurendraRedd/StreamlitProjects/blob/master/app.py](https://github.com/SurendraRedd/StreamlitProjects/blob/master/app.py)

