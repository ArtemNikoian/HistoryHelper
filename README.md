# HistoryHelper
Learn historic events easier
The code edits an excel file that you specify a path to (it has to be in strict structure, like BaseFile). It adds the name of the event, the date of it, people and countries involved in it, what the event actually is, and why it happened. This is all information you need to know to succeed in a history exam.

## Usage guide:
1. Download the HistoryHelper folder, and open it in your editor. 
2. Run this line of code to install all libraries: ```pip install openai openpyxl datetime``` if you are using python2, and ```pip3 install openai openpyxl datetime``` if you are using python3.
3. Open the AI.py file and specify your openai api key and the path to the excel file.
4. Run the code and input the name of historic event that you want to add information about.
5. Open your excel file, and see the event details in there.

Remember that the file structure should be as in BaseFile, otherwise the code will work improperly
