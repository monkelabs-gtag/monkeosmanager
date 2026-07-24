#  Monke OS Manager

Monke OS Manager is a Gorilla Tag mod that allows you to run MonkeOS operating systems created by **monkelabs-gtag**.

> **Note:** Only officially supported MonkeOS packages are compatible with Monke OS Manager.

---

##  Requirements

- Windows 11
- Steam
- Gorilla Tag (PCVR)
- BepInEx
- Utilla
- Steam Link (or another PCVR method)

---

##  Installation

1. Download the latest **Monke OS Manager** `.zip` file.
2. Extract the contents to:

```
C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag\BepInEx\plugins
```

> **Important:** If this is your first time using BepInEx, launch Gorilla Tag once, wait until you spawn in the Stump, then close the game. The `plugins` folder will be created automatically.

---

##  Installing a MonkeOS

1. Download a supported MonkeOS (`.dll` file).
2. Open the `OSValue` folder inside your `plugins` directory.
3. Copy the `.dll` file into the `OSValue` folder.
4. Launch Gorilla Tag.

Monke OS Manager will automatically detect and load the installed operating system.

---

##  Folder Structure

```
BepInEx
└── plugins
    ├── MonkeOSManager.dll
    └── OSValue
        ├── MonkeOS1.dll
        ├── MonkeOS2.dll
        └── ...
```

---

## 📄 License

This project is maintained by **monkelabs-gtag**.
