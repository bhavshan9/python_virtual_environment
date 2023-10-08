# python_virtual_environment
Beginer friendly readme to create a virtual environment in python 
*****



# Setting Up Python 3 and Virtual Environment

## Introduction
Welcome to the setup guide for Python 3 and a virtual environment. This guide will walk you through the process of installing Python 3, creating a virtual environment, and activating it. A virtual environment is a great way to isolate project dependencies and keep your development environment organized.

## Install Python 3
- Download and install Python 3 from [python.org](https://www.python.org/downloads/).
- Make sure to check the option that says "Add Python to PATH" during installation.

## Open Terminal/Command Prompt
- Open a terminal (Linux/Mac) or command prompt (Windows).

## Check Python Version
- Confirm that Python 3 is installed:
  ```bash
  python --version
![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/7dd7e530-ec4e-438f-910f-c1f44f84a8e6)

```markdown

  ```

## Create a Virtual Environment
- Navigate to your project directory and run:
  ```bash
  python -m venv venv
  ```
![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/bfaacb97-326e-45c6-b866-bbf218d985df)<br>I have given my virtual environment name as learn

## Activate the Virtual Environment
- Activate the virtual environment:
  - **For Windows:**
    ```bash
    venv\Scripts\activate
    ```
  - **For Linux/Mac:**
    ```bash
    source venv/bin/activate

   ![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/5f8c7780-e161-4250-aa70-2b621420f991)



## Next Steps

*Now that your virtual environment is activated, you can proceed with the following:

### Install Project Dependencies
Use `pip` to install the required packages for your project:
![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/f3d40e01-14c3-45d9-b2c9-a6d9c2d60851)

![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/475be1b7-9891-40a2-a5a3-521d74cfeb54)
![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/11dd40d4-bc3a-414d-befb-2986d1c16919)


### Generate `requirements.txt`
After installing dependencies, generate a `requirements.txt` file to document them:

```bash
pip freeze > requirements.txt
```
![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/b77c00c9-ee62-4818-bfe5-fa2439adc465)
![image](https://github.com/bhavshan9/python_virtual_environment/assets/144831365/4ce7846d-74d6-4209-a488-1b2dc84faff1)


### Run Your Project
Execute your Python scripts or start your development server:

```bash
python your_project_file.py
```

### Deactivate the Virtual Environment
When you're done working on your project, deactivate the virtual environment:

```bash
deactivate
```

Feel free to customize these next steps based on your specific project requirements. Enjoy coding!
```
