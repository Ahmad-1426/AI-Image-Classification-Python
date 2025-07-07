# AI-Image-Classification-Python
# 🍍 vs 🍎 Fruit Classifier using Teachable Machine and Python

This project demonstrates how to classify images as either **Pineapple** or **Apple** using a machine learning model trained via **Teachable Machine** and run locally using **Keras** and **Pillow** in Python.

---

## 1. Objective

- Use **Keras** and **Pillow** in Python.
- Bridge web-based training tools (**Teachable Machine**) with local Python scripts.
- Run simple AI inference tasks on custom images to distinguish between **Pineapple** and **Apple**.

---

## 2. Dataset

The model was trained on two classes:

| Class     | Description                |
|-----------|----------------------------|
| 🍍 Pineapple | Various images of pineapples |
| 🍎 Apple     | Various images of apples     |

Images were collected and uploaded manually into Teachable Machine.

---

## 3. Output Example

![لقطة الشاشة 2025-07-08 012956](https://github.com/user-attachments/assets/20843466-63ef-432f-aac5-4b44c1a29502)



---

## 4. Requirements

To run the Python prediction script, you need:

- Python 3.x
- TensorFlow  
  ```bash
  pip install tensorflow
| Item                      | Description                              |
| ------------------------- | ---------------------------------------- |
| Teachable Machine         | Used to create and export the ML model   |
| `keras_model.h5`          | Trained model file                       |
| `labels.txt`              | List of class labels                     |
| Python + Keras + Pillow   | Required libraries for running inference |
| `test.jpg` (or any image) | Image to classify                        |

6. How the Model Was Trained
Visited Teachable Machine.

Selected Image Project > Standard Image Model.

Created two classes:

Class 1: Apple

Class 2: Pineapple

Uploaded training images for both classes.

Trained the model using the built-in tool.

Exported the model:

Export Model → TensorFlow → Keras (keras_model.h5 + labels.txt)

7. How It Works
The script loads the model and labels.

An input image is resized to 224x224 and normalized.

The model predicts the class of the image.

The result shows:

The predicted class name (Apple or Pineapple).

The confidence score (how sure the model is).

8. python code with output:
   ![image](https://github.com/user-attachments/assets/4677303c-277f-492f-90b3-f683257b9230)


