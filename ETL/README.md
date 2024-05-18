## ETL

The Extract, Transform, Load (ETL) will show you the code in different steps of the ETL process by providing a basic explanation and it shows how to extract the datasets from datasource, and transform data based on the project's requirement and load the transformed data into MySQL database.

### Installation:
1. Install Python IDE Anaconda Navigator - Jupyter Notebook. The Anaconda documentation below provides instructions to install it based on your operating systems.
- https://docs.anaconda.com/anaconda/install/
2. Install MySQL. The MySQL installation Guide below provides instructions to install it based on your operating systems.
- https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/
3. Install Python libraries Pymysql, Pandas and NumPy on Jupyter Notebook using the below commands.
- pip install pymysql
- pip install pandas
- pip install numpy
- pip install seaborn
- For Verfication you can use cmd to check the installed libaries 
- pip list 

### Running code in Jupyter Notebook:
1. Jupyter Notebook documentation on how to run code. 
- https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Running%20Code.html

### ETL steps:
1. Extract flat files from Kaggle.com <br>
Download the below files to your computer.
- Netflix IMDB scores https://www.kaggle.com/sarahjeeeze/imdbfile

2. Transform data <br>
Open Jupyter Notebook in Anaconda and transform the data into tuple format .
- Code example for transforming the Netflix original file 
https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/blob/main/ETL/Transformation%20the%20data.png
https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/blob/main/ETL/Transformation.png

3. Load data <br>
Create the tables in mysql and load the transformed data into the tables using Python.
- Code example for creating the original_dim table in database and loading data to it 
https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/blob/main/ETL/Load%20the%20data%20into%20MySQL.png

### Contribute:
1. Source Code: https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/blob/main/ETL/Data%20Warehousing-Netflix-Project.ipynb





