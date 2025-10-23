# 📱 VeriCode
VeriCode — a modern QR Code Generator that does more than just make QR codes! Create encrypted, colorful, and logo-embedded QR codes, or generate hundreds at once from a spreadsheet — wrapped in a clean Tkinter (ttkbootstrap) UI with dark mode support.
<br>
<br>
<br>
# ✨ Features of VeriCode
  - Quick QR Generation – Instantly create QR codes for any text, link, or file with just one click.
  - Customization Options – Personalize your QR codes by changing colors, adding logos, and choosing from multiple save formats (PNG, JPG, PDF).
  - Secure QR Codes – Protect sensitive data with password-based encryption so only authorized users can access it.
  - Batch Processing – Upload Excel or CSV files to generate multiple QR codes automatically for bulk use.
  - Smart and Modern Interface – Enjoy a clean, scrollable UI with light/dark mode, file uploads, and QR scanning support—all designed with ttkbootstrap for a smooth experience.
<br>
<br>

# 🎥 Demo Video <br>
https://github.com/user-attachments/assets/82398aa3-68dd-45cf-be1e-ff21dbbc163b <br>
https://github.com/user-attachments/assets/d07d741a-9857-47dd-85b4-a07d5dbad17c
<br>
<br>

# 🖼️ Screenshots  
![lightmode](https://github.com/user-attachments/assets/1417c9d9-aad8-44af-9ab4-f4a28f4abc71)
![darkmode](https://github.com/user-attachments/assets/8ee09e0d-0d18-4772-8fcd-b7c89f46aebf)
![gqr](https://github.com/user-attachments/assets/5069af39-074d-4ca3-b203-49497b2a15c0)
<br>
<br>

# 🧠 Tech Stack

| Category             | Technologies Used                    |
| -------------------- | ------------------------------------ |
| **Language**         | Python                               |
| **GUI Framework**    | Tkinter + ttkbootstrap               |
| **QR Generation**    | `qrcode`                             |
| **Image Processing** | `Pillow (PIL)`                       |
| **Scanning**         | `OpenCV (cv2)`                       |
| **Encryption**       | `cryptography` (Fernet + PBKDF2HMAC) |
| **File Handling**    | `pandas`, `csv`, `os`, `fpdf`        |
| **UI Enhancements**  | `ttkbootstrap`, `ScrolledFrame`      |
<br>
<br>

# 🔄 Workflow
- Launch VeriCode <br>
  - Open the application and choose between the Generate QR or Scan QR tab.

- Generate QR Code<br>
  - Enter text or upload a file containing the data you want to encode.
  - (Optional) Add a password to encrypt the data for extra security.
  - Customize the QR by selecting foreground/background colors or adding a logo.
  - Click Generate QR to create your code and preview it instantly.

- Batch QR Generation<br>
  - Upload an Excel or CSV file containing multiple entries.
  - Choose the column (e.g., Roll Number or ID) to name each QR file.
  - Generate and save all QR codes automatically in a selected folder.

- Save or Export<br>
  - Save your generated QR code as a PNG, JPG, or PDF file.
  - Choose your desired location and format with one click.

- Scan QR <br>
  - Upload a QR image to decode its content.
  - If it’s password-protected, enter the password to view the decrypted data.
  - The result will be displayed instantly within the app.
<br>
<br>

# ⚙️ Installation & Setup
- Clone the repository <br>
  - git clone https://github.com/<your-username>/VeriCode.git
  - cd VeriCode

- Install dependencies <br>
  - pip install -r requirements.txt 

- Run the app <br>
  - python main.py
