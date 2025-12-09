# 6G Signal Modulation Classification using Machine Learning

This project focuses on generating and analyzing wireless communication signals resembling 6G characteristics and classifying modulation schemes such as PSK and QAM using Machine Learning and Deep Learning approaches.

This work is done as part of an academic project under the guidance of **Dr. Kishor Kisan Ingle**.

---

## Objective

- Generate digitally modulated signals (PSK, QAM)
- Apply channel effects including noise and multipath fading
- Train and evaluate Machine Learning and Deep Learning models for modulation classification

---

## Project Structure

| File/Folder | Description |
|------------|-------------|
| `notebooks/` | Contains development and experiment notebooks |
| `PSK_ANN.ipynb` | ANN-based classifier |
| `CNN_PSK.ipynb` | CNN model for modulation classification |
| `PSK_with_Multipath.ipynb` | Simulation with multipath channel |
| `PSK_wnoise_KNN.ipynb` | KNN with noisy PSK signals |
| `PSK+QAM.ipynb` | Multiple modulation schemes experiment |
| `requirements.txt` | Python library dependencies |

---

## Technologies Used

- Python
- NumPy
- Scikit-Learn
- TensorFlow / Keras or PyTorch
- Matplotlib

---

## How to Run

```bash
git clone https://github.com/Linkeshwar-vs/6g-signal-ml-modulation.git
cd 6g-signal-ml-modulation
pip install -r requirements.txt
