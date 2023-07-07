# FaceKubeLauncher

<br/>

![k8s_py_cv](https://github.com/Ddhruv-IOT/Python-K8S-OpenCV-Integration/assets/54676859/26622564-6391-4903-b8a3-e3df7448dd50)
<br/>

## About Project 🔥🔥

The **FacePodLauncher** is an innovative application built using Python and OpenCV that combines facial recognition technology with the power of Kubernetes and Minikube. This project aims to create a seamless and automated system for launching a pod in Minikube based on the recognition of a specific face.

Using the OpenCV library, the application is capable of detecting and analyzing faces in real time through a webcam or recorded video feed. It leverages advanced face detection and recognition algorithms to identify the target face accurately. Once the specific face is recognized, the FacePodLauncher triggers the deployment of a pod in the Minikube environment. The pod can be customized to perform various tasks or execute specific applications tailored to the individual associated with the recognized face. The utilization of Kubernetes and Minikube allows for scalable and efficient deployment of pods, making it suitable for a wide range of applications. Whether it's launching a personalized workspace, initiating specific workflows, or automating personalized tasks, the FacePodLauncher offers endless possibilities. This project not only showcases the capabilities of facial recognition and Kubernetes technologies but also demonstrates the potential for integrating computer vision and containerization for personalized and secure computing environments.

**With the FacePodLauncher, the future of face-based automation and personalized computing has arrived, empowering users with an intelligent and seamless experience. ✨✨**


## Tools and Technologies Used:

### Python Modules:
- OpenCV, for face recognition
- Pyttsx3, for voice assistance
- Subprocess, to run commands on the host OS
  
### Softwares Used
- Anaconda
- Spyder IDE
- Minikube
- Oracle VM Virtual Box
- Git Bash

### OS Used:
- Windows 10 

## Features
- Face detection
- Voice assistance
- Launch of pods in Minkube

## Working

The project encompasses three key components, each serving a distinct purpose:

**1. Data Collection:**
A Python script has been developed to automate the data collection process. By leveraging computer vision techniques, the script captures approximately 100 images, crops them to focus solely on the face, and converts them to grayscale. This ensures consistent and standardized data for subsequent analysis.

**2. Model Training:**
Following the data collection phase, a Local Binary Patterns Histograms (LBPH) face detection model is trained. This model is trained on the collected facial images, enabling it to learn and identify key facial features that distinguish individuals. The training process optimizes the model's ability to accurately recognize faces during subsequent real-time face recognition.

**3. Face Recognition and K8S Launch:**
In the final step, real-time face recognition is performed using the trained LBPH model. When a face is successfully recognized, the application proceeds to launch a Kubernetes (K8S) replication controller in the Minikube environment. This is achieved by employing a pre-defined manifest file, which automates the creation of pods. Once the pods are successfully created, a service is instantiated to expose them using **NodePort**. Consequently, the user gains access to the hosted webpage through a web browser, facilitated by the K8S pods.

Through this systematic approach, the project effectively combines data collection, model training, and real-time face recognition with the deployment and management capabilities of Kubernetes. The end result is a seamless and efficient solution that enables secure and personalized computing experiences.

## Demo Link:
[***Continue to LinkedIn***](https://www.linkedin.com/posts/ddhruv-arora_python-connections-datascience-activity-6879500818408587264-OB3X?utm_source=share&utm_medium=member_desktop)

# Thank you
- Thank you all for using my app.
- All suggestions are warmly welcomed.



