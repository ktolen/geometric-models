## **Decoding Hydrogel Porosity: Advancing the Structural Analysis of Hydrogels for Biomedical Applications**

#### *Supplementary Information*

### **About The Jupyter Notebook**  
This Jupyter notebook is part of the supplementary information for the paper titled above.  
It is written in **Python 3.11.5** and utilises the **Pandas 2.0.3** and **SciPy 1.11.1** libraries.  

### **What Does This Code Do?**  
This code generates the **diameter, area, perimeter, and/or volume** of **2D or 3D geometric models** from diffusion data using the **convex hull algorithm**.  

### **Who Can Use This Code?**
This code is designed for users of all skill levels, including those with no to little programming experience. 
Instructions are provided within the notebook.

### **Requirements**  
To run this code, ensure that your computer has:  
- **Python 3**  
- **Jupyter Notebook**  
- The following Python libraries: **pandas** and **scipy**  

💡 *Tip:* You can install **Anaconda** to easily set up all these dependencies.  
[Installation Guide](https://www.anaconda.com/download)  

### **Supported Data Format**  
This code accepts **CSV files** as input, which should be the output of **image analysis from particle tracking**. The CSV file must contain at least three columns:  
- **A unique particle identifier**  
- **X coordinate**  
- **Y coordinate**  

An optional **Z coordinate** can also be included.  
Each row represents an entry for these variables, and the first row should contain the **column titles**.
