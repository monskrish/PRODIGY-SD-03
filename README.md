# Contact Management System 📒

This project is a **Contact Management System** implemented in Python. It allows users to manage a list of contacts by adding, editing, deleting, and displaying contact information. The data is stored in a CSV file for persistence.

---

## Features 🚀

- **Display Contacts**: View all saved contacts in a tabular format.
- **Add Contact**: Add a new contact with a name, phone number, and email address.
- **Edit Contact**: Update an existing contact's phone number or email address.
- **Delete Contact**: Remove a contact from the list.
- **Save Contacts**: Save all changes to the `contacts.csv` file.
- **Persistent Storage**: Contacts are stored in a CSV file, ensuring data is retained between program runs.

---

## How to Use 🛠️

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/contact-management-system.git
   cd contact-management-system
   ```

2. Run the script:
   ```bash
   python contact_management_system.py
   ```

3. Follow the prompts in the menu to manage your contacts.

---

## CSV File Structure 📂

The application uses a CSV file named `contacts.csv` to store contact details. Each row in the file represents a contact with the following fields:

- **Name**: The contact's name.
- **Phone**: The contact's phone number.
- **Email**: The contact's email address.

If the file does not exist, it will be created automatically when saving contacts.

---

## Requirements 📋

- Python 3.6 or higher.

No additional libraries are required as the project relies on Python's built-in `csv` and `os` modules.

---

## Example Workflow 🖥️

1. **Adding a Contact**:
   ```
   Enter Name: John Doe
   Enter Phone: 1234567890
   Enter Email: john.doe@example.com
   Contact added successfully.
   ```

2. **Displaying Contacts**:
   ```
   Contact List:
   Name                 Phone           Email
   ---------------------------------------------------------------
   John Doe             1234567890      john.doe@example.com
   ---------------------------------------------------------------
   ```

3. **Editing a Contact**:
   ```
   Enter the name of the contact to edit: John Doe
   Editing Contact: John Doe
   Current Phone: 1234567890
   Current Email: john.doe@example.com
   Enter new Phone (leave blank to keep current): 0987654321
   Enter new Email (leave blank to keep current): 
   Contact updated successfully.
   ```

4. **Deleting a Contact**:
   ```
   Enter the name of the contact to delete: John Doe
   Contact deleted successfully.
   ```
