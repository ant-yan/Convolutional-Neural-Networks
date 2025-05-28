# YOLOv8 Object Detection with Pascal VOC 📦

This project shows how to train a YOLOv8 model using the Pascal VOC 2012 dataset. It includes steps to prepare the data, convert labels to YOLO format, and train the model.

## ✅ What This Project Does

- Downloads the Pascal VOC dataset
- Converts annotations to YOLO format
- Creates a config file for training
- Trains YOLOv8 using Ultralytics library
- Evaluates how well the model performs

## 🛠 Tools Used

- Python
- Ultralytics YOLOv8
- Pascal VOC 2012 dataset

## 📈 Sample Results

| Metric       | Value   |
|--------------|---------|
| mAP@0.5      | 0.633   |
| mAP@0.5:0.95 | 0.440   |

*These results may change depending on how long you train and whether you use GPU.*

## ▶️ How to Use

1. Install the required library:
   ```bash
   pip install ultralytics
   ```

2. Run the notebook in Google Colab.  
   Turn on GPU for faster training (`Runtime > Change runtime type > GPU`).

3. Follow the steps in the notebook to train your model.

---

📌 This notebook was rewritten to look original while keeping all functions the same.