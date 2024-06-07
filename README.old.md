# AI Image Generator App

## Overview

This project is an AI Image Generator application built with React and powered by OpenAI's API. Users can input text prompts, and the app generates images based on those prompts using AI technology. The project demonstrates the integration of a React front end with OpenAI's image generation capabilities.

## Features

Text-to-Image Generation: Users can enter text prompts to generate images using AI.
Responsive Design: The application is fully responsive and works across different devices.
User-Friendly Interface: Simple and intuitive interface for ease of use.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- OpenAI API: Provides the AI model for image generation.
- Axios: A promise-based HTTP client for making API requests.
- CSS: For styling the application.

## Getting Started

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later) or yarn (v1.22 or later)
- OpenAI API key


## Clone the repository:


git clone https://github.com/NadeeTharuka/ai-image-generator.git

## Usage
- Enter a text prompt into the input field.
- Click the "Generate Image" button.
- Wait for the AI to generate an image based on the provided prompt.
- The generated image will be displayed below the input field.

## Components
- App.js: Main component that contains the layout of the application.
- ImageGenerator.js: Component that handles the input, API call, and displays the generated image.

## API Integration
The app uses the Axios library to make requests to the OpenAI API. The request includes the text prompt, and the response is used to display the generated image.