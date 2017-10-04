# Flashcard-Generator

A backend node app for a basic flashcard application using an API that allows users to create two types of fkashcards:

* Basic - Cards conataining a front and a back
* Cloze - Cards containing partial-text, and the full text when the user rquests it.

![begin](/images/ScreenShot-1.png)
Format: ![Alt Text](url)

### Add Basic Card

The user can add their own Basic Card to the deck. 

!(/images/ScreenShot_AddBasic.png)
Format: ![Add Basic](url)

### Show Basic Cards

Their are already hardcoded cards in the file. This will show all cards including any cards the user has added.

!(/images/ScreenShot_ShowBasic.png)
Format: ![Show Basic](url)

* Note: added user card has been added

### Take Quiz

When "Take Quiz" is chosen the user will be asked to choose between taking either the "Basic Card" or "Cloze Card Quiz".

!(/images/ScreenShot_ChooseQuiz)
Format: ![Choose Quiz](url)

#### Basic Card Quiz

The front of the card is asked and the user enters their answer. If the user's answer matches the back of the card they will told they are correct. If their answer is incorrect, they will be told the correct answer. When all cards are used it will display the total number of correct and incorrect answers.

!(/images/ScreenShot_BasicQuiz)
Format: ![Basic Quiz](url)

* Note: added user card has been shown

#### Cloze Card Quiz

The partial question is asked and the user enters their answer. If they are correct or incorrect the full sentence will be shown. When all cards are used it will display the total number of correct and incorrect answers.

!(/images/ScreenShot_ClozeQuiz)
Format: ![Cloze Quiz](url)