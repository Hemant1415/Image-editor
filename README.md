# Image Processing Web App with Flask

This repository contains a Flask web application for image processing. Users can upload images, apply various transformations such as resizing, brightness adjustment, contrast enhancement, rotation, flipping, circular blur, and grayscale conversion, and then view the edited images.

## Technologies Used

- **Python Libraries:** Flask, PIL (Pillow), NumPy
- **Web Technologies:** HTML, CSS
- **Other:** Werkzeug

## Features

- **Image Transformation:** Resize, adjust brightness and contrast, rotate, flip, apply circular blur, and grayscale.
- **File Handling:** Upload and validate image files (supports formats: pdf, png, jpg, jpeg, gif, webp).
- **Interactive Web Interface:** Simple and intuitive UI for editing images.
- **Output:** Save edited images to a designated folder (`static`).

## Dependencies

- ![Flask](https://img.shields.io/badge/Flask-2.0.1-blue)
- ![PIL (Pillow)](https://img.shields.io/badge/PIL%20(Pillow)-8.4.0-blue)
- ![NumPy](https://img.shields.io/badge/NumPy-1.22.2-blue)
- ![Werkzeug](https://img.shields.io/badge/Werkzeug-2.0.1-blue)

## Setup and Usage

1. Clone the repository.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run the Flask application: `python app.py`.
4. Access the web app through your browser at `http://localhost:5000`.

## Image Editing App Demo

![Image Editing App](https://media.giphy.com/media/7TlXYo4FTC3aUZsfEY/giphy.gif)

## File Structure

- `app.py`: Main Flask application file containing routes and image processing methods.
- `templates/`: HTML templates for different pages (home, upload, edit, about, contact).
- `static/`: Folder to store uploaded images and edited images.

## Getting Started

To get started with the project:
- Ensure you have Python installed.
- Install Flask and other dependencies.
- Run the Flask application and start processing images!

## Contributing

Contributions are welcome! Please feel free to fork this repository and submit pull requests to suggest improvements or additional features.


