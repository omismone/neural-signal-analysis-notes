# Labs

This folder contains the laboratory exercises for the Neural Signal Analysis course. All labs within this folder share a global virtual environment to ensure consistency throughout the project.

## Global Virtual Environment Setup

A single virtual environment has been set up for all labs in this folder. Follow these steps to get it running:

1. **Navigate to the `labs` Folder:**

   Open your terminal and change directory to the `labs` folder:
   ```sh
   cd path/to/neural-signal-analysis-notes/labs
   ```

2. **Create the Virtual Environment:**

   Create a new virtual environment named `.venv`:
   ```sh
   python -m venv .venv
   ```

3. **Activate the Virtual Environment:**

   - **For Windows (using Git Bash):**
     ```sh
     source .venv/Scripts/activate
     ```
   - **For macOS/Linux:**
     ```sh
     source .venv/bin/activate
     ```

4. **Install Dependencies:**

   With the virtual environment activated, install the required packages by running:
   ```sh
   pip install -r ../requirements.txt
   ```
   This installs all the dependencies listed in the `requirements.txt` located in the parent directory.

## Contributing

If you plan to contribute to these labs, please follow the repository guidelines. When adding new lab materials, ensure that all necessary documentation and instructions are provided to help others understand and use your work.

---

This setup will help maintain a consistent working environment across all lab exercises.

