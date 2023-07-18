# ETL Project using PostgreSQL and Python

This Jupyter Notebook contains a small Extract, Transform, Load (ETL) project that demonstrates how to create a PostgreSQL database and tables using Python. The ETL process involves extracting data, transforming it as needed, and loading it into the database for further analysis.

## Prerequisites

Before running this notebook, make sure you have the following installed:

1. [Python](https://www.python.org/downloads/) - Python programming language.
2. [Jupyter Notebook](https://jupyter.org/install) - Interactive computing environment.
3. [psycopg2](https://pypi.org/project/psycopg2/) - PostgreSQL adapter for Python.

## Setting Up PostgreSQL

1. Install PostgreSQL: If you don't have PostgreSQL installed, download and install it from the [official website](https://www.postgresql.org/download/).

2. Create a Database: Open your PostgreSQL client (e.g., pgAdmin) and create a new database. Note the database name, username, and password, as you will need them later to connect from Python.

## Running the ETL Project

1. Clone the Repository: Clone this repository to your local machine or download the Jupyter Notebook.

2. Install Required Packages: Open a terminal/command prompt, navigate to the project folder, and install the required Python packages using the following command:
   
```pip install psycopg2```


3. Open Jupyter Notebook: Launch Jupyter Notebook from the terminal by typing `jupyter notebook`.

4. Open the ETL Project Notebook: Navigate to the folder where you cloned/downloaded this repository and open the `ETL_Project.ipynb` notebook.

5. Connect to PostgreSQL: In the notebook, locate the section where the PostgreSQL connection is established. Replace the placeholders (host, database, user, password) with your PostgreSQL database connection details.

6. Execute the Notebook: Run each cell of the notebook sequentially to execute the ETL process. The notebook will guide you through the steps of creating tables, extracting data, transforming it, and loading it into the database.

## Conclusion

This ETL project demonstrates the process of creating a PostgreSQL database and tables using Python. It serves as a starting point for more complex ETL projects and can be extended to handle larger datasets and more intricate transformations. Feel free to modify and adapt the notebook to suit your specific use case and data requirements.

Happy coding! 🚀
