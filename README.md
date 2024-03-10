# HistoryHelper
This code will help you in creating your personal history revision book with all needed information about historic events. You will be able to add any events you want by just typing its name in the console. The end result will look like this:

![Result image](image.png)

## Usage guide:
1. Download the project, and navigate to the HistoryHelper folder in your editor. 
2. Run this line of code in terminal to install all libraries: ```pip install openai openpyxl datetime``` if you are using python2, or ```pip3 install openai openpyxl datetime``` if you are using python3 (You can check the python version by running this line: python -V). 
3. Open the AI.py file. In the top of the code you can see variables for your openai api key and the path to the excel file. Write your openai api key and the excel file path there. If you don't know how to find a file path, I recommend you to watch these videos: Windows: (https://www.youtube.com/watch?v=QZUpzuQ0X5I), Mac: (https://www.youtube.com/watch?v=gxU1wlBAsig&t=23s)
4. Save the code and run it by writing this line in the terminal: ```python path_to_AI.py``` if you are using python2 or ```python3 path_to_AI.py``` for python3 (replace path_to_AI.py with actual path). Now input the name of historic event that you want to add information about. The code will find the info about the event and upload it to the file automatically.
5. Open your excel file, and see the event details in there. (I recommend enabling the text wrapping, setting the default column width to 20, and auto fit row height in excel settings)

## Warnings:
Remember that the file structure should be as in BaseFile, otherwise the code will work improperly. <br />Do not forget to delete all empty columns when you delete information about any event. <br />Do not delete the first column and the default events, they are used as timeline borders. <br /> You may get errors that indicate a mismatch between date formats. If you get them, try to do the request again, until it works.

## How to use it
This project helped me to improve my history grades from C- to B, without putting much more work into preparation. I didn't need to read millions of presentations with useless information anymore. This is how I used it to improve my efficiency. I quickly went through the syllabus for our classes, without going deep into what is written there. I only looked for events or terms I didn't know. As soon as I noticed one, I inputted it into the code and it automatically added it to my file. Then I revised all the events and terms in the file, only looking for names I didn't remember. Then I looked at all the information below and repeated this process untill I remembered everything. This is beneficial because you don't need to read all the extra information written in the books or presentations that you won't need. This only gives you the useful information.

## Thank you for visiting the page
I hope this code will help you in improving your history grades while decreasing the preparation time as well as it did to me. If you like my project, please give it a star so that I know it helped someone. Good luck!
