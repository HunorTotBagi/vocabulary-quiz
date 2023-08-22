# Language Translation Test
This Python script is designed to help you practice and test your skills in translating words and phrases from one language to another. In this example, we're testing your German translation skills, but you can adapt it to any language pair by providing a different text file with translations.

## How It Works
1. **Setting Up Dictionaries**: The script reads translation pairs from text files and creates dictionaries to store them. Each text file should contain translation pairs, with one pair per line, separated by ' - '. For example:

```
beli luk - der Knoblauch
sok - der Saft
banana - die Banane
```
You can add as many dictionaries as you want by providing different text files.

2. **Taking the Test**: The `the_test` function is the heart of the script. It presents you with random words or phrases to translate and evaluates your answers. Here's how it works:

* You're presented with a word or phrase to translate.
* You input your translation.
* The script checks your input against the correct answer. It handles single words and multi-word phrases.
* It provides feedback (correct +1 point, half-correct +0.5 point and wrong 0 point) and keeps track of your score.

3. **Scoring**: After completing the test, the script calculates your final score as a percentage based on the number of correct answers compared to the total number of questions.

4. **Reviewing Mistakes**: If you made any mistakes during the test, the script displays a list of those words or phrases, along with the correct translations, so you can review and learn from them.

## Getting Started

1. **Prepare Translation Files**: Create text files in the `database` directory with your translation pairs. Make sure each pair is separated by ' - ' on a new line.

2. **Running the Test**: Call the `the_test` function with the dictionary you want to use. For example, to test with `dict_8`, use `the_test(dict_8)`.

3. **Taking the Test**: Follow the prompts to translate words or phrases and see how well you perform.
