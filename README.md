# Python-For-Financial-Analysis
Udemy course by Jose Portilla

## Requirements
  * All required dependencies are located in _requirements.txt_, and optional dependencies (such as Jupyter Labs) are located in _optional-requirements.txt_.
  * Pip is a Python package manager and automatically comes with a standard Python installation
  * The following commands can be used to gather all dependencies, however it is strongly recommended that a virtual environment be used for installation (see the virtual environment step below).
    ```  
    pip install -r requirements.txt
    pip install -r optional-requirements.txt
    ```

## Virtual Environment

* It is common practice in Python to leverage libraries outside of the standard library. However, as libraries evolve over time, they may no longer be compatible with an older project. To avoid conflict, a virtual environment can be set up. On Windows, run the following command:

  + `python -m venv <Environment Directory>`

* To create the environment in the current directory:

  + `python -m venv . `

* Check out the [python documentation](https://docs.python.org/3/tutorial/venv.html) for more information.

* Now that the environment has been set up, the next step is to configure the environment to use libraries of your choice. The following commands will set up your system to install packages relative to the environment on Windows and Linux respectively:

  <code>

  \<Environment Directory>/Scripts/activate (Windows)
  
  source \<Environment Directory>/Scripts/activate ([Git Bash on Windows](https://gitforwindows.org/))

  \<Environment Directory>/bin/activate (Linux)
  </code>

* You should see the name of the directory in which the environment was created listed in parenthesis on the terminal (most likely the same name as your project directory if it was created locally). While the environment is active, any installation using pip will be localized to the environment, rather than system wide. Now, run the pip install command from above.
