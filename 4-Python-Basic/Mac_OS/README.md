# **Khipus.ai**
#  **Data Science Tools**

# How to export of a Jupyter notebook to PDF in Visual Studio Code

# © Copyright Notice 2025, Khipus.ai - All Rights Reserved.

This guide explains how to export of a Jupyter notebook to PDF in Visual Studio Code step-by-step.

## Export Jupyter Notebook to PDF

1. Download and install Pandoc from: https://github.com/jgm/pandoc/releases/tag/3.6.1
![alt text](images/image-19.png)
![alt text](images/image-20.png)

2. Download and install MikTeX: https://miktex.org/download

![alt text](images/image-5.png)
![alt text](images/image-8.png)
![alt text](images/image-9.png)
![alt text](images/image-10.png)
![alt text](images/image-11.png)
![alt text](images/image-12.png)
![alt text](images/image-13.png)
![alt text](images/image-17.png)
![alt text](images/image-18.png)

3. Verify Installations
Run the following commands in a terminal to verify that both tools are installed correctly:
   ```bash
   pandoc --version
   ```

![alt text](images/image-21.png)

   ```bash
   xelatex --version
   ```
![alt text](images/image-22.png)

4. Open your Jupyter notebook in Visual Studio Code. If you already have Visual Studio Code open, close it and then reopen it. 

5. Run all cells to ensure the notebook is up-to-date.

![alt text](images/image.png)


6. Access the Options Menu: The user clicks on the ... (three dots) menu located at the top-right corner of the notebook interface.

Select "Export": From the dropdown menu that appears, the user clicks on the Export option.

![alt text](images/image-14.png)
![alt text](images/image-15.png)


5. Save the notebook 

![alt text](images/image-2.png)

6. Install the missing packages.

![alt text](images/image-23.png)

7. You should see a message in the left corner that says your file is being exported as a PDF file:


![alt text](images/image-24.png)

![alt text](images/image31.png)

Note: The first time, the process will take about 5 minutes or more, depending on your internet speed

8. You have your pdf file ready:

![alt text](images/image-25.png)

## Upload the PDF file to the Khipus.ai Virtual Campus: 

1. Logs into the Khipus.ai platform using your credentials https://campus.khipus.ai/login/index.php

![alt text](images/image-26.png)

2. Navigate to the "Actividades" (Activities) section under "Unidad 1: Introducción a la Ciencia de Datos." and select the "Trabajo práctico Unidad 1" 
![alt text](images/image-27.png)

3. Click "Agregar entrega" (Add Submission) button to start the process of submitting the assignment.
![alt text](images/image-28.png)

4. "Choose File" and selects the PDF file

![alt text](images/image-29.png)

5. Finally, confirm the submission by clicking the "Guardar cambios"
![alt text](images/image-30.png)

![alt text](images/image-31.png)