Molecular Solubility Prediction

This project predicts the aqueous solubility of molecules based on their SMILES representation using a trained machine learning model.

Key Features:
1. **SMILES Input**: The user can input a SMILES string of a compound.
2. **Descriptor Calculation**: The code calculates molecular descriptors like LogP, molecular weight, number of rotatable bonds, and aromatic proportion.
3. **Solubility Prediction**: The model predicts the solubility (LogS) and classifies the compound into one of four solubility levels: Highly Soluble, Moderately Soluble, Slightly Soluble, or Poorly Soluble.
4. **Pre-trained Model**: The model is trained using Delaney’s solubility dataset and is saved for future predictions.

Usage:
1. Enter the SMILES string of a compound.
2. The solubility level will be printed based on the model's prediction.
