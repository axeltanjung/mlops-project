# **Machine Learning Operation Projects**

![workflow status](https://github.com/axeltanjung/mlops-project/actions/workflows/builder.yml/badge.svg)

Steps:
+ Select **Use this template** > **Create a new repository**. This menu is in the top right corner of this repository.
+ Create and define your the project repository.
+ Edit the [README.md](README.md) file's **workflow status** badge with the name of your repository.
+ Create virtual environment

    ```bash
    virtualenv .venv -p /usr/bin/python3.10
    ```
  **Note:** You can use any Pyton version, as long the Python packages in `requirements.txt` are supported. Because of the Python packages in `requirements.txt` were declared without describe the version.
+ Activate the virtual environment

    ```bash
    source .venv/bin/activate
    ```

+ Install package.

    ```bash
    pip install -r requirements.txt
    ```

+ enable the environment variables.

    ```bash
    cp .env.example .env
    ```