
# Crop Disease AI - Detection & Advisory System
## Final Year Project - CSE AIML

### Project Overview
An AI-powered smartphone app that detects 38+ crop diseases from leaf photos,
grades severity, and gives treatment advice in Telugu, Hindi, and English.

### Tech Stack
- Model     : EfficientNet-B3 (PyTorch)
- XAI       : Grad-CAM heatmaps
- Mobile    : TFLite (INT8 quantised)
- Backend   : FastAPI + Docker
- Frontend  : React PWA
- Hosting   : Render (backend) + Vercel (frontend)

### Dataset
- PlantVillage  : 54,306 images, 38 classes
- PlantDoc      : 2,598 real-world images
- Custom        : Real farm photos (Hyderabad region)

### Folder Structure
- data/         : All datasets
- models/       : Saved model weights
- notebooks/    : EDA and experiments
- src/          : Source code
- app/          : Backend + Frontend
- outputs/      : Results, heatmaps
- reports/      : Final year project report
