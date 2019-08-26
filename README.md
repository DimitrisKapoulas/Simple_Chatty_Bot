# Simple_Chatty_Bot
Project: Simple Chatty Bot

Stage 1/4: Hello! What’s your name?

Description

Digital personal assistants help people to drive cars, plan their day, buy something online. In a sense, they are simplified versions of artificial intelligence with whom you can talk.

In this project, you will develop step by step a simple bot which will help you to study programming.

For the first stage, you will write a bot who displays a greeting, its name and the date of its creation.

Your program must print the following lines:

Hello! My name is {botName}.</br>
I was created in {birthYear}.</br>

Instead of {botName} print any name you choose and replace {birthYear} with the current year (four digits), ex:

Hello! My name is Aid.</br>
I was created in 2018.</br>

You can change the text if you need but print exactly two lines.

Next, we will use Aid and 2018 as your assistant's name and its birth year, but you can change it if you want.

Stage 2/4: How old are you?

Description

At this stage, you will introduce yourself to the bot. He will greet you by your name and then try to guess your age using arithmetic operations.

Your program must print the following lines:

Hello! My name is Aid.</br>
I was created in 2018.</br>
Please, remind me your name.</br>
What a great name you have, {yourName}!</br>
Let me guess your age.</br>
Enter remainders of dividing your age by 3, 5 and 7.</br>
Your age is 22; that's a good time to start programming!</br>
You may change the name and the creation year of your bot if you want.</br>

Instead of {yourName}, the bot must print your name entered from the standard input. Instead of {yourAge}, the bot must determine your age according to the following formula:

age = ((age % 3) * 70 + (age % 5) * 21 + (age % 7) * 15) % 105</br>
Here is an example of a dialogue with the bot. Input lines are started with ">" symbol. You do not need to read this symbol.</br>

Hello! My name is Aid.</br>
I was created in 2018.</br>
Please, remind me your name.</br>
> Max</br>
What a great name you have, Max!</br>
Let me guess your age.</br>
Say me remainders of dividing your age by 3, 5 and 7.</br>
> 1 2 1</br>
Your age is 22; that's a good time to start programming!</br>
Use the provided template to simplify your work. You can change the text, but not the number of printed lines.</br>
