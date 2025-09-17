Video Demonstration:
    https://youtu.be/Ef2OAoJNqlQ?si=4iQGvm7-GmEe6B8f

Smart Wasteland Reclamation 

## Overview
This project is my entry for the "India AI Impact Hackathon (Track 3)" .
The theme is "Smart Wasteland Reclamation" – using "AI + Agentic workflows" to use soil, rainfall, and environmental data to forecast land reclamation capability.

The solution shows:
-  Synthatic dataset generation (train.csv, test.csv, sample_submission.csv)
-  Feature engineering (soil type, rainfall, temporal trends, vegetation index)
-  Training of the models (Ridge, RandomForest, ExtraTrees, LightGBM)
-  Ensemble model with predictions in submission.csv (*id only – prevents row_id errors*)
-  Visualizations: feature_importance.png and model_comparison.png
-  Optional "WatsonX Granite LLM" integration for sustainability & impact insights

## Project Structure
├── notebook.ipynb          # Main Jupyter Notebook with all code 
├── train.csv               # Training dataset 
├── test.csv                # Testing dataset 
├── sample_submission.csv   # Sample submission format 
├── submission.csv          # Generated submission file 
├── requirements.txt        # Dependencies 
├── feature_importance.png  # Model feature importance plot 
├── model_comparison.png    # Model comparison plot

## Setup
1. Install requirements:
   ```bash
   pip install -r requirements.txt

2. Open the notebook:
jupyter notebook notebook.ipynb

3. Run all cells to:
Train models
Compare results
Generate submission.csv

## Output
submission.csv → Final file for hackathon submission
feature_importance.png → Feature importance plot
model_comparison.png → Model comparison visualization

## Future Scope
This project lays the foundation for scalable AI-driven land reclamation systems. Future improvements could include:
1. Integration with IoT & Satellite Data
Real-time soil sensors, drone imagery, and satellite NDVI indices to improve predictions.
2. Climate Resilience Modeling
Simulating drought, flood, and soil degradation scenarios for long-term reclamation planning.
3. WatsonX Agentic Workflows
Using WatsonX LLMs to generate sustainability reports, explainability dashboards, and policy recommendations.
4. Community & Policy Integration
Deploying results in a decision-support tool for local authorities, farmers, and policymakers.
5. Scalability
Extend to other degraded lands (mining sites, deforested areas) across India.
