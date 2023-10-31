# poetry-project

## poetry
- Для начала использования ввести ```poetry shell```

## Линтер
- **[flake8](https://pypi.org/project/flake8/)**, использовать через обёртку [pyproject-flake8](https://pypi.org/project/pyproject-flake8/):
    ```
    (poetryproject-py3.11) PS D:\Study\QA course\PoetryProject> pflake8 .
    .\main.py:4:80: E501 line too long (98 > 79 characters)
    ```

## Автоформаттер
- **[black](https://pypi.org/project/black/)**, использовать напрямую:
    ```
    (poetryproject-py3.11) PS D:\Study\QA course\PoetryProject> black .
    All done! ✨ 🍰 ✨
    1 file left unchanged.
    ```