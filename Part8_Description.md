# Part8 - Design Documentation

## Part Overview
**Part Name:** Part8  
**Material:** Aluminum 6061, Welded  
**Density:** 2.7 g/cm³  
**Created:** April 5, 2026  
**File Format:** STEP (ISO 10303-21)  
**CAD Software:** Autodesk Inventor 2026  

---

## Design Intent & Purpose

### Primary Function
This part serves as a **structural connector/bracket** designed to integrate multiple sub-assemblies while maintaining lightweight properties through aluminum construction.

### Why This Design Was Created

#### Objectives:
1. **Weight Optimization** - Aluminum 6061 provides strength-to-weight ratio superior to steel
2. **Welded Construction** - Eliminates fastener requirements, reducing assembly complexity
3. **Multi-feature Integration** - Accommodates both cylindrical and planar mounting interfaces
4. **Cost Efficiency** - Welded aluminum reduces material waste and secondary operations

---

## Geometric Specifications

### Key Features

| Feature | Type | Dimension | Purpose |
|---------|------|-----------|---------|
| Primary Cylinder | Through-hole | Ø10mm | Mounting point / Fastener boss |
| Secondary Cylinder | Blind/Through | Ø30mm | Bushing seat / Secondary interface |
| Planar Faces | Multiple | Variable | Mounting surfaces / Assembly references |
| Overall Envelope | Bounding box | ~114 × 70 × 76mm | Design space allocation |

### Geometry Details
- **Total Faces:** 16 advanced surfaces
- **Cylindrical Surfaces:** 2 (radii: 10mm, 30mm)
- **Planar Surfaces:** 14 (supporting assembly alignment)
- **Complexity:** Moderate - multi-directional geometry with angled features

---

## Manufacturing Considerations

### Material Properties
- **Alloy:** Aluminum 6061, Welded
- **Density:** 2.7 g/cm³
- **Typical Uses:** General-purpose structural applications
- **Weldability:** Excellent (6061 is specifically formulated for welding)

### Recommended Manufacturing Process
1. **Stock Preparation** - Extrusion or plate stock
2. **Machining** - CNC for cylindrical and planar features
3. **Welding** - TIG/MIG welding for final assembly
4. **Finishing** - Anodizing for corrosion resistance (optional)
5. **QA Inspection** - Surface inspection for weld quality

---

## Assembly Integration

### Expected Interfaces
- **Ø10mm Hole:** For M8 fasteners or dowel pins
- **Ø30mm Feature:** For bearing/bushing installation or shaft coupling
- **Planar Faces:** Multiple surfaces for bolted assembly to adjacent parts

### Design Context
*[Add specifics about what assemblies this connects to]*

---

## Design Practice Notes

### Why Practice This Design?

This part is excellent for learning because it demonstrates:

✓ **Mixed Geometry** - Combines cylindrical and planar surfaces  
✓ **Material Selection** - Practical aluminum choice for weight-critical application  
✓ **Manufacturing Awareness** - Welded design shows DFM (Design for Manufacturing) thinking  
✓ **Assembly Logic** - Multiple features show intentional interface design  
✓ **CAD Modeling** - Complex enough to practice advanced feature creation  

### Learning Objectives
1. Understanding cylindrical feature creation and dimensioning
2. Planar surface modeling and reference plane usage
3. Material property implications on design
4. Assembly-driven design thinking
5. STEP file format and CAD data translation

---

## Revision History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2026-04-05 | LENOVO | Initial design creation |
| 1.1 | 2026-06-04 | SaymaSJ | Documentation & practice notes |


