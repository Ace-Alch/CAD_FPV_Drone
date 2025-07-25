# FPV Drone CAD Design | SolidWorks 2022

This project presents a complete 3D CAD design of an FPV (First Person View) quadcopter drone using SolidWorks. The design includes detailed part modeling, exploded views, and assembly drawings, making it suitable for both simulation and physical prototyping.
<p align="center">
  <img src="Docs/Assembly_Explode.gif" width="70%" alt="Exploded View Animation">
</p>

---

## Components Overview

| Part Name           | Quantity |
|---------------------|----------|
| Spider Top          | 1        |
| Spider Base         | 1        |
| Spider Arms         | 4        |
| Brushless Motors    | 4        |
| Propellers          | 4        |
| Battery             | 1        |
| Electrical Board    | 1        |
| Machine Screws/Nuts | Varied   |

See full breakdown in [Docs/Assembly_Explode3D.pdf](Docs/Assembly_Explode3D.pdf)

---

## CAD Deliverables

- [Assembly_Explode3D.pdf](Docs/Assembly_Explode3D.pdf): Exploded 3D view with part list  
- [Assembly_Draw3D.pdf](Docs/Assembly_Draw3D.pdf): Standard 3D drawing with multiple projections  
- SolidWorks source files (`*.SLDPRT`, `*.SLDASM`)  
- Animated exploded view: `Assembly_Explode.gif`

---

## Design Considerations

- Designed for **lightweight FPV racing**
- Modular frame for easy maintenance
- Battery bay placement optimized for balance
- 4x brushless motors (compatible with 5" props)

---

## Folder Structure

| Folder   | Contents                            |
|----------|-------------------------------------|
| `CAD/`   | SolidWorks part and assembly files  |
| `Docs/`  | Exploded view, drawings, and GIF    |

---

## Next Steps

- [ ] Export to `.STEP` and `.STL` for 3D printing  
- [ ] Simulate aerodynamics in SimScale or Ansys  
- [x] Integrate with flight controller — I have done this in [this project](https://github.com/Ace-Alch/dji-mavic-sim)  
- [ ] Create assembly video with annotations
