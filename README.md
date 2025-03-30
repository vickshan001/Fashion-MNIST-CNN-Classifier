# 🧥 Fashion MNIST CNN Classifier – ECS759P AI Coursework (2024)

The goal is to build, train, and evaluate a Convolutional Neural Network (CNN) to classify clothing items from the Fashion MNIST dataset.

---

## 🧠 Model Features

- 👕 Classifies images into 10 categories (e.g., T-shirt, Trouser, Sneaker)
- 🔍 Explores three activation functions: **Tanh**, **Sigmoid**, **ELU**
- ⚙️ Tests five learning rates: `0.001`, `0.1`, `0.5`, `1`, and `10`
- 📉 Uses **Categorical Cross-Entropy** as the loss function
- 🧪 Includes a **Dropout Layer** for regularization

---

## 📊 Summary of Findings

### 🔸 Activation Function Comparison

| Activation | Train Accuracy | Test Accuracy |
|------------|----------------|---------------|
| Tanh       | 100%           | 91.73%        |
| Sigmoid    | 87.87%         | 87.04%        |
| ELU        | 98.41%         | 91.25%        |

### 🔸 Learning Rate Comparison

| Learning Rate | Train Accuracy | Test Accuracy |
|---------------|----------------|----------------|
| 0.001         | 84.17%         | 83.11%         |
| 0.1           | 98.84%         | 90.80%         |
| 0.5 – 10      | ~10%           | ~10%           |

---

## 📂 Files Included

- `fashion_mnist.ipynb` – CNN implementation and experimental results
- `AI_CW2_Report_Vickshan_Vicknakumaran.pdf` – Supporting coursework documentation

---

## 🏫 Info

- 🏫 University: Queen Mary University of London  
- 📅 Year: 2024  
- 👨‍💻 Author: Vickshan Vicknakumaran

---

## 🚀 How to Run

1. Clone the repository.
2. Open `fashion_mnist.ipynb` in Jupyter Notebook.
3. Make sure the following libraries are installed:
   - `tensorflow`, `keras`, `numpy`, `matplotlib`
4. Run the notebook to train and evaluate the model.

---

## 📜 License

For academic and research use only.
