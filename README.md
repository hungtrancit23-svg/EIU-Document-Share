## 📁 Initial Folder Structure
* `src/frontend/`: HTML, CSS, and JS web interfaces
* `src/backend/`: Node.js & Express API code
* `docs/`: System documentation, architecture diagrams, and ADRs

## 🔀 Branching Strategy & Pull Request (PR) Rules
* **`main` branch:** Contains stable, production-ready code. No direct commits allowed.
* **`develop` branch:** The main integration branch for development.
* All developers must create feature branches from `develop` (e.g., `feature-login`).
* Merging into `develop` requires a **Pull Request (PR)**, which must be reviewed and approved by the **Tech Lead** before merging.
