# invoice-management-system
A React-based Invoice Management System with CRUD operations, live calculations, and PDF export.

# 📄 Invoice Management System – React + Redux Toolkit - 

A complete, modern, and fully functional Invoice Management System built using React, Redux Toolkit, and React Bootstrap.
This system allows users to:

✔ Create invoices
✔ Edit invoices
✔ Delete invoices
✔ Copy invoices
✔ Preview invoices
✔ Download as PDF
✔ Manage multiple line items
✔ Auto-calculate totals, tax, and discounts
✔ Navigate through invoices via pagination

# 🚀 Features - 
🔹 1. Create, Edit, and Delete Invoices
Easily manage invoices with full CRUD operations powered by Redux Toolkit.

🔹 2. Dynamic Invoice Form
Live subtotal calculation
Auto tax & discount calculation
Line item add/remove
Real-time field updates

🔹 3. PDF Download
Uses html2canvas + jsPDF to convert the invoice preview into a professional printable PDF.

🔹 4. Invoice Duplication
Duplicate any invoice instantly with a new unique invoice ID.

🔹 5. Pagination Support
Improves usability when handling large invoice lists.

🔹 6. Modern UI
Clean and fully responsive layout built using React Bootstrap.


# 📦 Tech Stack Used -

React

* Redux Toolkit
* React Router
* React Bootstrap
* Bootstrap
* JavaScript (ES6+)
* html2canvas
* jsPDF
* React Icons
* UUID

# 📁 Folder Structure - 
<img width="941" height="653" alt="image" src="https://github.com/user-attachments/assets/9689b242-3e8e-4fc6-a30e-d5e2a24616f9" />

# ⚙️ Installation & Setup -
 1. Clone the repository

 2. Install all dependencies
     # npm install

 3. Start the development server
     # npm start

# 📘 How PDF Generation Works

* The invoice preview is rendered inside #invoiceCapture.
* html2canvas converts the HTML to a canvas image.
* jsPDF embeds the canvas into a PDF file.
* User can download the invoice as a high-quality PDF.

# 🔮 Future Improvements

* Add backend (Node.js + MongoDB)
* Add authentication
* Add file upload (invoice images/PDFs)
* Export invoices as Excel
* Add dark mode
* Cloud deployment


# Application Preview - 
<img width="1897" height="876" alt="Screenshot 2025-11-17 154901" src="https://github.com/user-attachments/assets/6ca688da-3399-478f-9e93-582391471c4f" />
<img width="1903" height="876" alt="Screenshot 2025-11-17 154919" src="https://github.com/user-attachments/assets/aa1931f5-cba8-43c3-9fc5-bef370de7238" />
<img width="1919" height="882" alt="Screenshot 2025-11-17 155131" src="https://github.com/user-attachments/assets/2bf709a3-9632-44c4-abba-3f588125bd16" />





