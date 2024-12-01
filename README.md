# Shakespearean Translator

A lightweight and efficient translator that converts modern English text into Shakespearean language directly in your browser. No APIs or external dependencies required!

## Features

- **Dictionary-Based Translation**: Utilizes a predefined dictionary to translate words and phrases.
- **Real-Time Performance**: Translates instantly in your browser without any need for an internet connection.
- **User-Friendly Interface**: Clean and intuitive design for easy usage.
- **Expandable Dictionary**: Easily add or modify translations.

## How to Use

1. Download or clone this repository.
2. Open the `index.html` file in your browser.
3. Enter modern English text in the input box and click **Translate**.
4. The Shakespearean equivalent will appear below.

## Installation

1. Clone the repository or download the `index.html` file.
2. Open the `index.html` file in any modern web browser.
3. Start translating!

## Customization

Expand the dictionary by editing the JavaScript file in the `index.html`. Find the `shakespeareanDictionary` object and add more words or phrases as needed:

```javascript
const shakespeareanDictionary = {
    "hello": "hail",
    "friend": "comrade",
    "how are you": "how art thou",
    "today": "this day", // Add more translations here
};
