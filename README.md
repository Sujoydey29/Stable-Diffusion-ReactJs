# Stable-Diffusion-ReactJs

## Overview

This project combines stable diffusion image processing using Python Flask on the backend, GPU support for NVIDIA graphics cards (up to 4GB VRAM) with CUDA, Torch, PyTorch, and Torchaudio, and a ReactJS frontend. Users can input text prompts in the ReactJS frontend, and the backend will process the image and provide the output on the frontend.

## Table of Contents

1. [Installation](#1-installation)
2. [Usage](#2-usage)
   - [Running the Backend](#21-running-the-backend)
   - [Running the Frontend](#22-running-the-frontend)
3. [Technologies Used](#3-technologies-used)
4. [Contributing](#4-contributing)
5. [License](#5-license)

## 1. Installation

1.1. Clone the repository:

git clone https://github.com/your-username/your-repo.git

1.2. Install the required dependencies for the backend:
cd backend
pip install -r requirements.txt

1.3. Install the required dependencies for the frontend:
cd frontend
npm install

## 2. Usage
2.1. Running the Backend
To start the Flask backend server for image processing, run:
cd backend
python app.py

2.2. Running the Frontend
To start the ReactJS frontend, run:
cd frontend
npm start

Visit http://localhost:3000 in your web browser to interact with the ReactJS frontend. Enter a text prompt, and the backend will process the image and display the output on the frontend.

## 3. Technologies Used
Backend:

Python
Flask
NVIDIA GPU (up to 4GB VRAM)
CUDA
Torch
PyTorch
Torchaudio
Frontend:
ReactJS

## 4. Contributing
If you'd like to contribute to the project, please follow the contribution guidelines.

## 5. License
This project is licensed under the MIT License.


Customize the information in each section to accurately reflect your stable diffusion image processing project and its functionalities. Provide clear instructions for users to install the necessary dependencies, run the backend and frontend, and interact with the system.

