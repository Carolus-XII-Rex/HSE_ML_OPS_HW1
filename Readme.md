python -m venv env
env\Scripts\activate

pip install poetry

poetry install

dvc pull

poetry run python hw/infer.py
