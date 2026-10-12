cd muj-projekt
uv add --dev ipykernel
uv run ipython kernel install --user --name=casmi26 --display-name="casmi26"

cd muj-projekt
jupyter lab
