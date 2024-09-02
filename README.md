# **Leveraging AI-Based Drones for Effective Flood Rescue Operations**

![image](https://github.com/user-attachments/assets/33a64e87-a6c0-44b5-80bc-edc91122b21d)

![image](https://github.com/user-attachments/assets/01a6cf69-cd0e-4a53-af67-34b5ddfd4e57)

## **Overview**

Welcome to the official repository for **Leveraging AI-Based Drones for Effective Flood Rescue Operations**. This project explores the integration of AI and drone technology to enhance disaster response during flood emergencies. By utilizing advanced computer vision algorithms like YOLOv8, YOLOv9, and Detectron2, our system offers accurate and real-time detection of people and obstacles, optimizing rescue operations in challenging flood scenarios.

## **Key Features**

- **AI-Driven Detection**: Employs state-of-the-art deep learning models for real-time identification of survivors and obstacles in flood-affected areas.
  
- **High Accuracy**: Detectron2 outperforms other models in terms of precision, ensuring reliable detection from heights of 50-100 meters.

- **Scalable Solution**: Designed to be scalable across different disaster scenarios, allowing for adaptable deployment in various environments.

- **Real-Time Processing**: Capable of processing video feeds in real-time, enabling timely decision-making during critical rescue operations.

## **Project Structure**

- **/data**: Contains sample datasets used for training and testing the models.
  
- **/models**: Pre-trained weights for YOLOv8, YOLOv9, and Detectron2 models.

- **/scripts**: Python scripts for data preprocessing, model training, and inference.

- **/results**: Output results, including detection images, videos, and performance metrics.

- **/docs**: Project documentation, including the research paper, design documents, and related resources.

## **Getting Started**

### **Prerequisites**

- Python 3.x
- PyTorch
- OpenCV
- Detectron2
- CUDA (Optional for GPU acceleration)

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flood-rescue-drones.git
   cd flood-rescue-drones
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download pre-trained model weights and place them in the `/models` directory.

### **Usage**

- **Training**: To train the model on a custom dataset, modify the configurations in `scripts/train.py` and run:
  ```bash
  python scripts/train.py
  ```

- **Inference**: To run inference on test images or video feeds:
  ```bash
  python scripts/inference.py --input data/test_image.jpg
  ```

- **Evaluation**: Evaluate model performance using the provided evaluation scripts:
  ```bash
  python scripts/evaluate.py
  ```

## **Results**

Here are some sample results from our model:

![Sample Detection](sample_image_url)

- **Precision**: 95%
- **Recall**: 92%
- **Inference Speed**: 20 FPS (with GPU acceleration)

## **Contributors**

- [Your Name](https://github.com/yourusername) - Lead Developer
- M. Jaswanth Kumar
- Dhanush Bitra
- Rohan Titus
- Dill Jazz
- Cinu C. Kiliroor

## **Publication**

Our work is published in **[Journal Name]**. You can access the paper [here](link_to_publication).

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Acknowledgments**

We would like to thank proffesor Dr. Cinu  for his guidance and support throughout the project.

---

Feel free to modify the README to better fit your project's specifics, including adding any additional sections or details relevant to your repository.
