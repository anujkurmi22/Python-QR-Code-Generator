# Python-QR-Code-Generator
#  Python QR Code Generator

A beginner-friendly Python project that generates QR codes using the Python `qrcode` library.

This repository contains two mini-projects:

1. **URL QR Code Generator**
2. **UPI Payment QR Code Generator**

Both projects demonstrate how Python can be used to generate QR codes and save them as image files.

---

##  Projects Included

### 1. URL QR Code Generator

**Python File:** `QR_code_generate.py`

This project generates a QR code from a website URL entered by the user.

**Features:**

- Accepts a URL from the user.
- Generates a QR code automatically.
- Saves the QR code as a PNG image.
- Easy to use and beginner-friendly.

**Output:** `qrcode.png`

### 2. UPI Payment QR Code Generator

**Python File:** `QR_UPI_code_generate.py`

This project generates UPI payment QR codes using the user's UPI ID and payment amount.

**Features:**

- Takes UPI ID as input.
- Takes payment amount as input.
- Generates QR codes for different payment apps.
- Saves QR codes as separate PNG images.

**Generated Images:**

- `phonepe_qr.png`
- `paytm_qr.png`
- `google_pay_qr.png`

**Note:** The current Paytm and Google Pay URL formats need correction and testing before actual payment use.

---

##  Technologies Used

- Python
- QR Code Library
- Pillow

---

##  Installation

First, install Python 3 on your system.

Install the required library using:

```bash
pip install "qrcode[pil]"
```

---

##  How to Run the Projects

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Open the project folder**

```bash
cd Python-QR-Code-Generator
```

**3. Run the URL QR Code Generator**

```bash
python QR_code_generate.py
```

**4. Run the UPI Payment QR Code Generator**

```bash
python QR_UPI_code_generate.py
```

---

##  Project Structure

```text
Python-QR-Code-Generator/
│
├── QR_code_generate.py
│
├── QR_UPI_code_generate.py
│
└── README.md
```

---

##  Learning Outcomes

Through these projects, I learned:

- Python user input handling.
- Importing and using external libraries.
- Generating QR codes.
- Working with URLs and UPI payment links.
- Saving generated images using Python.

---

## Future Improvements

- Add input validation.
- Add error handling.
- Allow users to customize QR code colors.
- Add a modern graphical user interface (GUI).
- Improve UPI QR code generation.

---

## Disclaimer

These projects are created for educational and learning purposes.

Always verify the UPI recipient details and payment amount in your payment application before approving any transaction.

---

##  Author

**Anuj Kurmi**

Python Developer | Computer Science Graduate

GitHub: Add your GitHub profile link here.

---

 If you find this project useful, don't forget to give it a star!1
