# Image Steganography

A web-based application built with Django that allows users to securely hide and extract secret messages within images using steganography and encryption techniques.

## 🚀 Features
- Hide secret messages inside images
- Extract hidden messages from images
- User-friendly web interface
- Built using Django framework
- Supports multiple image formats (PNG, JPEG, BMP)

## 📝 Usage
1. Upload an image to hide a secret message.
2. Enter the message you want to hide.
3. Download the image with the hidden message.
4. To extract a message, upload the steganographed image and click **Extract**.

## 💻 Tech Stack
- Python 3.x
- Django 4.x
- HTML5, CSS3, Bootstrap
- Pillow (Python Imaging Library)
- Cryptography library for message encryption



## 🛠️ Installation

Run the following commands step by step in your terminal:

```bash
# Clone the repository
git clone https://github.com/darshangn-lab/image_steganography.git
cd image_steganography
```
```bash
# Create a virtual environment
python -m venv venv
```
```bash
# Activate the virtual environment
# On macOS/Linux
source venv/bin/activate
# On Windows
# venv\Scripts\activate
```
```bash
# Install dependencies
pip install -r requirements.txt
```
```bash
# Apply database migrations
python manage.py migrate
```
```bash
# Run the development server
python manage.py runserver
```
Open your browser and go to http://127.0.0.1:8000
 to access the app.
