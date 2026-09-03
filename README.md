# 🟢 GEEKLANDR — Landr OS

A lightweight **Home Lab & System Toolkit** built with Python and Tkinter.

GEEKLANDR provides a simple graphical interface for performing common system and networking tasks without having to type every command manually in a terminal.

---

## 🚀 Features

* 🖥️ **System Information**

  * Operating system
  * OS version
  * Machine architecture
  * Processor information
  * Python version

* 🌐 **IP Address**

  * Displays the system's network information

* 💾 **Disk Usage**

  * Checks available disk space
  * Displays disk usage information

* 🔐 **Password Generator**

  * Generates strong random passwords
  * Uses Python's secure random generation

* 📡 **Ping Tool**

  * Test connectivity to a host or IP address

* 🪟 **Graphical User Interface**

  * Built with Python Tkinter
  * Designed to be simple and easy to use

---

## 🖼️ Project

GEEKLANDR was created as a personal **home-lab / Linux system administration toolkit**.

The goal is to make common system tasks accessible through one simple GUI instead of requiring multiple terminal commands.

---

## 🛠️ Built With

* **Python 3**
* **Tkinter**
* **Pillow**
* **PyInstaller**

---

# 📥 Installation

## 1. Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Then enter the project directory:

```bash
cd YOUR-REPOSITORY
```

---

## 2. Create a Virtual Environment

It's recommended to use a Python virtual environment.

```bash
python3 -m venv venv
```

Activate it:

### Linux / Kali Linux

```bash
source venv/bin/activate
```

### Windows

```powershell
venv\Scripts\activate
```

---

## 3. Install Dependencies

Install the required Python packages:

```bash
pip install pillow pyinstaller
```

> **Note:** Tkinter may already be installed on your system. On Debian/Kali-based systems, you may need:

```bash
sudo apt install python3-tk
```

---

# ▶️ Running GEEKLANDR

Once the virtual environment is activated, run:

```bash
python3 LOS.py
```

Replace `LOS.py` with the name of the main Python file in your repository if it is different.

---

# 🔨 Building the Executable

GEEKLANDR can be packaged into a standalone executable using **PyInstaller**.

Example:

```bash
pyinstaller --onefile --windowed --name GEEKLANDR LOS.py
```

The finished executable will be placed inside:

```text
dist/
```

You can then run it without opening the Python source file.

---

# 📁 Project Structure

A typical project structure looks like this:

```text
GEEKLANDR/
│
├── LOS.py
├── geeklandr.png
├── README.md
│
├── venv/
│
├── build/
│
└── dist/
    └── GEEKLANDR
```

---

# 🖥️ Running the Compiled Version

After building the application:

```bash
cd dist
```

Then run:

```bash
./GEEKLANDR
```

If Linux reports that the file isn't executable:

```bash
chmod +x GEEKLANDR
```

Then:

```bash
./GEEKLANDR
```

---

# 🎯 Project Goals

GEEKLANDR was created to:

* Learn Python GUI development
* Practice Linux system administration
* Build useful home-lab tools
* Learn application packaging
* Learn how to distribute Python applications
* Create a practical toolkit for everyday system tasks

---

# ⚠️ Disclaimer

GEEKLANDR is intended for **educational purposes and authorized systems**.

The networking features should only be used on systems and networks that you own or have permission to test.

---

# 📌 Future Plans

Possible future features include:

* [ ] Network scanner
* [ ] Port checker
* [ ] DNS lookup
* [ ] Traceroute tool
* [ ] System monitoring
* [ ] CPU/RAM monitoring
* [ ] Process manager
* [ ] Network information dashboard
* [ ] Dark/light themes
* [ ] Linux desktop launcher
* [ ] Windows executable
* [ ] Configuration/settings panel

---

# 👨‍💻 Author

Created by **GEEKLANDR**

Built for learning, experimentation, and home-lab projects.

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

Thanks for checking out **GEEKLANDR — Landr OS!** 🟢
