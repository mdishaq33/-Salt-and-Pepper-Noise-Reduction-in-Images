# -Salt-and-Pepper-Noise-Reduction-in-Images

# 🧼 Salt and Pepper Noise Removal using NumPy

This project adds **salt and pepper noise** to a grayscale image and removes it using a **median filter**, all using only NumPy. No OpenCV or external image processing libraries are used.

---

## 📂 Features

- Upload your own image (JPG, PNG) using Google Colab
- Add salt (white) and pepper (black) noise with user-defined probabilities
- Remove noise using a custom NumPy-based median filter
- View original, noisy, and cleaned images
- Save image arrays as `.npy` files

---

## 📁 Files

- `main.ipynb`: Full working Google Colab notebook
- Output files created after running:
  - `original_image.npy`
  - `noisy_image.npy`
  - `cleaned_image.npy`

---

## 🛠 Requirements

- Python 3.x
- Google Colab (recommended)

---

## ▶️ How to Run

1. Open `main.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run the cells step-by-step
3. Choose:
   - `u` to upload your own image
   - `g` to use a generated gradient image
4. Enter:
   - Salt noise probability (e.g. `0.05`)
   - Pepper noise probability (e.g. `0.05`)
   - Filter size (odd integer, e.g. `3`)
5. View the results using matplotlib
6. Download saved `.npy` files if needed

---

## 🔍 Key Concepts

- NumPy arrays for image handling
- Random noise generation
- Median filtering using only NumPy
- Matplotlib for visual display
- PIL for image conversion

---

## 📌 Notes

- If no image is uploaded, a gradient image is used
- Median filter size must be odd (e.g., 3, 5, 7)
- Larger images may take longer to process

---

## 📄 License

Free for educational and non-commercial use.
