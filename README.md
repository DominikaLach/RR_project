# RR_project

This repository contains code that tries to reproduce results of the paper [**Do alcohol control policies have the predicted effects on consumption? An analysis of the Baltic countries and Poland 2000-2020**](https://pubmed.ncbi.nlm.nih.gov/36402051/) by Rehm J, et al.

All packages required to run the code, with appropriate versions, are listed in the `requirements.txt` file.

### Authors:
* Dominika Lach
* Marcin Miszkiel
* Katarzyna Mocio
* Mateusz Tomczak


## Initializing repository to reproduce the results

1. Clone the repo to your local machine
2. Open terminal at the location of your cloned repo and type following commands:
* `python3 -m venv .venv` - This will create virtual enviroment in folder `.venv`
* Now, when you enviroment is created, depending on the OS, type:
    * `source .venv/bin/activate` for **MacOS**/**Linux**
    * `.\.venv\Scripts\activate.bat` for **Windows CMD**
4. Now that your virtual enviroment is active, in the same console, type: `pip install -r requirements.txt` - this will install all required packages

After the neccessary packages are installed the files in the repository can be executed