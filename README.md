# MHRA 

**MHRA** – MHRA – A MATLAB application for external multi-hazard probabilistic risk assessment for nuclear power plant

Authors · Changuk Mun, Shinyoung Kwag, Seunghyun Eem, Daegi Hahm
  
License · MIT (see `LICENSE.txt`)

---

## Purpose

This program, called MHRA (Multi Hazard probabilistic Risk Assessment), is a MATLAB-based GUI developed to facilitate multi-hazard probabilistic risk assessment (PRA) for nuclear power plants (NPPs).

---

## Features

* MHRA consists of five integrated modules: 
   - Multi-hazard surface input  
   - Component fragility surface input and evaluation
   - Systems analysis model
   - Risk quantification
   - Output 
* Fully open MATLAB codebase  
* MIT-licensed and lightweight (runs on MATLAB Runtime if you have no MATLAB licence)

---

## Installation

### Option A – Source code (Recommended)

1. Clone this repository.  
2. Open 'MHRA_v1.mlapp' in MATLAB R2024a or newer.  
3. Click **Run** in App Designer.

### Option B – Packaged app 

1. Open MATLAB R2024a or newer.
2. **Install** MHRA_v1.mlappinstall in release folder, and run this application.
3. Go to the App manu of MATLAB and find "MHRA" app in My app.
4. Click "MHRA" to **Run** the MHRA application.

### Option C – Packaged app  (for this, release Application using Source code)
1. Open 'EHRA_v1.mlapp' in MATLAB R2024a or newer.
2. Make 'Application' using Share in App Designer (please, name as EHRA)
3. MATLAB APP
4. Web APP using MATLAB Compiler
5. Standalone APP using MATLAB Compiler
6. Install the matching MATLAB Runtime.
7. Run EHRA.exe (Windows) or the equivalent launcher for your OS.

---

## Quick start

Please take a look at the attached guide in the **docs** folder.

--- 

## Contributing

MHRA can be applied across academic, industrial, and educational settings. 
 - Researchers can utilize this tool to test newly developed algorithms in their work. 
 - Third-party reviewers involved in nuclear safety analysis can use MHRA as a complementary tool for independent verification of multi-hazard PRA results. 
 - Its transparency and reliability can be effective during regulatory discussions, allowing analysts to provide detailed technical justifications for their computational methods. 
 - This can aid in validating outputs from commercial codes for existing reactors, with the results serving as benchmarks. 
 - MHRA can be used to teach mutli-hazard PRA concepts to students and industry professionals for educational purposes.

---

## Contact

* Shinyoung Kwag — skwag@hanbat.ac.kr / skwag@edu.hanbat.ac.kr 

---

## License

MHRA is released under the **MIT License** – see `LICENSE.txt`.

---

## Disclaimer

The software is provided *as is* for research and educational use. The software is provided as is for research and educational use. Always confirm the input Excel template, hazard intensity ranges including subdivision, solver settings, and results on your specific multi-hazard PRA example, carefully.

