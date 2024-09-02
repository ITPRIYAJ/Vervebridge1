
Invoice Generator Python project. 
# Invoice Generator using Tkinter and docxtpl

## Overview

This project is a simple invoice generator application built using Python's Tkinter for the graphical user interface (GUI) and docxtpl for generating invoices in Microsoft Word (.docx) format. The application allows users to input customer details, items, prices, and quantities, and then generate a professional invoice with a single click.

## Features

- *User-friendly Interface*: Built with Tkinter, making it easy for users to interact with the application.
- *Customizable Invoices*: Users can enter customer details and itemized lists to create personalized invoices.
- *Invoice Templates*: The application uses docxtpl to fill in predefined templates with user data.
- *Save and Print*: Generate invoices in .docx format, ready for printing or digital distribution.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- tkinter (usually included with Python)
- docxtpl (You can install it via pip: pip install docxtpl)

## Installation

1. *Clone the Repository*:
   bash
   git clone https://github.com/yourusername/invoice-generator-tkinter.git
   cd invoice-generator-tkinter
   

2. *Install Dependencies*:
   bash
   pip install -r requirements.txt
   
   *(Ensure that docxtpl is listed in requirements.txt)*

3. *Run the Application*:
   bash
   python invoice_generator.py
   

## Usage

1. *Open the Application*:
   After running the script, the Tkinter window will appear.

2. *Enter Invoice Details*:
   - Input customer name, address, contact details, and other relevant information.
   - Add items to the invoice by specifying the item name, quantity, and price.

3. *Generate Invoice*:
   - Click on the "Generate Invoice" button to create a .docx file.
   - The file will be saved in the specified directory.

4. *View and Print Invoice*:
   - Open the generated .docx file with Microsoft Word or any compatible software.
   - Print or share the invoice as needed.

## Template Customization

If you wish to customize the invoice template:

1. Open the invoice_template.docx file located in the templates directory.
2. Modify the template according to your needs using Microsoft Word or another compatible editor.
3. Ensure the placeholders match the data fields used in the docxtpl script.

## Contribution

Contributions are welcome! If you have ideas for improvements or find bugs, please submit an issue or a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries, please contact [Your Name] at [dharshinijayprakash@gmail.com].
