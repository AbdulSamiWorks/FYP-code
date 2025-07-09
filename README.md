# 🧠 Federated Learning for Ocular Disease Classification

This project explores **Decentralized Federated Learning** for the classification of ocular diseases from retinal images, using state-of-the-art deep learning models like **EfficientNet-B0**, **Swin Transformer**, **MobileNetV3-Large**, and **CNN with Attention**. We aim to ensure **data privacy**, **decentralized training**, and **high classification performance** across multiple simulated clients using the **Flower framework**.

## 🚀 Objectives

- Train deep learning models on **distributed datasets** without centralizing sensitive medical data.
- Evaluate the performance of different **CNN architectures** in a federated setting.
- Improve diagnostic accuracy for **ocular diseases** like glaucoma, diabetic retinopathy, and cataracts.
- Demonstrate a privacy-preserving AI system using **Federated Learning**.

---

## 🧰 Tech Stack

- **Frameworks**: PyTorch, Flower (FL), TimM, TorchVision  
- **Models**:  
  - `EfficientNet-B0` (Baseline)  
  - `Swin Transformer` (Vision Transformer backbone)  
  - `MobileNetV3-Large` (Lightweight, mobile-friendly model)  
  - `CNN + Attention` (Custom architecture for localized feature enhancement)  
- **Dataset**: ODIR-5K  
- **Language**: Python  
- **Other Tools**: pandas, scikit-learn, PIL, matplotlib

---

## 🏥 Dataset: ODIR-5K

- 5000+ fundus images collected from multiple hospitals.
- Each image labeled with ocular conditions like:
  - Normal
  - Myopia
  - Glaucoma
  - Diabetic Retinopathy
  - Cataract
  - Hypertension, etc.
- We used **preprocessed and client-partitioned** subsets to simulate decentralized hospital data.

---

## 🏗️ Folder Structure

```

📦FYP-Ocular-FL
┣ 📂EfficientNet/
┣ 📂SwinTransformer/
┣ 📂MobileNet/
┣ 📂CNN\_Attention/
┣ 📂preprocessed\_images/
┣ 📄DFL.ipynb
┣ 📄FL\_Client\_0.csv
┣ 📄FL\_Client\_1.csv
┣ 📄requirements.txt
┗ 📄README.md

````

---

## ⚙️ How to Run

1. **Clone the repository**  
```bash
git clone https://github.com/YourUsername/FYP-Ocular-FL.git
cd FYP-Ocular-FL
````

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Train a specific model using Flower**

```bash
python EfficientNet/train_federated.py
python SwinTransformer/train_federated.py
# etc.
```

4. **Customize client CSV partitions** for federated splits (e.g. `FL_Client_0.csv`)

---

## 📊 Results

| Model             | Accuracy (%) | Precision | Recall | F1-Score |
| ----------------- | ------------ | --------- | ------ | -------- |
| EfficientNet-B0   | 98.4         | 0.2       | 0.98   | 0.97     |
| Swin Transformer  | 99.2         | 0.1       | 0.99   | 0.99     |
| MobileNetV3-Large | 97.1         | 0.3       | 0.98   | 0.97     |
| CNN + Attention   | 89.3         | 0.90      | 0.89   | 0.89     |

✅ **Swin Transformer outperformed others** in both accuracy and generalization.

---

## 🧠 Key Contributions

* Implemented **federated training** for ocular disease detection.
* Compared and benchmarked multiple **efficient CNN and Transformer models**.
* Achieved **>91% accuracy** using Swin Transformer in a decentralized setup.
* Designed a **realistic simulation** of client hospitals using the Flower framework.

---

## 🔭 Future Work

* Use **differential privacy** or **secure aggregation** for stronger data security.
* Integrate **edge-device optimization** for real-world deployment.
* Extend to **multi-modal diagnosis** (images + reports).

---

## 👨‍💻 Contributors

* **Abdul Sami** – Final Year Student, AI Researcher
* Supervisor: *\[Supervisor Name]* (optional)
* Institution: *\[University Name]*

---

## 📜 License

This project is for academic and research purposes. Licensing depends on dataset and model use.

---

```

Let me know:
- Your GitHub repo link (I'll update the clone URL)
- If you want badges (e.g., model versions, paper links, etc.)
- Supervisor/university details (optional)
- If you want an Urdu version too

I can generate a PDF or include visuals if needed.
```
