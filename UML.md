# Introduction #

This is an overview of what the classes will look like.


# Details #


|Class Name | Wheel | Player | Board | Main |
|:----------|:------|:-------|:------|:-----|
|Variable   | Values Array | totalScore | currentPhrase | Wheel |
|Variable   | Current Position | currentScore | lettersGuessed | Board |
|Variable   |       | playerName | dictionaryFile pointer | Players Array |
|Variable   |       | image  |       |      |
|Method     | (int) Spin | addPoints(int) | newPhrase() |      |
|Method     |       | keepPoints(int) | guessLetter(char) |      |
|Method     |       | getCurrentPoints(int) | tryToSolve(String) |      |
|Constructor | Wheel() | Player(name, image) | Board(dictionary file pointer) |      |