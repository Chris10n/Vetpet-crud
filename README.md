# 🐾 Vetpet CRUD

A simple and elegant veterinary pet records management system built with PHP and MySQL.

##  Features

- **Create** - Add new pet records with images
- **Read** - View all pet records in a responsive card layout
- **Update** - Edit existing pet information
- **Delete** - Remove pet records with confirmation
- **Image Upload** - Store pet photos in the uploads folder
- **Dark/Light Mode** - Toggle between themes
- **Responsive Design** - Works on all devices

##  Technologies

- PHP
- MySQL
- Bootstrap 5
- SweetAlert2
- PDO for database operations

##  Installation

1. Clone the repository:
```bash
git clone https://github.com/Chris10n/Vetpet-crud.git
```

2. Import the database:
   - Create a database named `vet_clinic`
   - Import `pets.sql` file into your database

3. Configure database connection:
   - Open `db.php`
   - Update credentials if needed (default: localhost, root, no password)

4. Start your local server:
   - Place the project in your web server directory (htdocs/www)
   - Access via `http://localhost/Vetpet-crud/`

##  Project Structure

```
Vetpet-crud/
├── index.php       # Main page - displays all pets
├── create.php      # Add new pet
├── update.php      # Edit pet details
├── delete.php      # Remove pet
├── db.php          # Database configuration
├── pets.sql        # Database schema
├── uploads/        # Pet images storage
└── pets/           # Additional resources
```

##  Usage

1. Visit the main page to view all registered pets
2. Click "Add New Pet" to register a new pet
3. Use "Edit" button to update pet information
4. Use "Delete" button to remove a pet record
5. Toggle dark/light mode using the switch in the navbar

## 📝 License

Open source - feel free to use and modify!

---

Made with ❤️ for veterinary clinics

