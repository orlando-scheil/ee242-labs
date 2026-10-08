# EE242 labs

## Setup (once per clone)

After pulling, install dependencies and enable automatic notebook output stripping:

```sh
uv sync
uv run nbstripout --install
```

Notebook outputs stay local. They are stripped automatically when committing, so
committed `.ipynb` files contain only source. The `nbstripout --install` step only
needs to be run once per clone.

If dependencies change, rerun:

```sh
uv sync
```
