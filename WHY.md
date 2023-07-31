## Why We Recommend This Process

This approach offers several benefits and encourages good practices. 
In this guide, we explain the reasons behind our recommendations.

### 1. Create One Virtual Environment per Project

Each project may require different packages and dependencies. 
By creating separate virtual environments for each project, we ensure that the dependencies are isolated from one another. 
This isolation prevents conflicts between packages used in different projects and ensures that each project has its own clean environment.

### 2. Use Built-In Tool (venv)

We use `venv` because it's a built-in Python module, requires no installation, and consistently works across different platforms. 
It ensures that everyone working on the project uses the same virtual environment, reducing potential issues due to variations in package versions or configurations.

### 3. Use Local Folder

In our courses, we encourage students to create virtual environments in the local project folders. This practice emphasizes the importance of self-contained environments for individual projects and reinforces the habit of organizing project-related files together.

### 5. Name the Folder .venv

Name the virtual environment folder `.venv`, using a leading dot in the folder name. This convention  keeps environment-related files away from the project's main code files. It also aligns with the common naming convention for virtual environments.

### 6. Later: Grouping Environments

While practicing at work or on shared systems, it might be useful to group multiple projects' virtual environments together. However, during the learning process, it's essential to focus on the practice of creating and activating different environments.

### 7. Community Discussion

Our recommendations are current, not fixed. We expect them to change over time. 
Join the conversation by sharing in our [discussions](https://github.com/denisecase/datafun-00-python-virtual-env/discussions).
