
# IndianCurrencyNotesDetection

### A web application made for Indian Currency Notes Detection using YOLOv5.

---

**Web Application available** [here](#)

---

## Objective/Purpose

- In India, Indian Currency Recognition System currently uses CNN and OpenCV-based recognition systems to detect currency notes. This model has lower detection accuracy than the proposed system which uses **YOLOv5** for object detection.
- Our App also serves the **tourists and other foreigners** in India to know the currency they possess, which also helps them avoid fraud.
- Our app also provides **audio outputs** which helps **visually impaired people**.

---

## Local machine setup for working application

### Requirements

- Text-Editor: VScode / SublimeText / VS (any modern editor)
- Python >= 3.7  
- Git >= 2.25.1 (Not mandatory)  
- Linux / Windows (Currently, PyTorch is not available for macOS)  
- For Windows users: install torch from [here](https://pytorch.org/get-started/locally/) and configure it using this [link](https://docs.microsoft.com/en-us/windows/wsl/install).  
- For Linux OS: dependencies are installed via command line using `requirements.txt`.

---

## Steps

1. Visit Git repository from [here](https://github.com/Gowtham-369/IndianCurrencyNotesDetection)

2. You can download code in zip format from the above link or  
   Run  
   ```bash
   git clone https://github.com/Gowtham-369/IndianCurrencyNotesDetection.git
   ```  
   inside terminal/CMD

3. Create a virtual environment for this project using [this link](https://docs.python.org/3/library/venv.html) and [this link](https://realpython.com/python-virtual-environments-a-primer/)  
   Activate virtual environment.

4. Open terminal/CMD in current working directory

5. Install dependencies using  
   ```bash
   pip install -r requirements.txt
   ```  
   Ensure **successful installation of all dependencies**

6. Type  
   - `ipconfig` (for Windows)  
   - `ifconfig` (for Linux)  
   in the terminal. Copy the IPv4 address and paste it in the `url` field in **line 19** of the `index.js` file.

7. Run  
   ```bash
   python3 app.py
   ```

8. Flask local server will open in console. Click the link or open in browser.

9. **To use web app on mobile**:  
   Connect the mobile to the **same WiFi/Ethernet** as the computer and open the same URL in any modern browser like **Chrome**, **Firefox**, **MS Edge**, or **Safari**.

---

## For Accurate and Clear Voice Outputs

- Use Chrome / Edge / Firefox Browsers

---

## For tweaking voices for speech output buttons

1. Open browser DevTools and go to Console.
2. Type and run:
   ```javascript
   speechSynthesis.getVoices()
   ```
3. Use the required `id` values in **line 58 and 64** of the `index.js` file.

---

## For Dataset

Dataset used from Kaggle: [Kaggle Link](https://www.kaggle.com/)

