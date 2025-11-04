# Pavan_Avenger

A custom **Unreal Engine 5** plugin that provides **complete read and write access** to Android’s local file system.  
This plugin enables developers to manage files across **internal and external storage**, including creating, reading, writing, copying, and deleting files directly from **Blueprints** or **C++**.

---

## 🚀 Features

- 📁 Read and write **text**, **JSON**, and **binary** files  
- 📂 Access both **internal** and **external** Android storage  
- 🔄 Copy, move, and delete files or folders  
- 🔍 Check file or directory existence  
- 📜 Retrieve folder contents (directory listing)  
- 🧩 Simple **Blueprint nodes** and **C++ API**  
- 🧠 Optimized for **Android and Meta Quest 2 / Quest 3**  
- ⚡ Lightweight — **no third-party dependencies**

---

## 🧰 Installation

### Option 1 — Project Plugin
1. Download or clone this repository.  
2. Copy the folder `Pavan_Avenger` into your Unreal project’s `Plugins` directory:
YourProject/
├── Plugins/
│ └── Pavan_Avenger/

markdown
Copy code
3. Open your project in **Unreal Engine**.  
4. Go to **Edit → Plugins**, search for `Pavan_Avenger`, and enable it.  
5. Restart Unreal Engine to apply changes.

### Option 2 — Engine Plugin (Optional)
If you want to make it available to all Unreal projects:
1. Copy the plugin folder into:
UnrealEngine/Engine/Plugins/

markdown
Copy code
2. Enable it from the Plugin Browser in any project.

---

## 🧩 Usage

### 📘 Blueprint Example
1. In your Blueprint, search for the provided nodes:
- **Write File to Android Storage**
- **Read File from Android Storage**
- **File Exists**
- **Delete File**
- **List Files in Directory**
2. Set the **file path** and **data** to read/write.
3. Run the project on an **Android device** or **Meta Quest headset**.

⚙️ Supported Platforms
✅ Android (All versions)

✅ Meta Quest 2 / Quest 3

✅ Unreal Engine 5.0 and above

🧪 Tested Configuration
Unreal Engine: 5.3.2

Devices: Meta Quest 3, Android Phones

Build Type: Android (Multi / ASTC)

📄 License
This project is licensed under the MIT License — free to use, modify, and distribute.

💡 Author
Pavan Sai Eedarada
Unreal Developer | Virtual Production & XR Specialist
+91 7981532487

⭐ Contributions
Pull requests, bug fixes, and feature suggestions are welcome!
If this plugin helps you, please star the repository and share it with the Unreal community.
