# SQL PROJECT README

# Running the Northwind Database in pgAdmin 4

## 1. Download the Northwind Database
You can download the Northwind database SQL file from GitHub. Follow these steps:
- Go to the official Northwind GitHub repository:
  - [Northwind GitHub Repository](https://github.com/jpwhite3/northwind-SQLite)
- Download the `northwind.sql` file or the appropriate version for PostgreSQL if available.

## 2. Install PostgreSQL and pgAdmin
If you don't have PostgreSQL installed, follow these steps:
- Download PostgreSQL from [https://www.postgresql.org/download/](https://www.postgresql.org/download/)
- During installation, ensure you install **pgAdmin 4** as part of the setup.
- After installation, open **pgAdmin 4** to manage your databases.

## 3. Create a New Database in pgAdmin 4
1. Open **pgAdmin 4**.
2. In the **Object Browser**, right-click on **Databases** and select **Create** > **Database**.
3. Name your new database (e.g., `northwind`).
4. Click **Save**.

## 4. Run the Northwind SQL Script in pgAdmin 4
1. In **pgAdmin 4**, select the `northwind` database from the Object Browser.
2. Click on the **Query Tool** (the SQL icon).
3. In the query editor, click on the **Open File** icon and select the `northwind.sql` file you downloaded.
4. Click on **Execute/Refresh** (the **lightning bolt** icon) to run the SQL script.
5. The script will create the tables and insert data into your new `northwind` database.

## 5. Verify the Data
After the script has run, you can verify the data by running a simple query:
1. In the Query Tool, type the following:
   ```sql
   SELECT * FROM customers LIMIT 5;

## Installing Dependancies

pip install -r requirements.txt

requirements;
- pandas
- sqlalchemy
- psycopg2