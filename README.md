# Day 0 — Minimal Python Data Science Dev Container

This is a tiny starter that gives you the *same* Python environment locally and in the cloud (GitHub Codespaces).

## Quick start (easiest: Codespaces)

1. Create a new **empty** GitHub repo (e.g., `my-ds-lab`).
2. Upload these files to the repo (drag-and-drop the ZIP contents into GitHub).
3. In the repo page, click **Code → Codespaces → Create codespace on main**.
4. When it opens, create or open `notebooks/00-hello.ipynb` and run the cells.

## Local usage (after Codespaces works)

1. Install **Docker Desktop**, **VS Code**, and the **Dev Containers** extension.
2. `git clone` your repo and open it in VS Code.
3. When prompted, click **Reopen in Container** (or use the Command Palette).
4. Run notebooks / scripts exactly as in Codespaces.

> Your Python version, packages, and Jupyter will be the same everywhere, because they are defined by the dev container files in `.devcontainer/`.
