# HistoryHelper
Learn historic events easier
The code edits an excel file that you specify a path to (it has to be in strict structure, like BaseFile). It adds the name of the event, the date of it, people and countries involved in it, what the event actually is, and why it happened. This is all information you need to know to succeed in a history exam.

Usage guide:
Download the HistoryHelper folder, and open it in your editor. 
Run this line of code without quotes to install all libraries: "pip install openai openpyxl datetime" if you are using python2, and "pip3 install openai openpyxl datetime" if you are using python3.
Open the AI.py file and specify your openai api key and the path to the excel file.
Run the code and input the name of historic event that you want to add information about.
Open your excel file, and see the event details in there.

Remember that the file structure should be as in BaseFile, otherwise the code will work improperly
