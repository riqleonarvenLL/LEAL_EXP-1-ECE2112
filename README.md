# 💻 LEAL_EXP-1-ECE2112

## ECE2112 - Introduction to Python 
**Experiment 1: Basic problems using strings, lists, and functions**

---

## 📂 Contents
- Variables & Data Types  
- Lists, Tuples, Dictionaries  
- Functions  
- Input and Output  

---

## 🚀 Getting Started
1. Download `ECE2112.PA.1.IntroPython.ipynb`
2. Open it using **Jupyter Notebook**
3. Run each code cell

---

## 🧰 Requirements
- Python 3  
- VS Code or Jupyter Notebook

  ## 🧾 Code Explanations

# 🔤 String Sorter in Python

This small Python script sorts the characters of a user-inputted word into alphabetical order.

---

## What It Does

- Prompts the user to type a word.
- Sorts the characters of that word alphabetically.
- Prints the sorted string.
  
**Function:**
 ```python
  
def sortstring():  # define a function
    user_input = input("Type a word: ")  # let user input their word of choice
    return ''.join(sorted(user_input))   # Return the sorted string
# # set sortedstring variable's value to the user's inputted string or word with the custom function
sorted_string = sortstring()
# Print the result
print("Sorted string:", sorted_string)
Sorted string: ehllo

```


---

# 😀 Emoticon Replacer in Python

This Python program replaces certain words in a sentence with emoticons.

---

## What It Does

- Asks the user to type a sentence.
- Looks for specific words like "smile", "grin", "sad", and "mad".
- Replaces those words with matching emoticons.
- Prints the sentence with emoticons.

---

# 📦 List Unpacking in Python

This Python script demonstrates how to unpack the first, middle, and last elements from a list.

---

## What It Does

- Defines a list of numbers.
- Uses unpacking syntax to assign the first, middle, and last elements to variables.
- Prints each part separately.

---

