<div align="center">

<h1>⚡ Pather v3.10b</h1>

<p>Step-by-step installation and activation guide</p>

![Version](https://img.shields.io/badge/Version-3.10b-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-informational?style=for-the-badge&logo=windows)
![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

</div>

---

## 📋 Requirements

| Requirement | Details |
|---|---|
| 🪟 **OS** | Windows 10 / 11 |
| 🔷 **PowerShell** | Version 5.1 or higher |
| 🗂️ **Files** | Extracted anywhere (Desktop works fine) |
| 🌐 **Internet** | Required during setup |

---

## 🚀 Installation

### Step 1 — Download the files

Download the Pather v3.10b archive and extract the contents.  
You can place the folder anywhere — putting it on the **Desktop** is perfectly fine.

> **ℹ️ Note:** The files will work correctly from the Desktop. No need to move them to any system folder.

---

### Step 2 — Check PowerShell version

Open PowerShell (search `powershell` in the Start menu) and run:

```powershell
$PSVersionTable.PSVersion
```

Expected output:

```
Major  Minor  Build  Revision
-----  -----  -----  --------
5      1      ...    ...
```

> **⚠️ Warning:** If `Major` is less than **5**, update PowerShell before continuing.  
> Download it from [microsoft.com/powershell](https://learn.microsoft.com/powershell).

---

### Step 3 — Run the activation command

In the same PowerShell window, paste and run:

```powershell
# YOUR COMMAND HERE
```

> **ℹ️ Note:** Run PowerShell as the same user who will be using Pather. Administrator rights are not required.

---

### Step 4 — Verify the installation

Once the activation command finishes, confirm everything installed correctly:

```powershell
# YOUR VERIFICATION COMMAND HERE
```

If successful, you will see a confirmation message in the terminal.

> **✅ Done:** Pather v3.10b is ready to use.

---

## 📁 File Structure

```
Pather-v3.10b/
├── ...       ← your files here
└── ...
```

---

## ❓ Troubleshooting

<details>
<summary><strong>PowerShell says "execution policy" error</strong></summary>

Run this command first, then retry:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

</details>

<details>
<summary><strong>Command is not recognized</strong></summary>

Make sure you are running the command from the correct PowerShell window and that the files are properly extracted (not still inside a `.zip` archive).

</details>

<details>
<summary><strong>Verification step fails</strong></summary>

Try closing and reopening PowerShell, then run the verification command again.

</details>

---

## 📄 License

For personal use only. Redistribution is not permitted without permission.

---

<div align="center">
  <sub>Pather v3.10b &nbsp;·&nbsp; Installation Guide &nbsp;·&nbsp; For support, contact the author</sub>
</div>
