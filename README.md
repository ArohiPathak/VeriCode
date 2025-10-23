# 📱 VeriCode
VeriCode — a modern QR Code Generator that does more than just make QR codes! Create encrypted, colorful, and logo-embedded QR codes, or generate hundreds at once from a spreadsheet — wrapped in a clean Tkinter (ttkbootstrap) UI with dark mode support.





# ✨ Features of VeriCode

  - Quick QR Generation – Instantly create QR codes for any text, link, or file with just one click.
  - Customization Options – Personalize your QR codes by changing colors, adding logos, and choosing from multiple save formats (PNG, JPG, PDF).
  - Secure QR Codes – Protect sensitive data with password-based encryption so only authorized users can access it.
  - Batch Processing – Upload Excel or CSV files to generate multiple QR codes automatically for bulk use.
  - Smart and Modern Interface – Enjoy a clean, scrollable UI with light/dark mode, file uploads, and QR scanning support—all designed with ttkbootstrap for a smooth experience.



  

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




# 🔄 Workflow

1. Launch VeriCode
  - Open the application and choose between the Generate QR or Scan QR tab.

2. Generate QR Code
  - Enter text or upload a file containing the data you want to encode.
  - (Optional) Add a password to encrypt the data for extra security.
  - Customize the QR by selecting foreground/background colors or adding a logo.
  - Click Generate QR to create your code and preview it instantly.

3. Batch QR Generation
  - Upload an Excel or CSV file containing multiple entries.
  - Choose the column (e.g., Roll Number or ID) to name each QR file.
  - Generate and save all QR codes automatically in a selected folder.

4. Save or Export
  - Save your generated QR code as a PNG, JPG, or PDF file.
  - Choose your desired location and format with one click.

5. Scan QR Code
  - Upload a QR image to decode its content.
  - If it’s password-protected, enter the password to view the decrypted data.
  - The result will be displayed instantly within the app.





# ⚙️ Installation & Setup

1. Clone the repository
- git clone https://github.com/<your-username>/VeriCode.git
- cd VeriCode

2. Install dependencies
- pip install -r requirements.txt 

3. Run the app
- python main.py
