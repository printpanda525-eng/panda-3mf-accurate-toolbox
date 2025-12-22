# panda-3mf-accurate-toolbox
⚠️ This repository is used for documentation and issue tracking only. The Panda 3MF Accurate Toolbox source code is not publicly available.

# Panda 3MF Accurate Toolbox

**Panda 3MF Accurate Toolbox** is a professional Blender addon focused on accurate and reliable **3MF import/export workflows for real-world 3D printing**.

This addon is designed for users who need precise scale handling, clean export pipelines, and batch workflows directly inside Blender, without relying on external conversion tools.

---

## 🔧 Key Features

- **3MF Import / Export**
  - Import and export 3MF files directly in Blender.
  - Quick export workflow using the current `.blend` file location.
  - Optional ignoring of artistic transforms for print-accurate geometry.

- **Batch Export by Build Plates**
  - Export multiple build plates in a single operation.
  - Each plate is exported as a separate 3MF file.
  - Automatic validation against build plate dimensions.

- **Virtual Build Plate**
  - Visualize a printer build plate directly inside Blender.
  - Helps organize and prepare models before slicing.
  - Designed as a visual aid, not a slicer replacement.

- **Transform Tools for 3D Printing**
  - Align objects to the build surface (Z axis).
  - Reset and apply transforms safely.
  - Prepare geometry for reliable slicing and printing.

- **Real Size Measurements**
  - Display accurate X / Y / Z dimensions in millimeters.
  - Values match slicer dimensions for scale verification.

---

## 🧩 Typical Workflow

1. Model or import geometry into Blender.
2. Verify real-world size using the Measurements panel.
3. Align objects and apply transforms if needed.
4. (Optional) Use the Virtual Build Plate to organize parts.
5. Export using **Export 3MF** or **Export Plates**.
6. Open the exported file in your preferred slicer (Orca, Bambu Studio, PrusaSlicer, Cura, etc.).

---

## ⚠️ Limitations

- This addon **does not fix geometry** or make models printable.
- No automatic detection or correction of non-manifold meshes.
- Final print validation is always performed by the slicer.
- Geometry is exported exactly as it exists in the Blender scene.

---

## 🆓 Free vs Accurate Version

| Feature | Panda 3MF Toolbox (Free) | Panda 3MF Accurate Toolbox |
|------|--------------------------|----------------------------|
| Basic 3MF Export | ✔ | ✔ |
| Batch Export (Plates) | ✖ | ✔ |
| Virtual Build Plate | ✖ | ✔ |
| Transform Tools | Limited | ✔ |
| Real Size Measurements | ✔ | ✔ |
| Advanced Workflow Tools | ✖ | ✔ |

---

## 📦 Availability

- **Free Version**  
  Available through **Blender Extensions**.

- **Panda 3MF Accurate Toolbox (Paid Version)**  
  Available via Gumroad (link below).

---

## 🛒 Purchase

You can purchase the **Panda 3MF Accurate Toolbox** here:

👉 *(Add your Gumroad link here)*

---

## 🐞 Bug Reports & Support

This repository is used for:
- Documentation
- Issue tracking
- User support

⚠️ **The source code of Panda 3MF Accurate Toolbox is not publicly available.**

If you encounter a bug or unexpected behavior, please open an issue and include:
- Blender version
- Operating system
- Steps to reproduce the problem

---

## 📄 Documentation

A full user manual (PDF) is included with the paid version of the addon.

---

## © Credits

Developed and maintained by **Panda Print**.

