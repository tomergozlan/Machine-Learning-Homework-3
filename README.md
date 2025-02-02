# 📚 Machine Learning - Homework 3  
**Ariel University**  
**Course:** Machine Learning  

---

## **📌 Assignment Overview**  
This assignment involves implementing **K-Nearest Neighbors (k-NN)** and **Decision Tree Algorithms** using the **Iris dataset**, specifically focusing on the **Versicolor and Virginica classes**, and using only the **second and third feature coordinates**.  

### **📂 Repository Structure**
```bash
📦 Machine-Learning-Homework-3
├── 📄 README.md                      # Project documentation
├── 📄 Machine Learning Homework 3.pdf # Assignment description
├── 📄 k-NN_and_DecisionTree.ipynb     # Jupyter Notebook with implementation
```

---

## **📝 Part 1: K-Nearest Neighbors (KNN)**
### 🔹 **Task Breakdown**
1. **Dataset Preparation**  
   - Split dataset into **50% training set** and **50% test set**.  
2. **KNN Classifier Implementation**  
   - Train **k-NN for k = {1, 3, 5, 7, 9}** and **distance metrics p = {1, 2, ∞}**.  
3. **Error Computation**  
   - Calculate classification error for both **training and test sets**.  
4. **Empirical and True Error Analysis**  
   - Repeat (1) & (2) **100 times**, computing **average empirical & true errors**.  
5. **Analysis Questions**  
   - Identify **best values for k, p**, discuss **overfitting and generalization**.  

---

## **📝 Part 2: Decision Tree Implementation**
### 🔹 **Task Breakdown**
1. **Decision Tree Construction**
   - Trees have **maximum depth = 3** (root, children, and leaf grandchildren).  
   - Each node either **becomes a leaf** or **splits based on a selected feature**.  
2. **Splitting Strategies**
   - **Brute-Force:** Constructs **all possible trees** of depth 3 and selects the one with **lowest classification error**.  
   - **Binary Entropy:** Iteratively splits nodes by selecting the **feature that minimizes entropy**, leading to **more optimal feature selection**.  
3. **Evaluation & Visualization**
   - Run both methods with **k = 3**, compare **error rates**, and **visualize the resulting trees**.  
4. **Analysis**
   - Compare the models' **performance, error rates, and generalization ability**.  

---

## **🛠️ How to Run the Code**
1. **Open Jupyter Notebook**
   ```bash
   jupyter notebook k-NN_and_DecisionTree.ipynb
   ```
2. **Run all cells** to execute both KNN and Decision Tree implementations.  

---

## **📊 Expected Output & Analysis**
- **Classifier accuracy comparison for different k, p values.**  
- **Decision tree visualizations for brute-force and entropy-based methods.**  
- **Discussion on best hyperparameters, overfitting, and model generalization.**  

---

## **📌 Submission Requirements**
- ✅ **Python code & Jupyter Notebook (`.ipynb`)**  
- ✅ **Results output (graphs, tables, performance metrics)**  
- ✅ **Analysis answers in `Machine Learning Homework 3.pdf`**  

---

## **📌 Author**
👤 **Tomer Gozlan**  
🔗 GitHub: [@tomergozlan](https://github.com/tomergozlan)  

---

📌 **This project is part of the Ariel University Machine Learning Course.**
