# English-to-Hinglish-Translator

## Method 1: Using Tkinter Library
This simple Python application utilizes the Tkinter library to create a graphical user interface (GUI) for translating English text into Hindi. The translation is performed using the englisttohindi library.

## Table of Contents
Requirements                                                                                          
Installation                                                                                                                                            
Usage

### Requirements
Python 3.x                                                                                                                     
Tkinter (usually included in Python standard library)                                                                               
englisttohindi library (Install using: pip install englisttohindi)

### Installation
Clone or download this repository to your local machine.
Make sure you have Python 3.x installed.
Install the required englisttohindi library using the command: pip install englisttohindi.

### Usage
Navigate to the directory containing the code.
Run the script english_to_hindi_translator.py.
The application window will appear, allowing you to enter English text.
Click the "Translate" button to convert the entered English text to Hindi.
The translated text will be displayed in the result area of the window.
Code Overview
The code defines a basic GUI using Tkinter to take user input, perform English to Hindi translation, and display the translated text. It uses the EngtoHindi class from the englisttohindi library to handle the translation.

### The GUI elements include:
A label for entering English text.
An entry field for the user to input English text.
A "Translate" button to initiate the translation.
A label to display the translated Hindi text.

## Method 2: Using Googletrans
This Python script utilizes the googletrans library to translate English text into Hinglish (a mixture of Hindi and English). The googletrans library is an unofficial Python wrapper for the Google Translate API.

## Table of Contents
Requirements                                                                                          
Installation                                                                                                                                            
Usage

### Requirements
Python 3.x                                                                                                                                     
googletrans library (Install using: pip install googletrans==4.0.0-rc1)

### Installation
Clone or download this repository to your local machine.
Make sure you have Python 3.x installed.
Install the required googletrans library using the command: pip install googletrans==4.0.0-rc1.

### Usage
Navigate to the directory containing the code.
Run the script hinglish_translator.py.
Enter the English text you want to translate into Hinglish.
The script will use the Google Translate API to perform the translation.
The translated Hinglish text will be displayed as the result.

### Code Overview
The code defines a simple Python function translate_to_hinglish(text) that takes an English text input and translates it to Hinglish using the googletrans library. The translation is done using Google Translate's src='en' (English) to dest='hi' (Hindi) parameters.
