# Design

## Architecture
- Frontend: Web interface
- Backend: Flask API
- Model: CNN (ResNet50)
- Explainability: Grad-CAM
- Database: SQLite

## Data Flow
1. User uploads skin image
2. Image is preprocessed
3. Model predicts disease
4. Grad-CAM highlights infected area
5. Result is shown to user

## Technology Stack
- Python
- TensorFlow / PyTorch
- OpenCV
- Flask
