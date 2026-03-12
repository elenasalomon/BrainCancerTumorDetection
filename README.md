# Brain Tumor Detection

> Detección automática de tumores cerebrales mediante segmentación semántica con U-Net.

**Deep Learning · Computer Vision — Especialización en Ciencia de Datos e IA (UTEC – MIT)**  
Elena Salomón · 2026 — 🚧 Mejoras en progreso

---

## Descripción

Modelo de segmentación semántica para la detección automática de tumores cerebrales en imágenes de resonancia magnética (MRI). El sistema utiliza una arquitectura U-Net para identificar y delimitar regiones tumorales pixel a pixel, con el objetivo de asistir en el diagnóstico clínico.

---

## Estado del Proyecto

> **🚧 En progreso.** Este repositorio se actualizará a medida que avance el desarrollo.

---

## Objetivo

Desarrollar un modelo de deep learning capaz de:
- Segmentar automáticamente regiones tumorales en imágenes MRI
- Distinguir entre tejido sano y tejido tumoral a nivel de pixel
- Proporcionar una herramienta de apoyo al diagnóstico médico

---

## Arquitectura: U-Net

U-Net es una arquitectura convolucional diseñada específicamente para segmentación de imágenes biomédicas. Su estructura encoder-decoder con skip connections permite:
- Capturar contexto global (encoder)
- Recuperar detalles espaciales precisos (decoder)
- Combinar información de distintas escalas para una segmentación precisa

---

## Dataset

- **Fuente:** Dataset de imágenes MRI de tumores cerebrales (por confirmar)
- **Tarea:** Segmentación binaria (tumor / no tumor)
- **Formato:** Imágenes + máscaras de segmentación

---

## Stack Técnico

```
Python · TensorFlow / Keras · U-Net · OpenCV · NumPy · matplotlib
```

---

## Estructura del Repositorio

```
BrainTumorDetection/
├── brain_tumor_unet.ipynb   (próximamente)
└── README.md
```
