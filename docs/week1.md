# Project Introduction: Sentence Processor

The Sentence Processor is a web-based tool designed to enhance the understanding of text-based data by breaking down sentences into individual words and retrieving their definitions. This application takes a sentence as input, analyzes it, and replaces each word with its corresponding definition from an online [Free Dictionary API](https://dictionaryapi.dev/). The tool preserves punctuation, making it easy to interpret the processed sentence.

The primary goal of this project is to help users better understand complex sentences by providing definitions for each word, allowing for more in-depth comprehension of the content. This tool can be especially useful for students, educators, and language learners who want to break down complicated text into simpler, more understandable components.

[Link to Use the Sentence Processor](../week1/index.html)


- **Input a Sentence**: The input box is prefilled with a sample sentence. You can modify this sentence or replace it with your own. The input must be a valid sentence ending with a period.

- **Submit the Sentence**: Click the "Submit" button to process the sentence. The tool will break down the sentence into individual words and retrieve their definitions from the Free Dictionary API. Punctuation marks such as commas and periods are preserved in the output.

- **View the Result**: After processing, the updated sentence, with definitions replacing the original words, will be displayed below the input box. If a word's definition cannot be found, the original word is retained.


The application uses the Free Dictionary API to retrieve word definitions. Each word in the sentence is sent to the API, which returns the first definition found. The API is a valuable resource for accessing dictionary data programmatically.

Regular Expressions (RegEx):

A regular expression (\w+|[.,:]) is used to split the sentence into words and punctuation marks. 



## Example Workflow
- Input: "This course is a survey of programming strategies and techniques for the procedural analysis and generation of text-based data."
- Output: The application replaces words with their definitions, resulting in a sentence like: "A teaching is a research of programming strategies and techniques for the a way of examining something analysis and creation of text-based data."
