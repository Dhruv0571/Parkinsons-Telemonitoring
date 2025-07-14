# Parkinsons Telemonitoring Project

## Overview
The Parkinsons Telemonitoring project aims to develop a system for monitoring Parkinson's disease patients using machine learning classification algorithms. The project includes data fetching, preprocessing, and various classification techniques to analyze patient data.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Dhruv0571/parkinson-telemonitoring.git
   ```
2. Navigate to the project directory:
   ```
   cd parkinson-telemonitoring
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
The main analysis and code for the project can be found in the Jupyter notebook located at `notebooks/Final Project Phase 3.ipynb`. Open this notebook to run the code and view the results.

## Directory Structure
- `data/`: Contains datasets used in the project.
- `notebooks/`: Contains Jupyter notebooks for analysis.
- `src/utils/`: Contains utility functions and modules.
- `requirements.txt`: Lists the required Python packages.
- `.gitignore`: Specifies files to be ignored by Git.


## Setting Up and Connecting to the MySQL Server 
Follow these steps to install, configure, and connect to your MySQL database for this project.

---

### ✅ 1. Install MySQL Server

**Windows/Mac:**
- Download and install MySQL from the official site:  
  👉 [https://dev.mysql.com/downloads/installer](https://dev.mysql.com/downloads/installer/)

During installation:
- Set a **root password** — remember it!
- Install **MySQL Server**, **Workbench** (optional), and **MySQL Shell**.

### ✅ 2. Start the MySQL Server

Make sure the MySQL server is running:

- **Windows**: Open "Services" → Look for **MySQL** → Start it.
- **Mac/Linux**: Use terminal: 
-bash
sudo service mysql start

 ### Write YOUR_PASSWORD in the password section for conncetion 
 conn = mysql.connector.connect(
    user='root',
    password='YOUR_PASSWORD_HERE',  # Replace with your actual password
    host='localhost',
    database='ParkinsonsDB'
)
 ### Write YOUR_CONNECTION_STRING_HERE/Your ROOT Directory Here 
 %load_ext sql
connect = 'YOUR_CONNECTION_STRING_HERE/Your ROOT Directory Here'  # Replace with your actual connection string/ Root Directory
%sql $connect

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
# Parkinsons-Telemonitoring
The Parkinsons Telemonitoring project aims to develop a system for monitoring Parkinson's disease patients using machine learning classification algorithms. The project includes data fetching, preprocessing, and various classification techniques to analyze patient data.
