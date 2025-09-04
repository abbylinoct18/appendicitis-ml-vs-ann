# 兒童闌尾炎診斷：ML vs ANN 模型比較

本專案使用 [UCI Regensburg Pediatric Appendicitis Dataset](https://archive.ics.uci.edu/dataset/938/regensburg+pediatric+appendicitis)  
透過 **傳統機器學習模型** 與 **人工神經網路 (ANN)**，比較不同方法在兒童闌尾炎診斷上的表現。

---

## 📊 專案目標
1. 探討 **不同演算法在醫療診斷問題上的效能差異**  
2. 建立分類模型，判斷兒童是否為闌尾炎  
3. 比較 **Logistic Regression、Random Forest、ANN** 的表現  

---

## 🛠 使用技術
- **Python**：pandas, numpy, matplotlib, seaborn  
- **scikit-learn**：Logistic Regression, Random Forest, 評估指標  
- **TensorFlow / Keras**：ANN 建立與訓練  
- **MinMaxScaler**：特徵標準化  

---

## 📂 資料來源
- Dataset: [UCI Machine Learning Repository - Regensburg Pediatric Appendicitis](https://archive.ics.uci.edu/dataset/938/regensburg+pediatric+appendicitis)

---

## 📈 模型比較結果
| Model               | Accuracy | F1-score | AUC     |
|----------------------|----------|----------|---------|
| Logistic Regression  | 0.8571   | 0.8772   | 0.9417  |
| Random Forest        | 0.9388   | 0.9492   | 0.9891  |
| ANN (Neural Network) | 0.8061   | 0.8430   | 0.8825  |

👉 Random Forest 表現最佳，ANN 在資料量有限時表現略遜於傳統機器學習模型。

---

## 📊 視覺化成果
* ROC 曲線圖
<img width="691" height="547" alt="image" src="https://github.com/user-attachments/assets/cfe445d4-005a-4749-9f96-7e0b1772eec4" />
