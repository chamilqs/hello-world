# RecycleWise

RecycleWise is a Django-based web application designed to promote recycling through an intelligent detection system. It utilizes advanced machine learning models to identify recyclable materials from images or videos uploaded by users.

## Features

- **Material Detection**: Leverages a pre-trained model (`modelos/best.pt`) to accurately identify various types of recyclable materials.
- **User-Friendly Interface**: Provides an easy-to-navigate web interface for uploading images or videos for detection.
- **Admin Dashboard**: A comprehensive admin panel for managing users, uploads, and detection results.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Django 5.0.6
- Other dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/RecycleWise.git
   ```
2. Navigate to the project directory:
   ```sh
   cd RecycleWise
   ```
3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply the migrations:
   ```sh
   python manage.py migrate
   ```
5. Start the development server:
   ```sh
   python manage.py runserver
   ```

## Usage

After starting the server, visit `http://127.0.0.1:8000/` in your web browser to access the RecycleWise application. From there, you can upload images or videos for material detection.

## Development

- **Models**: Define your database models in `detection/models.py`.
- **Views**: Implement your application logic in `detection/views.py`.
- **Templates**: Modify the web interface in the `templates/` directory.
- **Static Files**: Add or update CSS styles in `static/css/style.css`.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.
