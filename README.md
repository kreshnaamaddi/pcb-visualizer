# pcb-visualizer


````markdown
# 🧠 PCB Design Visualizer (Via, Trace, Backdrill, D2M, BD2M Simulator)

This project is a lightweight PCB design visualizer built using **Python (`pygame` + `tkinter`)**. It helps hardware engineers and PCB designers **visually simulate and validate** key board design elements like:

- 🕳️ Vias (drill, pad, antipad)
- 📏 Traces (copper lines)
- 🔧 Backdrills & Backdrill Antipads
- 📐 D2M (Drill to Metal) & BD2M (Backdrill to Metal) clearance check

---

## ✨ Features

- Visualize **two vias** (each with 3 concentric zones: drill, pad, and antipad)
- Add **two traces** (rectangles) between/around vias
- User-defined distances and positions
- Graph is centered (logical range from -50 to +50 units)
- Easy visualization for discussing with customers or teammates

---

## 📷 UI Preview

*Added in resources folder*

---

## ⚙️ Technologies Used

- `pygame` – for real-time 2D rendering
- `tkinter` – for input/config UI

---



## ✅ Use Case

This tool is helpful for:

* Quickly sketching and validating PCB stack elements
* Communicating **design intent or clearance violations** during early discussions
* Saving time instead of manual paper sketches

---

## 🧠 Future Enhancements (Ideas)

* Add auto-validation for D2M / BD2M violations
* Export snapshots as images/PDFs
* Layer-wise visualization


---

