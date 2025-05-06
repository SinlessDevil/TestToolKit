# 🧪 TestToolKit for Unity

A lightweight Unity Editor tool for running and managing Edit Mode tests. Built to simplify local test workflows and ensure project integrity through key validation checks.

![Test Window](https://github.com/SinlessDevil/TestToolKit/blob/main/Images/Window.png)

---

## ✨ Features

- 🧩 **Simple GUI** for launching Edit Mode tests from the Unity Editor  
- ⚙️ **Toggle Tests** via `[Ignore]` attribute directly in the code  
- 🧼 **Quick Filtering**: isolate or enable only relevant checks  

---

## ✅ Built-in Tests

| Category            | Description                                                  |
|---------------------|--------------------------------------------------------------|
| 🔁 GUID Validator    | Detects duplicate GUIDs in `.meta` files                     |
| 🧱 Resources Checker | Finds prefabs with missing scripts in `Resources/` folder    |
| 🎭 Scene Validator   | Checks for broken scenes: missing prefabs, components, etc.  |

---

## 📦 Installation

Simply clone or copy the folder into your Unity project (recommended under `Plugins/` or `Editor/`).  
The tool is accessible via `Tools > TestToolKit`.

| Test Name                          | Purpose                                                                                                                        |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------|
| ✅ `GuidDuplicationTest`            | Ensures all `.meta` files have unique GUIDs. Prevents asset conflicts.                                                        |
| ✅ `ResourcesPrefabValidationTests` | Checks all prefabs in `Resources/` folder for missing scripts or broken links.                                                |
| ✅ `SceneValidationTests`           | Validates all scenes in the project for: <br>• Missing scripts <br>• Missing prefab references <br>• Serialized `null` fields |
