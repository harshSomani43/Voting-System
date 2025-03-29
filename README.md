# Online Voting System

## Overview
The Online Voting System is a Python-based application designed to provide a secure and efficient way for users to cast their votes online. This project uses MySQL for database management and Tkinter for the GUI. 

## Tech Stack
- **Programming Language**: Python
- **Database**: MySQL
- **GUI**: Tkinter

## Database Connection
```python
import mysql.connector as mysql

mydb = mysql.connect(
    host="localhost",
    port=3306,
    user="root",
    password="YourPassword",
    database="voting_system"
)

```

## Requirements

Make sure to install the required Python packages before running the application. You can install them using pip:

```bash
pip install tk mysql-connector==2.2.9 Pillow==9.3.0

```


