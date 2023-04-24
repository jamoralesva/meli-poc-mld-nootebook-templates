# {{ cookiecutter.project_name }}

- Proof of Concept for Insurtech Machine Learning Delivery Team
- Created by: {{ cookiecutter.author_name }}

## Folder structure

This section describe the folder structure:

```sh
{{ cookiecutter.project_name }}/
├─ doc/
├─ queries/
├─ output/
├─ {{ cookiecutter.project_name }}_eda.ipynb
├─ {{ cookiecutter.project_name }}_train_model.ipynb
├─ README.md

```

- *doc*: This folder contain the markdown format of train_model.ipynb.
- *queries*: This folder contain the .sql files necessary for execute the train_model.ipynb.
- *output*: This folder have the outputs of model, like, a feature importance dictionary and model pre-trainer file.
- *eda.ipynb*: This notebook contain the all process for the exploratory data analysis.
- *train_model.ipynb*: This notebook contain the all process for the training of model.
