In this project we intend to create a simple Text Editor program and implement Auto-Complete feature using **Trie** data structure.

![simple menu](menu.png)

## Features

1. If we enter a word completely (speciﬁed by Space or Enter ) and it does not
exist in our dictionary, it must be added.
>- In the case of pressing Tab the program shows all of the possible states that
can complete the word.
E.g. if the words “complete” and “common” are saved in our trie then by
pressing tab while the word “com” is typed, the
program will show “complete” and “common” as the possible words.
>- After the program shows a list of all possible words, user may choose a word,
then the entire sentence (with the chosen word) will be printed.
>- User should be able to exit the editor and return to the main menu. In this
case the program asks if you wish to save your text as *.txt ﬁle.
2. The program read a list of words as a ﬁle and save them.
3. It is able to add a word given from user.
4. User can be able to delete a word.
5. User may ask to see the entire dictionary sorted by the alphabet.
6. The program should provide a procedure to save the dictionary that is stored
in trie, in a ﬁle.
