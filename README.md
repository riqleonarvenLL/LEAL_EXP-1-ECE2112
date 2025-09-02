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

```
**Output**
```
Sorted string: ehllo
```
---

# 😀 Emoticon Replacer in Python

This Python program replaces certain words in a sentence with emoticons.
***Funtion***
```python
def replace_emoticons(): # define a function
    emoticons = {"smile": ":)", "grin": ":D", "sad": ":((", "mad": ">:("} # define the elements (key pairs) of the dictionary

    sentence = input("Type a word: ") # let user input their word of choice
    words = sentence.split() # the split syntax is called on the sentence 
    new_sentence = [] # define a new list that stores the appended sentence in the for loop

    for word in words: # use for loop 
        if word in emoticons: # use if loop to check whether the sentence has an element in the emoticons dictionary
            new_sentence.append(emoticons[word]) # if an element was found, append the emoticons to the word/s that is present in the sentence given by the user to the new_sentence list
        else:
            new_sentence.append(word) # if an element was not found, just append the whole sentence into the new_sentence list

    return " ".join(new_sentence) # use return '' to return the space character and the whole output, used syntax .join to concatenate the user's inputted string 

print(replace_emoticons()) # print the final output
```
***Output***
```
>:(
```
---

## What It Does

- Asks the user to type a sentence.
- Looks for specific words like "smile", "grin", "sad", and "mad".
- Replaces those words with matching emoticons.
- Prints the sentence with emoticons.
***Function***
```python
  writeyourcodehere = [1,2,3,4,5,6] # set writeyourcodehere variable's list elements to 1,2,3,4,5,6

first, *middle, last = writeyourcodehere # set the unpacking syntax

print("First:", first) # print the first element
print("Middle:", middle) # print the middle element/s
print("Last:", last) # print the last element
```
***Output***
```
First: 1
Middle: [2, 3, 4, 5]
Last: 6
```
---

# 📦 List Unpacking in Python

This Python script demonstrates how to unpack the first, middle, and last elements from a list.

---

## What It Does

- Defines a list of numbers.
- Uses unpacking syntax to assign the first, middle, and last elements to variables.
- Prints each part separately.

---

