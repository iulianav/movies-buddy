# Your AI-Powered Movies Buddy

## 🤗 How to contribute

1. Clone the repo:

```bash
git clone git@github.com:xtreamsrl/movies-buddy

gh repo clone xtreamsrl/movies-buddy
```

> [!NOTE]
> The project uses Python 3.11

1. Install PDM

2. Run the following:

```bash
pdm install --group=:dev
```

3. Check if everything works:

```bash
pdm run python -c "from movies_buddy import version; print(version.__version__)"
```

4. Install `pre-commit` and `nbstripout` hooks:

```bash
pdm run pre-commit install --install-hooks
pdm run nbstripout --install
```
