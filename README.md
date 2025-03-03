# README  

This is the directory of the work **"MMDDI-SSE: A Novel Multi-Modal Feature Fusion Model with Static Subgraph Embedding for Drug-Drug Interaction Event Prediction."**  


![MMDDI-SSE Model](model.jpg)  

## Dataset Description  

This project includes two datasets, which can be found in the `data` folder.  

Additionally, we manually collected the pharmacodynamic text information of the drugs in both datasets and processed them into feature vectors using Bio-BERT:  

- The pharmacodynamic features of the **small dataset** are stored in the `xiaoshujuji.csv` file.  
- The pharmacodynamic features of the **large dataset** are stored in the `dashujuji.csv` file.  

## File Structure  

```
├── data  
│   ├── dataset1.csv  # First dataset  
│   ├── dataset2.csv  # Second dataset  
│   ├── xiaoshujuji.csv  # Pharmacodynamic features of the small dataset (processed by Bio-BERT)  
│   ├── dashujuji.csv  # Pharmacodynamic features of the large dataset (processed by Bio-BERT)  
│   └── ...  
├── src  # Source code files  
├── README.md  # This file  
└── ...  
```  

## Data Processing  

1. **Data Collection**  
   - The datasets contain multiple drugs and related information.  
   - Pharmacodynamic text information was manually collected and curated.  

2. **Feature Extraction**  
   - Bio-BERT was used to process the pharmacodynamic text and generate high-dimensional feature vectors.  

## How to Run  

Please refer to the code in the `src` directory for data preprocessing, model training, or analysis.  

## Contact  

If you have any questions or suggestions, please contact [your contact information or GitHub profile].  

---  

Thank you for your interest!