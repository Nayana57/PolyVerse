🌐 PolyVerse: Polymer Property Prediction Using Deep Learning
PolyVerse is a deep learning-powered web application that predicts key physical and chemical properties of polymers based on their SMILES notation. This project bridges materials science and AI, enabling efficient and accurate prediction of polymer behavior, thereby reducing the need for costly and time-consuming experiments.

🧠 Project Overview
Traditional computational techniques like DFT and MD simulations are slow and resource-intensive. PolyVerse tackles this by leveraging:

A Feedforward Neural Network (FNN) trained on curated polymer datasets.
RDKit for molecular fingerprint generation.
A MERN Stack web interface for user interaction.
Advanced deep learning models (initial experiments also explored Transformer architectures).
📌 Key Features
Predicts properties such as:
Tensile Strength
Ionization Energy
Electron Affinity
LogP (Partition Coefficient)
Refractive Index
Molecular Weight
SMILES-based input with automatic validation.
Interactive frontend with prediction and analysis views.
Authentication (Register/Login) system.
Real-time prediction via Flask API backend.
🧪 Tech Stack
Layer	Technology Used
Frontend	React, TailwindCSS, Lucide Icons, Axios
Backend	Node.js + Express (API), Flask (ML logic)
ML Framework	TensorFlow/Keras, RDKit
Database	MongoDB Atlas
🔬 ML Model Summary
Architecture: 3-layer dense neural network (128 → 64 → output)
Features: 1024-bit Morgan fingerprints
Training: Mean Squared Error loss, Adam optimizer, EarlyStopping
Dataset: Polymer_final (cleaned and curated SMILES + properties)
📊 Results
Achieved ~95% R² score
Realistic predictions validated against known polymer data
Handles diverse polymer classes with good generalization
RDKit Documentation: https://www.rdkit.org

Polymer Handbook, PySMILESUtils, PPPDB datasets

About
polyverse-sandy.vercel.app
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Deployments
1
 Production 2 months ago
Languages
JavaScript
90.2%
 
Python
8.5%
 
Other
1.3%
Footer
