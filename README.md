# Text-to-Math-Problem-Solver-and-Data-Search-Assisstant-

This is a Streamlit-based web application that leverages LangChain and Groq's Gemma2-9b-It model to solve mathematical problems and perform information retrieval from Wikipedia. The application combines multiple tools into a seamless conversational agent capable of answering math-related questions, logic-based reasoning problems, and fetching general knowledge from Wikipedia.

# Features
# Math Problem Solver:
Solve complex mathematical problems step-by-step.
# Wikipedia Search:
Fetch detailed information on a variety of topics using Wikipedia as a knowledge source.
# Reasoning Tool:
Handle logical and reasoning-based questions by providing point-wise explanations.
# Interactive Chat Interface:
Engage in a conversational interface to input questions and receive detailed answers.

# Installation:
# Prerequisites:

Python 3.8+

Streamlit

Groq API Key

# Clone the Repository

git clone https://github.com/yourusername/text-to-math-solver.git
cd text-to-math-solver

# Install Dependencies:

Install the required Python packages:

pip install -r requirements.txt

# Set Up Environment Variables:

Make sure to have your Groq API Key ready. You can input it directly in the sidebar once the application is running.

# Running the Application:

To run the Streamlit app, use the following command:

streamlit run app.py

This will launch the application in your default web browser.

# Usage:
# Steps to Interact:

# Enter Groq API Key: 
Input your Groq API key in the sidebar.
# Input Question:
Enter your math or reasoning question in the provided text area.
# Get Answer:
Click "Find my answer" to get the detailed response. The agent will solve your question step-by-step or provide relevant information using the Wikipedia tool.

# Example
Question: "I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes. Then I buy a dozen apples and 2 packs of blueberries. Each pack of blueberries contains 25 berries. How many total pieces of fruit do I have at the end?"

The agent will calculate the total pieces of fruit after performing all the operations and provide an explanation.

# Key Components
# ChatGroq (Gemma2-9b-It):
This model is used as the core LLM for solving mathematical and logic-based problems.
# LLMMathChain:
Specialized tool for handling mathematical expressions.Example
Question: "I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes. Then I buy a dozen apples and 2 packs of blueberries. Each pack of blueberries contains 25 berries. How many total pieces of fruit do I have at the end?"

# WikipediaAPIWrapper: 
Utility for fetching information from Wikipedia.
# Streamlit Interface: 
Interactive front-end for easy user interaction and problem-solving.

The agent will calculate the total pieces of fruit after performing all the operations and provide an explanation.


