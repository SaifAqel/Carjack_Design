# 🛠️ Trapezoidal Car Jack Design

This project presents the mechanical design, analysis, and manufacturing process of a **trapezoidal car jack** intended to lift a 1000 kg vehicle. It includes detailed calculations, component selection, material analysis, safety verification, and an assembly drawing.

---

## 📁 Project Contents

- `Carjack_Report.pdf`  
  A full design report including:
  - Problem definition and objectives
  - Load calculations and part-specific stress analysis
  - Threaded shaft and nut design
  - Fatigue and buckling checks
  - Thrust bearing and drive arm sizing
  - Manufacturing method selection and material specs

- `Carjack_Assemply.pdf`  
  Engineering drawing of the car jack assembly showing:
  - Sectional views (A-A, B-B, etc.)
  - Part names, materials, and quantities
  - Key dimensions and TR8x1.5 screw thread details

---

## ⚙️ Key Design Inputs

- **Vehicle Mass**: 1000 kg  
- **Lifting Height Range**: 180 mm – 300 mm  
- **Safety Factor Used**: 1.5

---

## 🧩 Major Components

| Part Name            | Material         | Process                        |
|----------------------|------------------|--------------------------------|
| Base                 | S235JOW          | Shearing, bending              |
| Lifting Arms         | S235JOW / 355JOW | Cold bending                   |
| Threaded Shaft       | C45              | Turning, thread rolling        |
| Nut & Cross Piece    | C22E / C45       | Chip formation                 |
| Driving Arm          | C25              | Cold bending                   |
| Bearings             | SKF 51100        | Stock selection                |
| Pins                 | C22E             | Cutting, riveting              |

---

## 🧮 Engineering Highlights

- **Load Analysis**: Max force = 9810 N, Arm force = 4905 N  
- **Lifting Arm Stress**: σ = 25.9 MPa, Safety factor = 9.1  
- **Threaded Shaft**:
  - Tensile stress = 325 MPa  
  - Equivalent stress = 412 MPa (C45E Re = 490 MPa)  
  - TR8x1.5 thread is **self-locking**
- **Nut & Pin Design**: Verified for surface pressure, bending, and shear  
- **Thrust Bearing**: SKF 51100 (Static rating > load, So = 1.43)  
