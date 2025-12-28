# Healthcare Data Privacy and Sharing Using Federated Learning

## Project Overview
This project demonstrates a **privacy-preserving healthcare data analysis system** using **Federated Learning**.  
Instead of sharing sensitive patient data, multiple healthcare institutions collaboratively train a machine learning model by sharing **model updates only**, ensuring **data privacy and security**.

This approach is highly suitable for medical applications where data confidentiality is critical.



## Objectives
- Preserve patient data privacy across healthcare institutions
- Enable collaborative model training without centralizing data
- Reduce data leakage risks
- Demonstrate federated learning in real-world healthcare scenarios



## Technologies Used
- Python
- TensorFlow / PyTorch (Federated Learning concepts)
- NumPy, Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook



## System Architecture
1. Each hospital keeps its data locally
2. A local ML model is trained at each institution
3. Only model weights are sent to a central server
4. The server aggregates the weights (Federated Averaging)
5. The updated global model is shared back with institutions

**Raw data never leaves the local systems**



## Dataset
This project uses the **MedMNIST (Medical MNIST)** dataset, a well-known medical imaging dataset.

### Dataset Classes:
- AbdomenCT  
- BreastMRI  
- ChestCT  
- Chest X-Ray (CXR)  
- Hand X-Ray  
- HeadCT  
Due to GitHub size limitations, the dataset is **not included** in this repository.

### Download Dataset from Kaggle:
- https://www.kaggle.com/datasets/andrewmvd/medical-mnist



## Flow Diagram:

![Healthcare Flow Diagram](Screenshots/flow%20diagram.png)

*Flow diagram illustrating healthcare data privacy and federated learning workflow.*

