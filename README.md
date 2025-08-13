## Git Version Control

This repository is a demonstration of a standard Git branching and version control workflow, commonly used in DevOps and software development projects. The purpose is to showcase best practices for managing code, from feature development to release.

---

## Project Purpose

The main goal of this project is to provide a clear, hands-on example of the following concepts:

-   **Branching Strategy:** Using `main`, `dev`, and `feature` branches.
-   **Committing Changes:** Writing clear and descriptive commit messages.
-   **Pull Requests:** Merging code in a controlled and reviewed manner.
-   **Tagging:** Marking specific commits as releases (e.g., `v1.0.0`).
-   **Documentation:** Maintaining a `README.md` and `.gitignore` file.

---

## Branching Strategy

This project follows the GitFlow-lite model:

-   `main`: This branch represents the stable, production-ready code. Code is only merged into `main` from the `dev` branch for a new release.
-   `dev`: This is the primary development branch. All feature branches are created from `dev` and merged back into it via Pull Requests.
-   `feature/*`: Individual features are developed in their own branches (e.g., `feature/add-login-page`). This keeps development work isolated until it's ready for integration.

---

## How to Contribute

Since this is a demo project, direct contributions aren't necessary. However, you can clone or fork this repository to experiment with the workflow yourself.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mdazamdevops/git-version-control.git](https://github.com/mdazamdevops/git-version-control.git)
    ```
2.  **Navigate into the project:**
    ```bash
    cd git-version-control
    ```
3.  **Create your own feature branch and start experimenting!**
    ```bash
    git checkout -b feature/my-new-idea
    ```

---

## Author

* **mdazamdevops** - [GitHub Profile](https://github.com/mdazamdevops)