## For most necessary libraries
```text
pip install -r requirements.txt
```

## For progress bar
```text
pip install ipywidgets
```

#### Jupyter lab
```text
pip install ipywidgets jupyterlab_widgets
```

#### Jupyter notebook
```text
jupyter nbextension enable --py widgetsnbextension --sys-prefix
```

```text
jupyter nbextension install --py widgetsnbextension --sys-prefix
```

## For testing
```text
pytest tested_file.py -v -s
```

## Necessary api keys
add to the root `.env` file
