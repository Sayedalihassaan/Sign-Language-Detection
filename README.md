
---

## 🤟 Sign Language Detection Using YOLOv8

This project applies **Ultralytics YOLOv8** to recognize and detect **hand signs** representing letters of the alphabet in sign language. It demonstrates real-time object detection for educational or assistive technology applications.

---

### 🔍 Project Highlights

- 🔤 Detects A-Z signs from sign language
- 🧠 Uses pre-trained/custom YOLOv8 models
- 🖼️ Visualizes predictions with bounding boxes
- ⚙️ Runs on GPU via Google Colab (or locally)

---

### 🛠️ Requirements

- Python 3.8+
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- Torch, OpenCV (optional for local video)
- Jupyter/Colab environment

```bash
pip install ultralytics==8.0.196
```

---

### 📂 Project Structure

```
📁 Sign_Language_Detection/
│   ├── Sign_Language_Detection.ipynb  # Main notebook
│   └── runs/detect/                   # YOLOv8 results directory
```

---

### ▶️ How to Run

1. Install `ultralytics`:
    ```bash
    pip install ultralytics==8.0.196
    ```

2. Open the notebook in Jupyter or Google Colab.

3. Run the cells to:
   - Load the YOLOv8 model (e.g., `YOLO('sign_language.pt')`)
   - Perform inference on images or videos
   - View results in the `runs/detect/` folder

---

### 📊 Output

- 🖼️ Annotated images with bounding boxes for each detected letter
- ✅ Visual predictions that assist in interpreting sign language

---

### 📌 Example Use Case

This tool can be used in:
- Assistive technologies for people with hearing impairments
- Sign language learning tools
- Human-computer interaction research

---

### 📝 License

This project is open for educational use. Please contact the author for commercial or research applications.

---

