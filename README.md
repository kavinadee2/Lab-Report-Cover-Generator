# University  Lab Cover Page Architect 📐

A high-fidelity, engineering-grade web utility designed to automatically generate lab report cover pages with micro-millimetric precision. This tool was built specifically to eliminate formatting errors and guarantee absolute compliance with strict academic drafting standards.

🚀 **[CLICK HERE TO ACCESS THE LIVE GENERATOR](https://kavinadee2.github.io/Lab-Report-Cover-Generator/)**

---

## 💎 Locked Engineering Specifications

This architect automatically validates the exact millimetric values required by strict university submission guidelines:

* **Sheet Margins Box**: Exactly **15mm Left margin** (for folder binding) and **12mm on all other sides** (Top, Right, Bottom).
* **Experiment Title**: Anchored symmetrically inside margins with an automated vertical center alignment engine. Characters are scaled to **10mm Height × 8mm Width** with a **1mm inter-character gap**. Text lines are separated from their corresponding underlines by an exact **1mm clearance gap**.
* **Student Credentials**: Perfectly left-aligned to the starting coordinate of the student's name.
    * **Student Name**: Rendered at **5mm Height × 4mm Width** with a **1mm gap**. The trailing character/dot rests exactly **10mm away from the right margin line**.
    * **Metadata Blocks (Reg No, Group, Semester, Date)**: Scaled to standard drafting parameters of **4mm Height × 3mm Width** with a **1mm gap**.
* **Cascading Clearances**: Underlines fit individual word lengths. Vertical gaps between a field's underline and the subsequent line of text are locked at **3mm**. The final clearance from the Submission Date underline to the bottom margin line is locked at exactly **15mm**.

---

## 🌟 Key Features

* **Draftsman's Spacing Engine (Kerning)**: Dynamically rescales bounding boxes for narrow symbols and digits (such as `1`, `I`, `/`, and `.`), keeping the real, physical stroke-to-stroke gap inside a word at exactly 1mm without awkward extra padding.
* **Aesthetic Character Overhaul**: Implements premium technical stroke configurations with fully unslashed, wide loop profiles for `0` (Zero), unified high-density loops for `8`, and clean structural drafting geometry for `6` and `9`.
* **Millimeter CAD Annotation HUD**: Toggling **"Sizing Guidelines"** projects a real-time, multi-colored dimension overlay across your canvas (Blue for boundaries, Red for Title, Green for Name, Yellow for metadata tags) to allow absolute visual validation before exporting.
* **Privacy First & Offline-Locked**: Does not connect to a central database or log private user telemetry. The **"Save Profile Credentials"** button securely holds profile configurations right inside your personal web browser using localized browser memory (`localStorage`).
* **Mathematical Vector Exports**: Exports flawless blueprints directly to lossless vector `.pdf` and engineering-compliant `.svg` formats.

---

## 🛠️ How to Use

1. Open the live link in your web browser.
2. Fill out your Experiment Title, Student Name, Registration Number, Group Number, Semester, and Submission Date in the left control workspace.
3. Click **"Save Credentials"** so the platform auto-fills your data the next time you write a lab report.
4. Use the **"MILLIMETER MICRO-ADJUSTERS"** panel if you need to temporarily adapt layout sizes, element heights, character widths, or gaps for specialized department variations.
5. Click **"Download Vector PDF"** or choose **"Print Cover"** to render your finalized template.

---

## 🖨️ CRITICAL: Printer Calibration Settings

To guarantee that your printed document perfectly matches the true millimetric requirements, students **must bypass system printer auto-scaling**:

1. Open your downloaded document inside a dedicated reader like **Adobe Acrobat Reader** or your system printer panel.
2. In the Print Dialog menu under **Page Sizing & Handling**, always change the selection from *"Fit to Page"* or *"Shrink oversized pages"* to **"Actual Size"** (or hard-lock the scale percentage to exactly **100%**).
3. If you leave auto-scaling turned on, your computer will shrink the A4 canvas to accommodate normal desktop paper feed clips, which distorts your true measurements (turning a 15mm margin into 20mm). Switching to **Actual Size** ensures your output printed margins match the target **15mm / 12mm** specifications perfectly.

---
