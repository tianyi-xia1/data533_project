# French Learning Package

Contribution from both of members: Litao Zheng, Tianyi Xia

## Subpackage 1: memorization

### classes.py

- WordPair: class used to represent a pair of French and English words
- EasyWordPair, MediumWordPair, HardWordPair: subclasses of WordPair to represent difficulty levels of word pairs, inherits from WordPair

### initializer.py
- initialize_word_pairs: function that used to initialize selected number of word pairs with selected difficulty level

## Subpackage 2: quiz

### manager.py

- StatusManager: class used to manages word pairs based on their quiz performance, with status correct_first_time(word pairs answered correctly on the first attempt) and failed_first_time(word pairs answered incorrectly on the first attempt)
- view_progress: function that allows user to view their progress by calling the status manager class after the quiz

### quizzing.py

- display_word_pairs: function used to display the word pairs for memorization
- clear_screen: function used to clear the terminal screen to hide the word pairs before the quizzing starts
- quiz_user: function used to conduct the quiz by asking the user for the English meaning of French words and check whether the users's inputs are same as the correct answer

## main.py

- main: the main function that used to run the whole French Learning Program including display the menu for difficulty selection, allow the user to choose words to learn and quizzes the user on those words, and tracks performance and displays a progress


```python

```
