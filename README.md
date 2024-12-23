# Attendance Management System Using Face Recognition

This project implements an attendance management system using face recognition. Users can register their faces with the system, and then the system can be used to automatically track their attendance.

## Getting Started

### Prerequisites

This project requires the following Python libraries:

* `face_recognition`
* `opencv-python`
* `numpy`
* `datetime`

You can install these libraries using pip:

```bash
pip install face_recognition opencv-python numpy datetime
```
Running the System
Clone the repository:
```bash
git clone https://github.com/devsiddu/Attendance-Management-System-using-Face-Recognition.git
```
Navigate to the project directory:
```bash
cd attendance-management-system-using-face-recognition
```
Install the required libraries:
```bash
pip install -r requirements.txt
```
Run the system:
```bash
python main_Run.py
```
This will start the system and allow you to register users and track their attendance.

## Features
##### Register users with the system
##### Track user attendance automatically using face recognition
##### Mark attendance manually (optional)
##### Generate attendance reports (optional)

## Usage
#### Registering Users
##### To register a user with the system:

* Run the system (python attendance.py).
* Select the "Register" option.
* Enter the user's name and ID.
* The system will prompt you to capture the user's face. Follow the instructions on the screen.
## Tracking Attendance
Once users are registered, you can track their attendance by running the system and selecting the "Track Attendance" option. The system will use face recognition to identify registered users and mark their attendance automatically.

## Customization
This is a basic example of an attendance management system using face recognition. You can customize the system to fit your specific needs. For example, you can:

* Add support for different types of attendance (e.g., lectures, meetings)
* Implement different authentication methods (e.g., passwords)
* Generate more detailed attendance reports
## Disclaimer
```
This is a sample project and is not intended for production use. You may need to modify it to meet your specific requirements.
```
