# piglatinpy
_Pig Latin_ is a language game, in which English words are altered, according to some rules, to obtain their _Pig Latin_ translation. The _piglatinpy_ program allows translating words from English to _Pig Latin_.

## Instructions for You
* You are asked to develop _piglatinpy_ by following TDD.
* You DO NOT need to develop a GUI.
* You CANNOT change the signature of the provided methods, move the provided methods to other classes, or change the name of the provided classes. However, you CAN add fields, methods (e.g., methods used by tests to set up the fixture or methods used by the provided methods), or even classes (including other test classes), as long as you comply with the provided API.
* You CAN use the internet to consult Python APIs or QA sites (e.g., StackOverflow).
* You CANNOT use AI tools (e.g., ChatGPT).
* You CANNOT interact with your colleagues. Work alone and do your best!
* The _piglatinpy_ requirements are divided into a set of USER STORIES, which serve as a to-do list (see the _Issues_ session).
* You should be able to incrementally develop _piglatinpy_ without an upfront comprehension of all its requirements. DO NOT read ahead, and handle the requirements (i.e., specified in the user stories) one at a time in the provided order. Develop _piglatinpy_ by starting from the first story’s requirement. When a story is IMPLEMENTED, move on to the NEXT one. A story is implemented when you are confident that your program correctly implements the functionality stipulated by the story's requirement. This implies that all your test cases for that story and all the test cases for the previous stories pass. You may need to review your program as you progress toward more advanced requirements.
* Each time you end a TDD phase, COMMIT.
* If you need to handle error situations (including situations unspecified by the user stories), throw a `PigLatinError`.
* If you need some English words for your tests, you are allowed to go to: https://wordfinder.yourdictionary.com/letter-words/

## API Usage
Take some minutes to understand, in broad terms, how the API works (see also the docstring comments of each method). If you do not fully understand the API, do not worry because further details will be given in the user stories.

A typical API usage follows.
```python
# To initialize a translator with a phrase
translator = PigLatinTranslator.PigLatinTranslator("This is a phrase")
# To get the phrase
phrase = translator.get_phrase()
# To get the Pig Latin translation
translation = translator.translate()
```
