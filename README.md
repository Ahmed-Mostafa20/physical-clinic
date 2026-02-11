# Physical Clinic

A simple **PHP & MySQL based Physical Clinic Management System** — to manage patients, appointments, medical records, and clinic services.

## Features
- Add, edit, and delete patients  
- Create and manage appointments  
- Store and view medical records  
- Simple clinic dashboard interface  
- Built with plain PHP, HTML, and CSS  

## Tech Stack
- **Backend:** PHP  
- **Database:** MySQL  
- **Frontend:** HTML & CSS  

## Repository Structure
```
├── index.php                  # Main homepage or dashboard
├── patients.php               # Manage patients
├── appointments.php           # Manage appointments
├── medical_records.php        # View & store medical records
├── db_connect.php             # Database connection file
├── styles.css                 # Basic styles
├── clinic_database.sql        # SQL schema for database
└── logo.png                   # Logo file (optional)
```

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Ahmed-Mostafa20/physical-clinic.git
```

### 2. Create Database
Import the provided SQL file into MySQL:
```sql
SOURCE path/to/clinic_database.sql;
```

### 3. Configure Database Connection
Open `db_connect.php` and update your MySQL credentials (host, username, password, database name).

### 4. Run the System
Place the project folder into your server’s root (`htdocs` for XAMPP) and open in your browser:
```
http://localhost/physical-clinic/index.php
```

## Usage
- **Patients** – View and manage patient details  
- **Appointments** – Create and track appointments  
- **Medical Records** – Store and consult medical history  
- Simple UI for daily clinical tasks

## Contributing
Feel free to fork the project, add improvements, or new features. Pull requests are welcome.

## License
This project is open source — no specific license provided.
