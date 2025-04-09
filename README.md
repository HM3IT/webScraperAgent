# Project Setup Guide
To set up the project, please follow the steps below:

- Install uv: Begin by installing [uv](https://docs.astral.sh/uv/getting-started/installation/), a fast Python package and project manager.​
 
- Synchronize Dependencies: Once uv is installed, navigate to your project directory and run the following command to install the required dependencies:​

```bash
uv sync
```
This command will create a virtual environment (if one doesn't exist) and install all dependencies specified in your pyproject.toml and uv.lock files.

Note: Ensure that your project contains a pyproject.toml file with the necessary configurations. For more details on working with projects using uv, refer to the [official documentation](https://docs.astral.sh/uv/guides/projects/).
