# **Khipus.ai**
# 📦 **Visual Studio Code Installation Guide**

# Python Development Environment Setup on Visual Studio Code

# © Copyright Notice 2025, Khipus.ai - All Rights Reserved.

This guide will help you set up a Python development environment using Visual Studio Code (VS Code),to ensure you have everything you need for your coding projects and tutorials! 💻💡

## 📥 **Prerequisites**

- **Install Python**: Download and install Python from the [official Python website](https://www.python.org/downloads/). Make sure to check the box to add Python to your PATH during installation.

| 🖥️ **Operating System**   
|---------------------------|
| Windows, macOS, or Linux   | 

![alt text](images/mac-1.png)

![alt text](images/mac-2.png)

![alt text](images/mac-3.png)

![alt text](images/mac-4.png)

![alt text](images/mac-5.png)

![alt text](images/mac-6.png)

![alt text](images/mac-7.png)

## Step-by-Step Installation


### 1: **Download Visual Studio Code**

1. **Download the Installer**:  
   Click the link below to download the **Visual Studio Code** installer:  
   - 📥 [**Download Visual Studio Code**](https://code.visualstudio.com/)
![alt text](images/mac-8.png)
 

### 🔧 Step 2: **Install Visual Studio Code**

1. **Run the Installer**:  
   Double-click the downloaded file to start the installation process. 🖱️ 
   ![alt text](images/mac-9.png) 

2. **Follow the Installation Instructions**:  
   ✔️ Follow the prompts in the installer to complete the installation.
   ![alt text](images/mac-10.png)


### 2. Install Python Extension for VS Code

1. Open VS Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing 
3. Search for "Python" and install the extension published by Microsoft.

![alt text](images/mac-11.png)

### 3. Install Recommended Extensions

- **Jupyter**: For running Jupyter Notebooks directly in VS Code.
![alt text](images/mac-12.png)

### 4. Install Virtual Environment Support

1. Open the integrated terminal in VS Code (`Ctrl+`` for Windows/Linux or `Cmd+`` for Mac).
![alt text](images/mac-13.png)

2. Create a virtual environment:
![alt text](images/mac-14.png)

   ```

   Example: admin@Admin_MacBook-Pro ~ %
   ```
   ```
   python -m venv .venv
   ```

3. Activate the virtual environment:
   - **Windows**: `venv\Scripts\activate`
   - **Mac/Linux**: `source venv/bin/activate`
4. Install necessary Python packages:
   ```bash
   pip install --upgrade pip
   ```
![alt text](images/mac-15.png)

4.1 Install NumPy package:
   ```bash
   pip install numpy
   ```
![alt text](images/mac-16.png)

4.2 Install Pandas package:
   ```bash
   pip install pandas
   ```
![alt text](images/mac-17.png)
4.3 Install Matplotlib package:
   ```bash
   pip install matplotlib
   ```
4.4 Install seaborn package:
   ```bash
   pip install seaborn 
   ```
4.5 Install pip install statsmodels:
   ```bash
   pip install statsmodels
   ```
4.6 Install Notebook Converter package:
   ```bash
   python -m pip install nbconvert
   ```
 4.7 Install Notebook Converter package:
   ```bash
   pip install notebook

   ```  

### 5. Test Your Setup

1. Create a new Python file:
![alt text](images/mac-18.png)

![alt text](images/mac-19.png)

![alt text](images/mac-20.png)

![alt text](images/mac-21.png)


   ```
   print("Hello, Python!")
   ```

2. Run the file:

![alt text](images/mac-22.png)
