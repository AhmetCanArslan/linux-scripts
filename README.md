# 🐧 Linux Scripts Collection

A collection of useful Bash scripts for Linux automation and productivity tasks.

## 📁 Scripts Overview

### 📤 [sendClipboardtoDevice](./sendClipboardtoDevice/)
Send files, folders, or screenshots from your clipboard to connected devices via KDE Connect.

**Features:**
- Send files that are copied to clipboard directly to your device
- Automatically send latest screenshot when clipboard contains raw image data
- Works with any KDE Connect paired device
- Sends folders by compressing them into a zip archive before transfer

**Requirements:** KDE Connect, xclip

---

### 💻 [openWithVSCode](./openWithVSCode/)
Open files and folders with Visual Studio Code from file manager or desktop shortcuts.

**Features:**
- Handle file:// URIs from file managers
- Decode URL-encoded paths (spaces, special characters)
- Open each path in a new VS Code window
- Support for multiple file/folder selection

**Requirements:** Visual Studio Code

---

### 🔄 [convertPptxtoPdf](./convertPptxtoPdf/)
Convert Microsoft PowerPoint (.pptx) files to PDF using LibreOffice.

**Features:**
- Converts `.pptx` to `.pdf`.
- Uses LibreOffice `soffice` command.
- Supports batch conversion.
- Outputs PDF in the same directory as the source.

**Requirements:** LibreOffice

---

## 📝 Usage

Each script folder contains its own detailed README with specific installation and usage instructions. Navigate to the respective folder for more information.

## 🤝 Contributing

Feel free to add new scripts or improve existing ones. Each script should:
- Have its own folder with descriptive name
- Include a detailed README.md
- Follow consistent naming conventions
- Be well-commented and documented
