# BE_Project for PICT IT 2023-2024
# Intelligent Video-Based Attendance Tracking with Machine Learning  
(A face recognition attendance marking system)

The Real-Time Attendance Management System is an innovative solution designed to streamline and automate the process of recording student attendance during lectures. Traditional methods like paper-based systems or card-swiping are often time-consuming and prone to errors. This project leverages advanced face recognition technology to mark attendance for multiple students simultaneously, ensuring accuracy, efficiency, and improved security.

By capturing real-time video feeds from multiple camera angles strategically positioned within a classroom, the system can identify and match student faces with a pre-registered encodings database. Additionally, the system automatically sends email notifications to students, informing them of their attendance status for each lecture, thereby enhancing communication and accountability.

**Project Structure**  

**1. Data Preprocessing**  
Registration of Students: Collecting and storing student data and face images for initial setup. Face Encoding Generation: Generating unique face encodings for each registered student. Data Preparation for Machine Learning: Preparing the collected data for training the face recognition model.

**2. Encodings**  
Extraction of 128 Points: Using a deep learning model to extract 128-point facial embeddings for accurate recognition.

**3. Implementation of Modules**  
Machine Learning Pipeline: Building and training the face recognition model using the preprocessed data.

**4. Model Deployment**  
OpenCV: Integrating the trained model with OpenCV for real-time face detection and recognition.

**5. Automatic Email Notification**  
SMTP: Setting up an SMTP server to automatically send email notifications to students after each lecture.

**6. Experimentation Setup**  
Evaluation of Machine Learning Models: Testing different models to determine the best-performing one. Selection of Best-Performing Model: Choosing the model that provides the highest accuracy for real-time attendance tracking.
