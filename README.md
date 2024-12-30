# PPE Detection Project

Welcome to the **PPE Detection Project**! This project is designed to detect Personal Protective Equipment (PPE) such as helmets, face masks, and vests in real-time using object detection techniques.

The system utilizes the **YOLO** (You Only Look Once) model for object detection and is optimized for **CUDA** and **CDNN** to leverage GPU acceleration for faster and more accurate results.

---

### **Overview**

The **PPE Detection** project aims to detect whether individuals are wearing the required PPE items in real-time video streams. This project can be applied to various safety-critical environments like construction sites or manufacturing plants, ensuring workers are wearing the necessary protective gear.

---

### **Features**
- **Real-Time PPE Detection**: Detects the presence of PPE (helmets, masks, vests) in live video feeds.
- **High Accuracy**: Powered by the **YOLO** object detection algorithm for precise identification.
- **GPU Acceleration**: Uses **CUDA** for GPU-powered inference, ensuring fast processing of video streams.
- **Custom Model**: The pre-trained model (`PPE.pt`) is specifically fine-tuned for detecting PPE in videos.

---

### **Tech Stack and Requirements**

This project uses several tools and libraries for optimal performance:

#### **Required Libraries**:
Install the following Python libraries by running:
```bash
pip install -r requirements.txt
```

- **cvzone**: 1.5.6
- **ultralytics**: 8.0.26 (for YOLO models)
- **hydra-core**: >=1.2.0
- **matplotlib**: >=3.2.2
- **numpy**: >=1.18.5
- **opencv-python**: 4.5.4.60
- **Pillow**: >=7.1.2
- **PyYAML**: >=5.3.1
- **requests**: >=2.23.0
- **scipy**: >=1.4.1
- **torch**: >=1.7.0
- **torchvision**: >=0.8.1
- **tqdm**: >=4.64.0
- **filterpy**: 1.4.5
- **scikit-image**: 0.19.3
- **lap**: 0.4.0

#### **System Requirements**:
- **CUDA & GPU Support**: This project uses **CUDA** for GPU acceleration. You will need an NVIDIA GPU with compatible drivers installed.
- **PyTorch with CUDA**: Ensure PyTorch is installed with GPU support:
  ```bash
  pip install torch torchvision torchaudio
  ```

---

### **Project Structure**

```bash
PPE-Detection/
├── PPE-Detection.py
├── PPE.pt
├── __pycache__/
├── requirements.txt
└── README.md
```

---

### **How to Run the Code**

1. **Install Dependencies**:
   First, install all required libraries by running:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Detection Script**:
   - To start PPE detection, simply run the following command:
   ```bash
   python PPE-Detection.py
   ```

3. **Input Sources**:
   - For **real-time video detection**, ensure that the webcam is connected.
   - For **video files**, place the video files in the same directory as the script and update the file path in the code.

4. **Model Weights**:
   - Ensure the correct pre-trained weights (`PPE.pt`) are available in the same directory as the script.

---

### **Project Demonstrations**

The system is capable of detecting the presence of **helmets**, **face masks**, and **vests** worn by individuals in various environments.

![Screenshot 2024-12-30 181410](https://github.com/user-attachments/assets/d0efb8e2-728a-44d3-b1c1-c7afe00b45ea)
![Screenshot 2024-12-30 181512](https://github.com/user-attachments/assets/15443cc9-3a00-4ff7-9421-ac46e721d783)


---

### **Key Files:**
- **`PPE-Detection.py`**: Main script for detecting PPE (helmets, face masks, vests) in real-time using a video stream. The script uses YOLO for object detection.
- **`PPE.pt`**: The pre-trained YOLO model fine-tuned for detecting Personal Protective Equipment. It is loaded by the detection script for inference.

---

### **Contributing**

We welcome contributions to this project! If you'd like to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Make your changes and test them.
4. Push your changes (`git push origin feature-name`).
5. Open a pull request with a detailed description of your changes.

---

### **License**

This project is licensed under the **MIT License**.

---

### **Acknowledgments**

- **YOLO**: Special thanks to the creators of the YOLO model for their contributions to object detection.
- **OpenCV**: For handling video input and image processing.
- **PyTorch**: For deep learning model training and GPU acceleration.

---

### **Contact**

If you have any questions or suggestions, feel free to open an issue in the repository or contact me at [viditupadhyay07@gmail.com](mailto:viditupadhyay07@gmail.com).

---

