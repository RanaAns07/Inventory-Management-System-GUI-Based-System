# Inventory Management System

A desktop application for managing product inventory, built with Python and Tkinter. This system allows users to add, update, and report on products, with a user-friendly dashboard and authentication (login/signup) features.

## Features

- **Login & Signup:** Secure authentication for users.
- **Dashboard:** Visual overview of inventory and product sales.
- **Add Product:** Add new products to the inventory.
- **Update Product:** Modify existing product details.
- **Generate Reports:** Create and view inventory reports.
- **Data Visualization:** Product sales chart using Matplotlib.
- **Modern UI:** Styled with custom fonts and images.

## Project Structure

```
Inventory Management System/
│
├── add_and_del_product.py      # Add/Update product logic
├── dashboard.py                # Main dashboard window
├── Login_window.py             # Login window UI and logic
├── signup.py                   # Signup window UI and logic
├── temp_database.py            # Temporary in-memory database and chart display
├── menu_logo.png               # Logo image for dashboard
├── requirement.txt             # Python dependencies
└── invent/                     # Python virtual environment (optional)
```

## Installation

1. **Clone the repository:**
   ```bash
   git clone (https://github.com/RanaAns07/Inventory-Management-System-GUI-Based-System.git)
   cd "Inventory Management System"
   ```

2. **(Optional) Create a virtual environment:**
   ```bash
   python3 -m venv invent
   source invent/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirement.txt
   ```

4. **Install Tkinter (if missing):**
   ```bash
   sudo apt-get install python3-tk
   ```

## Usage

1. **Run the application:**
   ```bash
   python Login_window.py
   ```
   - The login window will appear first.
   - After successful login/signup, the dashboard will be displayed.

2. **Dashboard Features:**
   - Add, update, and report on products using the left menu.
   - View product sales chart in the dashboard.

## Requirements

- Python 3.12+
- Tkinter
- Pillow
- Matplotlib
- See `requirement.txt` for all dependencies.

## Troubleshooting

- **Blank Small Window:** If you see a blank window, ensure you start the app from `Login_window.py` and not `dashboard.py`.
- **Tkinter Error:** If you get a `ModuleNotFoundError: No module named 'tkinter'`, install it using your system package manager (see Installation).
- **Image Not Found:** Ensure `menu_logo.png` is present in the project directory.

## Contact

Inventory Management System by Ans Mustafa  
Contact: ranaans.pk@gmail.com
