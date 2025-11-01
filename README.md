# Clasificación de CIFAR-10 usando MLP y CNN en PyTorch

Este proyecto implementa y compara dos modelos de Deep Learning para la clasificación del dataset **CIFAR-10**:

- 🧠 **MLP (Multi-Layer Perceptron)**
- 🧩 **CNN (Convolutional Neural Network)**

El código incluye:
- Carga manual de datos CIFAR-10 desde archivos `.pkl`
- División en entrenamiento/validación/prueba (80/10/10)
- Data augmentation
- Entrenamiento con *Early Stopping*
- Comparación final de métricas
- Curvas de aprendizaje
- Guardado de mejores modelos `.pth`

---

## 📂 Estructura del Proyecto

Proyecto/
│── notebooks/
│   ├── Descarga_datos.ipynb       # Notebook para descarga y preparación de datos
│   ├── Proyecto.ipynb             # Notebook principal del proyecto
│
└── .gitignore                     # Archivos ignorados (datos, .pth, .pkl, etc.)


---

## 🧪 Dataset

Se usa **CIFAR-10**, 60,000 imágenes (32×32×3, 10 clases):

- 50,000 para entrenamiento
- 10,000 para pruebas
- Se redivide a 80% train / 10% val / 10% test

---

## ⚙️ Requerimientos

```bash
python 3.8+
torch
torchvision
numpy
pickle
scikit-learn
matplotlib

---

📊 Resultados Esperados

| Modelo | Accuracy aprox. |
| ------ | --------------- |
| MLP    | ~50%–60%        |
| CNN    | ~70%–80%        |

Las gráficas y métricas se imprimen en consola al finalizar.

---

🧠 Idea Principal

Este proyecto sirve para:

Entender diferencias entre MLP y CNN

Manejo manual de CIFAR-10 desde pickle

Implementación de early stopping

Guarda del mejor modelo y métricas

---

✨ Autor

Brenda Fernanda Noguez Ruiz