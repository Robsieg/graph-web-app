# Repository Overview

This repository contains a Streamlit-based web application. Below is an overview of the structure and how to set it up.

## Directory Structure
- `app/`: Contains the main application code, including Streamlit scripts and models.
- `__pycache__/`: Python bytecode files (ignored in `.gitignore`).

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the `app/` directory:
   ```bash
   cd app
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:
   ```bash
   streamlit run streamlit_app.py
   ```

## Notes
- Ensure Docker is installed if you plan to use the provided Dockerfile.
- Add your GitHub Personal Access Token as a secret if using the MCP server.