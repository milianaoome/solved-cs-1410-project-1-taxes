Download Link: https://assignmentchef.com/product/solved-cs-1410-project-1-taxes
<br>
4.12 Programming Project #1 –TaxesBackgroundThis will be your first programming project in C++. Although most of the basicprogramming concepts are the same as those you should already be familiar with, youwill have some syntax and structure differences to work through as you begin todevelop programs using C++. This first programming assignment will give you a gentleintroduction to programming in C++.ObjectivesAt the completion of this project, you will have created an application that properlyuses C++ syntax and structure. In particular, this project:• introduces students to the style and structure of a C++ program• uses the standard C++ I/O library to get input from the console,• uses arithmetic expressions, assignment, and control structures; and• uses the standard C++ I/O library to format output and send it to the consoleIntroductionSuppose that your Utah state tax is computed using the following tables (Note allincome amounts are in whole dollars):

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/03/997.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/03/997.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>For example, if a married person who earns $5000.00 a year files a joint return theformula to calculate this person’s taxes would be:tax = (5000 – 1726) * 0.033 + 40.0ProjectFor this project, you should write a program that does the following:1. Prompt the user to enter in their taxable income.2. Get the input. Validate the input to insure that it is a positive value. You mayassume that a numerical value is entered.3. Prompt the user to enter in “s” or “m” for filing single or jointly.4. Get the input and validate that it is either “s” or “m”. Re-do this step if the input isnot valid.5. Based on the user’s input, calculate the user’s tax using the appropriate taxtable and display the amount of money that person owes. Present this datanicely formatted.6. Ask the user if they want to do another tax calculation.7. Accept either ‘y’, ‘n’, or ‘q’ as input. Validate the input and re-do this step if it isnot correct.8. If the user selects ‘y’ start back at step one. If the user selects ‘q’, quit. For allother choices, tell the user that an invalid choice was made and ask them toinput again.For this program, you can enter your code directly in Zylabs while you are developingit. When you are ready to submit your program, click on the Submit button. If you useanother development environment, you can paste your code into the main.cpp textbox in Develop mode, and then click on Submit. (The latter mode is recommended.)Note: Your code must be portable, meaning it must run on any C++ compiler. Do notuse any platform-specific code.Input and Output in ZylabsRunning a console program in Zylabs is different than in a terminal window on yourcomputer. A sample execution in a terminal window would look something like thefollowing.Please enter in your taxable income.(This must be a positive value): 10000Please enter m if married and filing joint return,or s if filing a single return: mYour taxable income is $10000.00and you are filing a joint return.Your income tax will be $493.05Would you like to do another calculation (y or n)?nWhen running this in Develop Mode in Zylabs, you enter each input on its own line inthe input window. For this sample, you would enter the following in the input window:10000mnZylabs automatically feeds each data item into each input request from your program.It is important that you do not wait for the user to press Enter/Return (don’tuse cin.get() or anything like it in the code you submit to Zylabs).In the expected output window, you place everything except the input, which in thiscase is:Please enter in your taxable income.(This must be a positive value):Please enter m if married and filing joint return,or s if filing a single return:Your taxable income is $10000.00and you are filing a joint return.Your income tax will be $493.05Would you like to do another calculation (y or n)?The same output as seen in the console sample above will then appear in theexecution output window in Zylabs.When you enter Submit Mode and click Submit, your program will be run against testcases that have been prepared by your instructors. You will be able to see the resultsand resubmit if needed. Make sure you submit your finished solution by the due dateand time. All entries are time-stamped by Zybooks and late projects will be dockedaccording to the syllabus.