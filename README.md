# Flipkart_Grid

Flipkart Grid Robo 6.0: Smart Quality Test System
Table of Contents
Project Overview
Key Features
Use Cases
Technologies Used
Installation Guide
Usage
Challenges
Recommendations
Contributing
License
Contact
Project Overview

Project Overview
This project was developed as part of the Flipkart Grid Robo 6.0 challenge to create a Smart Quality Test System using camera vision technology. The system assesses shipment quality and quantity for India's leading e-commerce company, ensuring that products meet high standards before reaching the customer. The project uses OCR (Optical Character Recognition) and Machine Learning models to analyze product details and detect freshness, quantity, and expiry dates.

Key Features
OCR Applications for extracting key details such as brand name, product name, quantity, expiry date, and MRP from images.
Machine Learning Classification Models for object recognition, counting, freshness detection, and expiry date validation.
Seamless integration of models into a graphical user interface (GUI) with real-time or photo upload capabilities.
Ability to connect models through APIs for easy implementation in real-world scenarios.

Use Cases
The project addresses several specific use cases:
Use Case 1: Extracting Brand-Name, Quantity, and Product Name
Accuracy: 81.75% (using Easy OCR and Pytesseract)
Use Case 2: Extracting Expiry Date and MRP
Accuracy: 80.56% (using Pytesseract and OCR Regex)
Use Case 3: Object Recognition and Counting
Accuracy: 91.74% (using XGBoost)
Use Case 4: Freshness Detection
Accuracy: 92.79% (using Autoencoders and fine-tuning)
Use Case 5: Expiry Date Detection
Accuracy: 90.68% (using neural networks and regex patterns)

Technologies Used
Programming Languages: Python
Libraries:
OCR: EasyOCR, Pytesseract
Machine Learning: XGBoost, TensorFlow, Autoencoders
Regex for pattern matching
GUI: Streamlit (or Flask/Django for API integration)
Tools: OpenCV, NumPy, Pandas

Usage
Real-time Processing: Use a connected camera to feed images in real time.
Photo Upload: Upload photos of shipments to analyze them through the system.
GUI: Interact with the models through the provided GUI for ease of use.
The system provides real-time feedback on shipment quality, including:

Recognized brand and product names
Quantity verification
Freshness assessment
Expiry date detection

Challenges
Throughout development, the following challenges were faced:

OCR Accuracy: Achieving a balance between processing speed and accuracy in extracting text details, especially in cases with low-quality images.
Real-Time Processing: Handling large amounts of data in real-time for object recognition and freshness detection.
Model Fine-Tuning: Optimizing machine learning models to increase accuracy across different product categories and shipment types.
Recommendations
To further enhance the system:

Use HD cameras: Higher quality images will improve the accuracy of OCR and object detection models.
Model Expansion: The system can be extended to incorporate more categories and models for other e-commerce use cases.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or issues:

Author: Mayank Choudhary
Email: mayank.22bce7861@vitapstudent.ac.in

API Integration: Each model can be integrated into a broader system using APIs, enabling scalability and adaptability.
