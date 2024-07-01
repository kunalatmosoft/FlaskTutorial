### Basic Python Commands

- **Check Python Version**:
  ```bash
  python --version
  python3 --version
  ```

### Package Management with `pip`

- **Show Installed Packages**:
  ```bash
  pip list
  ```

- **Install a Package**:
  ```bash
  pip install package_name
  ```

- **Uninstall a Package**:
  ```bash
  pip uninstall package_name
  ```

- **Upgrade a Package**:
  ```bash
  pip install --upgrade package_name
  ```

- **Show Package Information**:
  ```bash
  pip show package_name
  ```

- **Freeze Installed Packages**:
  ```bash
  pip freeze > requirements.txt
  ```

- **Install Packages from a Requirements File**:
  ```bash
  pip install -r requirements.txt
  ```

### Virtual Environment Management

- **Create a Virtual Environment**:
  ```bash
  python -m venv env_name
  python3 -m venv env_name
  ```

- **Activate a Virtual Environment**:
  - **Windows**:
    ```bash
    .\env_name\Scripts\activate
    ```
  - **MacOS/Linux**:
    ```bash
    source env_name/bin/activate
    ```

- **Deactivate a Virtual Environment**:
  ```bash
  deactivate
  ```

