# virtualbox-snapshot-restore
# virtualbox-snapshot-restore-project

## 🌀 Snapshot & Restore Testing (VirtualBox)

### 🎯 Description  
This project demonstrates how to take a VirtualBox snapshot before a system change (like installing software) and restore it afterward. This simulates what IT professionals do to protect systems from unwanted installs, updates, or malware.

Snapshots are essential for safely testing in virtual environments — especially when building an IT lab or trying risky tools.

---

### 🛠 Tools Used  
- VirtualBox  
- Windows 10 VM  
- Built-in Snapshot Tool  

---

### 🔍 What I Did  
1. **Took a Snapshot** before installing Zoom on my Windows 10 VM  
2. Installed Zoom  
3. Used **VirtualBox's Restore feature** to roll back the VM to its previous clean state  
4. Verified the app and changes were fully removed after restore

---

### 💡 Why It Matters  
- Snapshots let IT pros create clean restore points  
- Super useful before big changes, software installs, or malware testing  
- Speeds up recovery and avoids needing full reinstalls

---

### ✅ Outcome  
The snapshot successfully restored the system to its pre-install state. All Zoom files were gone, and performance returned to normal.

---

### 🧠 Related Skills  
- Virtualization  
- Snapshot Management  
- Troubleshooting & Rollback  
- Safe Test Environments  
