**PySpark Setup with IntelliJ IDEA (Windows Guide)**

A complete step-by-step guide to configure PySpark locally using IntelliJ IDEA with JDK and Python.
This setup is ideal for Big Data coursework, Spark assignments, and local experimentation.


**============================================================================================**
## **Intellij Installation**
↓
Download IntelliJ
install IntelliJ
Download Python
Create Python Project
Install Pyspark
Install JDK
Create Pyfile with any name
Open git url and copy the Code from code_setup
Paste in Pyfile
Edit java path
Run it


===================================================================================================
📌 **Installation & Configuration Steps**
1️⃣ **Install IntelliJ IDEA**

Download from:
*https://www.jetbrains.com/idea/download/*

Install with default settings.

Launch IntelliJ.

2️⃣ **Install Python (3.10.11)**

Download Python from:
https://www.python.org/downloads/

During installation:

✅ Check “Add Python to PATH”

✅ Verify installation:

✅ python --version


3️⃣ **Create a Python Project in IntelliJ**

✅ Open IntelliJ

✅ Click New Project

✅ Select Python

✅Choose New Virtual Environment (.venv) 

✅ Python (3.10.11)

Click Create

4️⃣ **Install PySpark**

✅ Open IntelliJ Terminal and run:

✅ pip install pyspark

✅Verify:

✅pip show pyspark


5️⃣ **Install JDK (Required for Spark)**

✅ After installation:

✅ Set Environment Variable

✅ JAVA_HOME → Path to JDK installation

Example:

C:\Program Files\Java\jdk-11

✅ Add to system PATH:

✅ %JAVA_HOME%\bin

✅ Verify:

✅ java -version


6️⃣ **Create PySpark File**

✅ Inside your project:

✅ Right click → New → Python File

✅ Name it anything (e.g., main.py)

7️⃣ **Copy Code from Repository**

✅ Open GitHub repository

✅ Go to code_setup

✅ Copy the PySpark code

✅ Paste into your Python file


8️⃣ **Edit Java Path in Code (If Required)**

✅ Inside your script, make sure:

✅ import os
✅ os.environ['JAVA_HOME'] = r'C:\Program Files\Java\jdk-11'

✅ Adjust according to your system.



9️⃣ **Run the Application**

✅ Click ▶ Run in IntelliJ.

✅ If configured correctly:

✅ Spark will start locally

✅ Console will display Spark logs

✅ Output will be printed

📂 Recommended Project Structure
project_name/
 ├── .venv/
 ├── main.py
 ├── Dataset/
 ├── spark-config/
 └── README.md





 
🚀 ##Why This Setup?

✔ No Hadoop cluster required
✔ Runs Spark locally
✔ Clean development workflow
✔ Beginner-friendly
✔ Perfect for academic Big Data courses
