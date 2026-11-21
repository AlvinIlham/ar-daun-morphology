# AR-Daun - Botanical Leaf Morphology & Anatomical Structure Augmented Reality Pack

![Type](https://img.shields.io/badge/Type-3D_Asset_%26_Marker_Archive-purple.svg?style=for-the-badge)
![Field](https://img.shields.io/badge/Field-Botany_%26_Plant_Biology-green.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Compressed_Archive-yellow.svg?style=for-the-badge)

---

## 📖 1. Overview
**AR-Daun** is a botanical Augmented Reality project that models plant leaf morphology (pinnate, palmate, parallel, and arcuate venation patterns) and cross-sectional plant anatomy in full 3D space for secondary school biology instruction.

---

## 📦 2. Archive Contents (`AR Daun.zip`)
```text
AR Daun/
├── 3D Model/
│   ├── ASSET DAUN.fbx      # 3D leaf model with detailed chlorophyll surface textures
│   ├── daun.fbx            # Botanical leaf variant 1
│   ├── daun1.fbx           # Botanical leaf variant 2
│   └── daun2.fbx           # Botanical leaf variant 3
├── ASSET DAUN.blend        # Master Blender 3D source file (open for leaf mesh editing)
├── marker_adel.png         # High-contrast physical print AR marker
└── SC/
    └── Screenshot (155).png# Verified AR render capture proof
```

---

## 🚀 3. Integration & Shader Guide
1. Extract `AR Daun.zip` to your project directory.
2. Drag `3D Model` into your Unity `Assets/Models/` folder.
3. **Important Material Setup:** In the Inspector, configure the leaf material shader with **Double-Sided Rendering** (or disable backface culling) so that the underside of the leaf remains visible during camera rotation.
4. Upload `marker_adel.png` to Vuforia Target Manager to create an Image Target database.
