# **Khipus.ai**
# 📦 **Visual Studio Code Installation Guide**

# Python Development Environment Setup on Visual Studio Code

This guide will help you set up a Python development environment using Visual Studio Code (VS Code),to ensure you have everything you need for your coding projects and tutorials! 💻💡

## 📥 **Prerequisites**

- **Install Python**: Download and install Python from the [official Python website](https://www.python.org/downloads/). Make sure to check the box to add Python to your PATH during installation.

| 🖥️ **Operating System**   
|---------------------------|
| Windows, macOS, or Linux   | 

![alt text](images/image.png)

![alt text](images/image-1.png)

![alt text](images/image-2.png)

![alt text](images/image-3.png)


## Step-by-Step Installation


### 1: **Download Visual Studio Code**

1. **Download the Installer**:  
   Click the link below to download the **Visual Studio Code** installer:  
   - 📥 [**Download Visual Studio Code**](https://code.visualstudio.com/)
![alt text](images/image-4.png)
 

### 🔧 Step 2: **Install Visual Studio Code**

1. **Run the Installer**:  
   Double-click the downloaded file to start the installation process. 🖱️ 
   ![alt text](images/image-5.png) 

2. **Follow the Installation Instructions**:  
   ✔️ Follow the prompts in the installer to complete the installation.
   ![alt text](images/image-6.png)

   ![alt text](images/image-7.png)

3. **Launch Visual Studio Code**:  
   🎉 Once installation is complete, launch **Visual Studio Code** from the Start Menu or desktop.
   ![alt text](images/image-8.png)

### 2. Install Python Extension for VS Code

1. Open VS Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing 
3. Search for "Python" and install the extension published by Microsoft.

![alt text](images/image-9.png)

### 3. Install Recommended Extensions

- **Jupyter**: For running Jupyter Notebooks directly in VS Code.
![alt text](images/image-10.png)

### 4. Install Virtual Environment Support

1. Open the integrated terminal in VS Code (`Ctrl+`` for Windows/Linux or `Cmd+`` for Mac).
![alt text](images/image-11.png)

2. Create a virtual environment:
![alt text](images/image-12.png)

   ```
   cd C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python<version>\

   Example:cd C:\Users\admin2024\AppData\Local\Programs\Python\Python313\
   ```
   ```
   python -m venv venv
   ```
   ![alt text](images/image-13.png)

3. Activate the virtual environment:
   - **Windows**: `venv\Scripts\activate`
   - **Mac/Linux**: `source venv/bin/activate`
4. Install necessary Python packages:
   ```bash
   pip install --upgrade pip
   ```
![alt text](images/image-19.png)

### 5. Test Your Setup

1. Create a new Python file:
![alt text](images/image-14.png)

![alt text](images/image-15.png)

   ```
   print("Hello, Python!")
   ```
   ![alt text](images/image-16.png)

   ![alt text](images/image-17.png)

2. Run the file by pressing `F5` or right-clicking and selecting **Run Python File in Terminal**.

![alt text](images/image-18.png)
