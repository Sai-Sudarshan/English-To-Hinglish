# English-To-Hinglish
This project is a Python-based tool for converting English text to Hinglish (a mixture of Hindi and English) using transliteration techniques. It leverages The Natural Language Toolkit library to achieve accurate transliterations from English to Hinglish.
# English-to-Hinglish Translation Model

Translate English Sentences into Hinglish Using NLTK and Google Translate

## Project Overview

This repository houses a Python script designed to transform English sentences into Hinglish, a delightful fusion of Hindi and English. The translated text aims to capture the essence of spoken Hindi while ensuring clarity and accessibility for both native Hindi speakers and learners of the language.

## Key Project Objectives

The primary aspirations of this endeavor include:

1. **Fluent Translation:** Developing a translation model proficient in producing Hinglish text that artfully mirrors the cadence of spoken Hindi.

2. **Clarity and Preservation:** Retaining select English words within the translation to enhance lucidity, especially for non-native Hindi speakers.

3. **Semantic Precision:** Ensuring that Hinglish translations accurately convey the intended meaning of the original English sentences.

## Utilized Libraries and Components

This project artfully combines various components and leverages the following libraries:

1. **Translation Engine:** The project's cornerstone employs NLTK for text processing and seamlessly integrates the Google Translate API to metamorphose English sentences into Hinglish.

2. **Noun Discernment:** Within the project's repertoire lies a function that adroitly identifies and extracts nouns from input sentences, harnessed by NLTK.

3. **Translation Alchemy:** Another function artfully utilizes the Google Translate API to transmute English sentences into Hindi.

4. **Substitution Logic:** At its core, the project showcases a function that orchestrates the substitution of nouns in the Hindi translation with their English counterparts, while judiciously preserving specific English words to maintain lucidity.

## Getting Started
Here's a step-by-step guide on how to use the code:
1. **Clone the Repository**: Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/Sai-Sudarshan/English-To-Hinglish.git
   
2. **Install Dependencies**: Ensure Python is installed on your system. If not, you can download it from python.org. Afterward, install the necessary Python libraries by running these commands:

    ```bash
    !pip install nltk
    !pip install googletrans==4.0.0-rc1
    
3. **Run the Code**: Execute the code to translate English text into Hinglish. Customize the input text and other options as needed.

# sample Output

- **Enter a sentence**: i was waiting for the bag
- **Hinglish Sentence**:i बैग का इंतजार कर रहा था
- **Enter a sentence**: Definitely share your feedback in the comment section.
- **Hinglish Sentence**: निश्चित रूप से comment section में अपनी feedback साझा करें।
- **Enter a sentence**: So even if it's a big video, I will clearly mention all the products.
- **Hinglish Sentence**: तो भले ही यह एक बड़ा video है, मैं स्पष्ट रूप से सभी products का उल्लेख करूंगा।

