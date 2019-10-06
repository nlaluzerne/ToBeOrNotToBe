# ToBeOrNotToBe

This project uses a Random Forest Classifier, along with a data set containing information on all of William Shakespeare's plays, to try to  determine the 'Player' using the other data contained in the data set as features.

### About the Data

- Dataline - index of the row
- Play - the Play that the Player/lines are from
- PlayerLinenumber - the number of the line being spoken
- ActSceneLine - the Act.Scene.Line from which the line is from
- Player - the player who is speaking the line
- PlayerLine - the line being spoken

### Data Source
https://www.kaggle.com/kingburrito666/shakespeare-plays

### Troubleshooting GitHub Notebook Rendering
Sometimes GitHub has trouble rendering notebooks. Should GitHub have troubles rendering the notebook in this project, please navigate to https://nbviewer.jupyter.org/ and enter https://github.com/nlaluzerne/ToBeOrNotToBe in the text bar to view the notebook.

### Memory Constraints
This data set is very large. Should your computer throw memory errors when trying to train the Random Forest Classifier, please lower the percentage of the data set to use in classification by adjusting the value of "frac" in Cell 10 to a smaller value. Currently, I use 45% of the data set to classify as this was the largest value my system would allow.
