
# Python Password Manager

A simple desktop password manager built with Python's Tkinter GUI library. Easily generate, save, and copy strong passwords for your accounts! Passwords are stored locally in a text file in a readable table format.

---

## Features
- Modern dark-themed interface
- Secure random password generator
- Copy generated passwords to clipboard
- Add new website/email/password entries
- Local text file storage for your passwords
- User-friendly error and confirmation dialogs

---

## Screenshots

### Main Screen
![image](https://github.com/user-attachments/assets/9f73351e-5585-454a-b9ed-addcb38c04e4)


---

## How It Works
1. Enter your website, email, and password (or generate a strong password).
2. Click **Add Password** to save the entry to `data.txt`.
3. All entries are appended to the file in table format.
4. The **Generate** button creates a strong random password and copies it to your clipboard automatically.

---

## Installation

1. Clone the repository or download the code files.
2. Install dependencies:
    ```bash
    pip install pyperclip prettytable
    ```
3. Place a logo image named `image.png` in the same directory.
4. Run the script:
    ```bash
    python main.py
    ```

---

## Dependencies
- Python 3.x
- Tkinter (included with standard Python installation)
- [prettytable](https://pypi.org/project/prettytable/)
- [pyperclip](https://pypi.org/project/pyperclip/)

---

## Example Entry (data.txt)
```
| example.com      | user@email.com           | gH8!jdK29&Lq   |
```

---

## License
MIT

---

## Author
Ecem Nur Özen

---

## Notes
- Your passwords are saved **unencrypted** in `data.txt`. For increased security, consider using an encrypted storage solution for sensitive data.

