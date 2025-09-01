# ECG Analysis for Beginners

This project is a beginner-friendly ECG signal analysis based on publicly available data.  
I followed and adapted the original work from a Kaggle notebook for learning purposes.

---

## 📊 What the Code Does

- Loads ECG data from a CSV file (`100_ekg.csv`)
- Plots:
  - 30 minutes of ECG signal
  - First few heartbeats of the signal
- Uses `scipy.signal.find_peaks()` to identify R-peaks (heartbeat spikes)

---

## ⚠️ Credit and Source

This project is based on the Kaggle notebook by proto bioengineering (linked below).  
I have re-written and adapted the code for personal learning purposes only.

- Original notebook: (https://www.kaggle.com/code/protobioengineering/getting-started-visualizing-patient-100-s-ecg/notebook)]

---

## 🧠 Issues and Observations

- The original Kaggle notebook lacks detailed explanation on **peak detection tuning**
- The ECG signal is noisy in some sections — more preprocessing (like filtering) might be needed
- It assumes the file `100_ekg.csv` is available locally — this should be clarified or uploaded

---

## 🚧 What's Next

- Add peak filtering and noise reduction
- Try analyzing more ECG files (e.g., patient 101, 102, etc.)
- Add RR interval calculation and heart rate variability analysis

---

## 🧑‍💻 Tech Stack

- Python
- pandas
- matplotlib
- scipy

---

## 🙋‍♀️ Disclaimer

This project is for **educational purposes only**.  
All credits go to the original author(s) of the Kaggle notebook.

