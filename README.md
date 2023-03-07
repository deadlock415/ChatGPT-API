# ChatGPT-API
This is an example code for using OpenAI API to generate text based on a prompt.

## Prerequisites
Before running this code, you need to have an OpenAI API key. You can get one by signing up for an account at https://platform.openai.com/signup . Once you have your API key, replace the 'Enter your API_Key' placeholder in the code with your actual API key.

You also need to install the OpenAI Python package. You can do this by running 
```pip install openai```

## Usage
To use this code, simply run it in a Python environment. The script will prompt you to enter a prompt, which is the starting text for the generated text.

The model parameter in the openai.Completion.create() method specifies the model used for generating the text. In this example, we are using the text-davinci-003 model, which is one of the most capable models currently available.

The max_tokens parameter in the openai.Completion.create() method specifies the maximum number of tokens to generate. A token is a word or a punctuation mark, and the default value is 2048.

The generated text will be printed to the console.

## How to Use<br>
1.Set your OpenAI API key in the "Enter your API_Key" field.<br>
2.Run the code.<br>
3.Enter the prompt when prompted by the code.<br>
4.The generated text will be printed as output.<br>


