# RR_project

This repository contains code that tries to reproduce results of the paper [**Do alcohol control policies have the predicted effects on consumption? An analysis of the Baltic countries and Poland 2000-2020**](https://pubmed.ncbi.nlm.nih.gov/36402051/) by Jürgen Rehm, Alexander Tran, Inese Gobiņa, Kinga Janik-Koncewicz, Huan Jiang, Kawon Victoria Kim, Vaida Liutkutė-Gumarov, Laura Miščikienė, Rainer Reile, Robin Room, Mindaugas Štelemėkas, Relika Stoppel, Witold A. Zatoński, Shannon Lange

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

Now that the virtual enviroment is set, you can use it by selecting it as python kernel in any IDE that supports it to run the jupyter notebook file.

You IDE may require you to add this enviroment as a python interpreter manually. In such case, when adding the interpreter, navigate to, and select the following file in the enviroment folder:

> `./.venv/bin/python`

If you want to run the notebook on other enviroments, you can just add a code cell at the beginning of the jupyter file `RR_project.ipynb* with the following command:

> `!pip install -r requirements.txt`

Run this cell before other cells, it will install all required packages on the enviroment that is selected as kernel for the jupyter file. Note that this method is less robust than creating a clean enviroment.

After the neccessary packages are installed the files in the repository can be executed