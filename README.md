Brickfields Library Management System

Brickfields Library System is a Python-based library management application designed to streamline the management of library data, including administrators, librarians, members, books, and book loan processes. It provides different access levels for super administrators, administrators, librarians, and library members.


Files Used

admin.txt → Stores administrator information

member.txt → Stores member information

librarian.txt → Stores librarian information

book.txt → Stores book information

overdue.txt → Stores book loan records

librarianid.txt → Stores librarian login credentials

memberid.txt → Stores member login credentials


Usage Overview
Administrator Management

Add, view, search, edit, or remove administrator accounts.

Super administrators have full control, while regular administrators have limited access.

Member Management

Add, view, search, edit, or remove library members.

Members can update their own profile information.

Librarian Management

Add, view, search, edit, or remove librarian accounts.

Librarians can manage books and perform loan operations.

Book Management

Add, view, search, edit, or remove books.

Librarians handle book loan processes, including:

Checking loan eligibility

Recording borrowed books

Calculating overdue charges

Loan Process

Members can borrow up to 5 books.

Overdue charges are calculated based on the number of days a book is late:

Day 1 → $2.00

Day 2 → $3.00

Day 3 → $4.00

Day 4 → $5.00

Day 5 → $6.00

More than 5 days → $10.00

Login Credentials (Default)

Super Administrator Password: sAd@kl2024
Administrator Password: Ad@kl2024

Notes

All data is stored in plain text files (.txt), separated by semicolons (;).

The system performs input validation for login, book limit, and overdue checks.

Super administrators have exclusive rights for managing administrators.

Future Improvements

Add database support (e.g., SQLite or MySQL) for better data management.

Implement password hashing for security.

Add GUI interface using Tkinter or PyQt.

Include email notifications for overdue books.
