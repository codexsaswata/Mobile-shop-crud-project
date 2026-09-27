# 📱 Mobile Shop CRUD Project

A simple **Mobile Shop Management System** built using Python.

This project demonstrates the basic **CRUD operations**:

- **C** → Create / Add Mobile
- **R** → Read / Display and Search Mobile
- **U** → Update Mobile
- **D** → Delete Mobile

The project uses a **Python list** to store mobile records.

---

## 🚀 Features

1. Add Mobile
2. Display All Mobiles
3. Search Mobile
4. Update Mobile
5. Delete Mobile
6. Exit

---

## 🛠️ Technologies Used

- Python 3
- Lists
- Functions
- Loops
- Conditional Statements
- `match-case`
- User Input

---

## 📂 Data Structure

Each mobile is stored as a list in the following format:

```python
[id, brand, model, price, quantity]
Example
[101, "Samsung", "Galaxy A55", 35000, 5]

Where:

Field	Description
ID	Unique mobile ID
Brand	Mobile brand
Model	Mobile model
Price	Price of the mobile
Quantity	Available quantity
📋 Menu

When the program starts, the following menu is displayed:

=============================================
       MOBILE SHOP MANAGEMENT
=============================================
1. Add Mobile
2. Display All Mobiles
3. Search Mobile
4. Update Mobile
5. Delete Mobile
6. Exit
=============================================
➕ Add Mobile

The user can add a new mobile by providing:

Mobile ID
Brand
Model
Price
Quantity

Example:

Enter Mobile ID: 101
Enter Brand: Samsung
Enter Model: Galaxy A55
Enter Price: 35000
Enter Quantity: 5

Mobile added successfully.

The record is stored as:

[101, "Samsung", "Galaxy A55", 35000, 5]
📋 Display All Mobiles

Displays all mobile records stored in the list.

Example:

ID      Brand          Model               Price          Quantity
---------------------------------------------------------------------------
101     Samsung        Galaxy A55          35000.00       5
102     Apple          iPhone 15           65000.00       3
103     OnePlus        Nord 4              30000.00       7
🔍 Search Mobile

A mobile can be searched using its unique Mobile ID.

Example:

Enter Mobile ID to search: 101

Mobile Found!
Mobile ID : 101
Brand     : Samsung
Model     : Galaxy A55
Price     : 35000
Quantity  : 5
✏️ Update Mobile

The user can update the details of an existing mobile.

The following information can be updated:

Brand
Model
Price
Quantity

Example:

Enter Mobile ID to update: 101

Mobile Found.

Current Brand    : Samsung
Current Model    : Galaxy A55
Current Price    : 35000
Current Quantity : 5

Enter New Details
Enter New Brand: Samsung
Enter New Model: Galaxy A56
Enter New Price: 40000
Enter New Quantity: 8

Mobile updated successfully.
🗑️ Delete Mobile

A mobile can be deleted using its Mobile ID.

The program asks for confirmation before deleting the record.

Do you want to delete this mobile? (Y/N): Y

Mobile deleted successfully.
▶️ How to Run
1. Clone the repository
git clone https://github.com/codexsaswata/Mobile-shop-crud-project.git
2. Open the project folder
cd Mobile-shop-crud-project
3. Run the Python program
python mobile_shop.py

Replace mobile_shop.py with the actual Python filename if your file has a different name.

📁 Project Structure
Mobile-shop-crud-project/
│
├── mobile_shop.py
└── README.md
🎯 Learning Objectives

This project was created to practice:

Python functions
Lists
for loops
while loops
if-elif-else
User input
Searching through lists
Updating list elements
Removing elements from lists
CRUD operations
Menu-driven programming
match-case
🔄 CRUD Mapping
Operation	Function	Python Concept
Create	add_mobile()	append()
Read	display_mobiles()	for loop
Search	search_mobile()	Loop + condition
Update	update_mobile()	List modification
Delete	delete_mobile()	remove()
👨‍💻 Author

Saswata Pati

B.Tech Information Technology

📌 Future Improvements

Possible improvements for this project:

Store data permanently using a database
Add MySQL connectivity
Add login authentication
Add stock management
Add billing functionality
Add customer management
Add input validation
Add a graphical user interface (GUI)
