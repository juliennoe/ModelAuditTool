# 🧱 Model Audit Tool

A Unity Editor tool that scans and audits all 3D model prefabs in your project.  
It helps technical artists and developers visualize and sort models based on optimization-related metrics.

---

## ✨ Features

- 🔍 Scans all prefabs for:
  - Vertex count
  - Triangle count
  - Material usage
  - LOD levels
  - Colliders
  - Static flags
  - Addressable status
  - File size & estimated memory usage
- 🧠 Sorting, searching & column toggles
- 📁 Ping prefabs directly in Project window
- 🧵 Responsive UI with scrollable views
- 💾 Persists UI state across sessions

---

## 📦 Installation

1. Copy the tool into your Unity project under `Assets/Editor/ModelAuditTool`.
2. Or use Unity Package Manager with this Git URL:  
   `https://github.com/juliennoe/ModelAuditTool.git`

---

## 🖥️ How to Use

- Open the tool via `Tools > Model Audit`.
- Click **"Scan All Prefabs"** to generate results.
- Use column toggles and sorting to organize data.
- Click on a prefab name to ping it in the Project panel.

---

## 🆘 Help

Click the `Help ▶` button in the top-right corner of the tool for a quick reminder.

---

## 🧪 Requirements

- Unity 2020.3+
- Addressables package (`com.unity.addressables`)

---

## 📜 License

MIT — see `LICENSE` file for details.
