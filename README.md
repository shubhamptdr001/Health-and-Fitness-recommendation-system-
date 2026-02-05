## Personalized Diet & Workout Recommendation System

This project is a web-based health and fitness recommendation system that provides personalized diet and workout plans based on user inputs such as dietary preferences, fitness goals, health conditions, and restrictions.
It uses Google Gemini AI for intelligent recommendations and Flask for the web interface.

## Features

Personalized diet recommendations
Customized workout plans
Healthy breakfast and dinner suggestions
Useful snacks, supplements, and hydration tips
Simple and user-friendly web interface
AI-powered responses using Gemini API

## How It Works

User enters:

  Dietary preferences
  Fitness goal
  Dietary restrictions
  Health conditions
  Personal query

Data is sent to the backend (Flask)

Gemini AI model processes the input and generates:

  Diet types
  Workout options
  Meal suggestions
  Additional health tips
  Results are structured and displayed on the suggestion page

## Project Structure

    ├── app.py                # Flask backend with Gemini AI integration
    ├── templates/
    │   ├── index.html        # User input form
    │   └── suggestion_page.html  # Recommendation display page
    ├── static/
    │   ├── style.css         # Styling
    │   └── image.png         # Project logo
    ├── README.md

## Technologies Used

  Python
  Flask
  HTML & CSS
  Google Gemini AI (Generative AI)
  Prompt Engineering
