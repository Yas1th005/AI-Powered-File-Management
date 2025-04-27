# AI File Assistant 🚀

An intelligent system for managing, searching, and interacting with your files using Natural Language.

## ✨ Features

- 🔥 **AI Terminal**: Run machine operations with simple English commands
- 📂 **AI File Management**: Auto-organize your downloads based on file content
- 🔎 **AI File Search**: Use a GUI to search files by typing natural queries

## 📥 Installation (First Time Setup)

1. Clone or download this repository
2. Open your terminal and navigate to the project directory
3. Run the installer script:
   ```bash
   bash ubuntu_installer.sh
   ```

The installer will automatically:

- Create a folder named `Trial3/`
- Inside it, you will find:
  - `file_manager.py`
  - `gui_final.py`
  - `terminal.py`
  - `files_info.db` (Database)
  - `home/` (Folder for file management)
- Open three terminals running:
  - AI Terminal
  - AI File Management
  - AI File Search

**✅ You're all set after this step!**

## 🚀 Running the Application (After Installation)

Every time after the first installation:

1. Navigate to the Trial3 directory:

   ```bash
   cd Trial3
   ```

2. Open three terminal windows and run:

   **AI Terminal**:

   ```bash
   python3 terminal.py
   ```

   **AI File Management**:

   ```bash
   python3 file_manager.py
   ```

   **AI File Search**:

   ```bash
   python3 gui_final.py
   ```

## 🛠️ How to Use

### 1. AI Terminal

- Run `terminal.py`
- Enter simple English commands like:
  - "Create a folder named Projects"
  - "Delete the file report.docx"
- The AI interprets and executes them automatically

### 2. AI File Management

- Save any downloaded files into the `home/` folder
- The system will:
  - Monitor for new files
  - Sort files based on content
  - Move files into existing folders or create new folders intelligently

### 3. AI File Search

- Run `gui_final.py` to launch the GUI
- Steps:
  1. Choose a directory to scan
  2. Click "Scan Directory"
  3. Enter a query like:
     - "Give me tech-related documents"
     - "Find all my reports"
  4. View the file paths and open files directly from the interface

## 📂 Project Structure

```
Trial3/
├── file_manager.py
├── gui_final.py
├── terminal.py
├── files_info.db
└── home/
```

## ⚡ Requirements

- Python 3.8 or higher
- Install dependencies if not already available:
  ```bash
  pip install watchdog tkinter
  ```

## 🖼️ Screenshots

| AI Terminal  | AI File Management | AI File Search |
| ------------ | ------------------ | -------------- |
| [screenshot] | [screenshot]       | [screenshot]   |
