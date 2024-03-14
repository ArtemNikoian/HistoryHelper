# HistoryHelper
This code will help you in creating your personal history revision book with all needed information about historic events. You will be able to add any events you want by just typing its name in the console. The end result will look like this:

![Result image](image.png)

## Setup guide:
1. Download the project, and navigate to the HistoryHelper folder in your editor. 
2. Run this line of code in terminal to install all libraries: ```pip install openai openpyxl datetime``` if you are using python2, or ```pip3 install openai openpyxl datetime``` if you are using python3 (You can check the python version by running this line: python -V). 
3. Open the AI.py file. In the top of the code you can see variables for your openai api key and the path to the excel file. Write your openai api key and the excel file path there. If you don't know how to find a file path, I recommend you to watch these videos: Windows: (https://www.youtube.com/watch?v=QZUpzuQ0X5I), Mac: (https://www.youtube.com/watch?v=gxU1wlBAsig&t=23s)
4. Save the code and close it.

Once the setup is completed, you do not need to repeat the steps above anymore.

## How to run the code
To run the code, simply write this line in the terminal: ```python path_to_AI.py``` if you are using Python2 or ```python3 path_to_AI.py``` for Python3 (replace "path_to_AI.py" with the actual path). Once you have done this, input the name/names of the historic event you wish to add information about. If you want to add multiple events at once, separate them with ", " (witout quotation marks). The code will find the information about the events and upload it to the file automatically. You can open your Excel file and see the event details in there. I recommend enabling the text wrapping, setting the default column width to 20, and auto-fitting row height in Excel settings.

## Warnings:
Remember that the file structure should be as in BaseFile, otherwise the code will not work properly. <br />Do not forget to delete all empty columns between default events when you delete information about any event. <br />Do not delete the first column. <br /> You must have at least one event with a structure as in default event. You can add one by using code, and then delete the default events.

## How to use it
This project helped me improve my history grades from a C- to a B without having to put in a lot of extra work. I no longer needed to read through numerous presentations filled with useless information. This is how I used it to improve my efficiency: first, I quickly went through the syllabus for our classes without delving too deep into it. I only looked for events or terms that I didn't know. As soon as I came across something new, I inputted it into the code and it automatically added it to my file. Then, I reviewed all the events and terms in the file, only focusing on the names I didn't remember. If I came across something I didn't remember, I looked at all the information below and repeated this process until I remembered everything. This method is beneficial because you don't need to read all the extra information written in the books or presentations that you won't need. This only gives you the useful information.

## Thank you for visiting the page
I hope this code will help you in improving your history grades while decreasing the preparation time as well as it did for me. If you like my project, please give it a star so that I know it helped someone. Good luck!
