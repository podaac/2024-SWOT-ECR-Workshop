# 2024-SWOT-ECR-Workshop
2024 SWOT Early Career Researcher Workshop using Binder

## Prerequisites

Before the Workshop, you will need the following:

### **1. Earthdata Login Account**

An Earthdata Login account is required to access data, as well as discover restricted data, from the NASA Earthdata system. Thus, to access NASA data, you need Earthdata Login. Please visit https://urs.earthdata.nasa.gov to register and manage your Earthdata Login account. This account is free to create and only takes a moment to set up. Please remember your username and password to access the data!

### **2. A fully charged laptop or tablet**

Participation in the exercises requires a laptop or tablet. The hands-on portion of the workshop lasts about 90 minutes. We will be accessing a Jupyter Lab environment through Binder. 

### **3. Decide whether you would like to follow along via Binder or set up the environment on your local machine.**

#### *Option 1: If you would like to launch a Jupyter Lab environment via Binder, you will just need to click the following link on the day of the workshop, but will be unable to save your changes:*

*INSERT LINK*

#### *Option 2: If you would like to follow along on your local machine instead of Binder, follow these instructions:*

##### Have a Python Coding Workspace on your local machine

First, if you do not already have it, install [Python](https://www.python.org/downloads/) > 3.8. [Jupyter Lab](https://jupyter.org/install) deployed from [Anaconda Navigator](https://docs.anaconda.com/navigator/index.html) is a great option to work with Python Jupyter Notebooks. 

##### Clone the GitHub Repository

The Jupyter notebook examples we will be demonstrating are in this GitHub repository: [https://github.com/podaac/2024-SWOT-ECR-Workshop](https://github.com/podaac/2024-SWOT-ECR-Workshop)

Cloning this repository allows you to have a copy of all the Jupyter Notebook tutorials on your own machine to use. Follow [these instructions to clone our repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) from GitHub documentation, selecting your machine type and what method you would like to use to clone at the top ([GitHub Desktop](https://desktop.github.com/) is a useful interface if you would rather not use the command line).

Using GitHub Desktop, the link for cloning this particular repository is: [https://github.com/podaac/2024-SWOT-ECR-Workshop.git](https://github.com/podaac/2024-SWOT-ECR-Workshop.git)

In the command line or Git Bash, change the working directory to the location where you would want the cloned directory and then type:

`git clone https://github.com/podaac/2024-SWOT-ECR-Workshop`

##### Environment Set Up

Before the workshop, import this Python environment onto your local machine: [https://github.com/podaac/2024-SWOT-ECR-Workshop/blob/main/environment.yml](https://github.com/podaac/2024-SWOT-ECR-Workshop/blob/main/environment.yml)

One way to do this would be through the following command in your computer’s command line: 

`conda env create --file environment.yml`

To activate the environment, run the following command:

`conda activate env-swot-wrkshp`

Once you have done this, you will be able to successfully run the notebooks from the cloned repository on your local environment!
