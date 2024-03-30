# Car Tracking Project

This project aims to track cars using YOLOv7 object detection and tracking.

## Overview

The "Car Tracking" project utilizes YOLOv7, a state-of-the-art object detection model, for detecting and tracking cars in images or videos. The project combines the power of YOLOv7 with additional tracking algorithms to accurately track cars in real-time scenarios.

## Features

- Object detection using YOLOv7.
- Object tracking for car detection.
- Real-time car tracking in videos or live streams.
- Integration with SQLite for data storage.
- Frontend interface using Vue.js and Nuxt.js.
- Backend API development using Django.

## Requirements

- Python 3.12.2
- Vue.js
- Nuxt.js
- Django

## Installation

1. Clone the repository:

```
git clone https://github.com/TanaboonJew/Car_tracking.git
```

2. Install dependencies:
- Backend (Django):

  ```
  cd backend
  pip install -r requirements.txt
  ```
- Frontend (Vue.js/Nuxt.js):
  ```
  cd frontend
  npm install
  ```

## Usage

1. Set up the SQLite database and configure database settings in the Django backend.
2. Train the YOLOv7 model on a dataset of car images or use a pre-trained model.
3. Run the Django backend server:

```
cd backend
python manage.py runserver
```
4. Run the Vue.js/Nuxt.js frontend:

```
cd frontend
npm run dev
```

5. Access the application in your web browser.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- YOLOv7 Object Tracking: [YOLOv7](https://github.com/RizwanMunawar/yolov7-object-tracking)
- Django Web Framework: [Django](https://www.djangoproject.com/)
- Vue.js Framework: [Vue.js](https://vuejs.org/)
- Nuxt.js Framework: [Nuxt.js](https://nuxtjs.org/)
