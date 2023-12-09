# Text to Speech Sound Generation with Next.js

Welcome to the **Text to Speech Sound Generation** project built using Next.js! This project demonstrates the generation of sound using pre-trained hugging face models. Users can select different hugging face sound models and input text to generate corresponding audio. The generated audio can be played back directly on the web interface.

## Overview

This project showcases how to leverage pre-trained hugging face models along with the Hugging Face inference API to convert input text into synthesized speech. The user interface provides a selection of sound models to choose from and an input field to enter the desired text. Once submitted, the application fetches the generated audio from the model's API and presents it in an audio player.


## Architecture 
![image](https://tyhgectxutilszaayoua.supabase.co/storage/v1/object/public/misc/text-to-speech-model.png?t=2023-08-14T02%3A52%3A52.637Z)



## Notes
This application relies heavily on the stability of the Hugging Face Inference API models. Please note that occasional random errors may occur.

## How to Run the Project

### Prerequisites

- Node.js 
- npm 

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Ahmed9588406/text_to_speech.git
   ```
2. Navigate to the project directory:
   ```sh
   cd text_to_speech
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Hugging Face Access Token added to your `.env.local` file:
   ```sh
   Hugging face tokens can be created in the hugging face settings portal
   ```

### Running the Application

1. Start the development server:
   ```sh
   npm run dev
   ```
2. Open your browser and visit `http://localhost:3000` to access the application.

## Project Structure

- `components`: Contains reusable UI components used across the application.
- `lib`: Contains constants and utility functions.
- `pages`: Houses the main views and API routes of the application.
- `public`: Holds static assets like images, fonts, etc.
- `styles`: Includes global and component-specific styles using CSS or CSS-in-JS.
- `views`: Houses the main application views and components.

## Usage

1. Open the application in your browser after running it.
2. In the "Sound Model" dropdown, select a model for generating sound.
3. Enter the desired text in the "Text" input field.
4. Click the "Submit" button.
5. The generated audio will appear in an audio player below.
