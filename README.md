# studio_funzioni
Studio di funzioni in Python




# uv


uv init studio_funzioni
uv add --dev ipykernel
uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=project
uv run --with jupyter jupyter lab

