# Sign Language Recognition with LSTM

This project is focused on sign language recognition using LSTM (Long Short-Term Memory) networks. The system captures keypoints from signers' hand movements and translates them into text using deep learning techniques.

## 📽️ Demo Video
[![Watch the video](video demo.mp4)


## 📂 Files

### 1. `signlanguage keypoints collection.ipynb`
- This notebook is used for collecting keypoints from signers' videos using MediaPipe.
- It extracts hand landmarks and stores them for model training.

### 2. `sign-language lstm model.ipynb`
- This notebook contains the training pipeline for the LSTM model.
- It loads keypoint data, trains an LSTM-based neural network, and saves the trained model.

### 3. `test.ipynb`
- This notebook is for testing the trained LSTM model.
- It takes sign language inputs and predicts corresponding text.

## 🛠️ Installation Guide

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- TensorFlow, OpenCV, and MediaPipe

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/Hercules-Peters/Sign-Language-Recognition-with-LSTM
   cd Sign-Language-Recognition-with-LSTM
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Run the notebooks in the provided order:
   - First, run `signlanguage keypoints collection.ipynb` to generate keypoints.
   - Next, train the model using `sign-language lstm model.ipynb`. prefer GPU
   [Kaggle Link](https://www.kaggle.com/code/herculespeters/sign-language)  
   - Finally, test the model using `test.ipynb`.

## 📜 License

This project is licensed under the MIT License. See the full license below:

```
MIT License

Copyright (c) 2025 Hercules-Peters

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🤝 Contributing
Feel free to contribute to this project by submitting issues or pull requests!

## 📞 Contact
For any inquiries, reach out at: [kinyuapeter816@gmail.com] or [https://www.linkedin.com/in/peter-ngugi-987255240/].

