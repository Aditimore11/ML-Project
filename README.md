# ML-Project
# MediPredictor - Disease Prediction Tool

**Author:** Aditi More  
**Project Type:** React Web Application  
**Purpose:** Educational tool for predicting disease probabilities based on selected symptoms.  

---

## Project Overview
MediPredictor is a web-based disease prediction tool that allows users to select symptoms and get a list of probable diseases with confidence levels. The app uses a simple rules-based approach (or simulated AI logic) to provide predictions and visualize disease probabilities.

---

## Features

1. **Symptom Selection**
   - Users can select multiple symptoms from a pre-defined list.
   - Selected symptoms are highlighted.
   - Option to clear all selections.

2. **Disease Prediction**
   - Calculates probable diseases based on selected symptoms.
   - Shows confidence/probability levels.
   - Updates dynamically as symptoms are selected/deselected.
   - Shows toast notifications for user guidance.

3. **Visualization**
   - Interactive display of disease probabilities.
   - Top prediction highlighted.

4. **User Feedback**
   - Toast notifications for actions (e.g., first symptom selected, clearing all selections).
   - Loading indicator while analysis is simulated.

5. **Disclaimer**
   - Informational purpose only; not a substitute for professional medical advice.

---

## Tech Stack
- **Frontend:** React, TypeScript  
- **Styling:** Tailwind CSS  
- **State Management:** React Hooks (`useState`, `useEffect`)  
- **Notifications:** Custom Toast component  
- **Data:** Local simulated medical dataset (`medical_data.ts`)  

---

## Folder Structure
/src
/components
Header.tsx
SymptomSelector.tsx
DiseaseVisualization.tsx
PredictionResult.tsx
Disclaimer.tsx
/data
medical_data.ts
pages
index.tsx
