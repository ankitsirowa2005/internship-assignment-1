# internship-assignment-1
###question 1 : Explain the difference between the following data types with examples -
Integer(int) - this python datatype is used to store integer values(e.g. 12, -67, -28 etc.). this datatype can store values requiring of size 64-bit or more.                      we can perform arithmatic operations(+,-,*,/,//), bitwise operations(&,|,~,^,<<,>>) and comparison operations(<,>,<=,>=,==,!=) on the variables of                  this datatype. the variables of this datatype belongs to the class 'int'.
Float(float) - this pythin datatype is used to store those values which has has a fractional part(e.g. 3.92, -98.44, -10.29 etc.). this datatype can store values                  of size 64-bit or more with a double precision. this datatype suports arithmatic and comparison operations and variables of this dataype belong to                  the 'float' class.
String(str) -  this datatype is used to store a collection of characters(e.g. "a", "2", "#" etc.). string datatype is immutable which means once a string is                       created it cannot be modified instead a new one is created which is referenced. strings can be concatenate('+'), repeated('*') and allow indexing                   and slicing. strings have their own dedicated methods like upper(), lower(), strip(), split() and replace etc.
Boolean(bool) - this datatype is used to store boolean values(True or False). these values are used to perform logical, conditional and comparison operations.                      variables of this datatype belong to the bool class.

###question 4 :  Explain any five commonly used string methods in python with examples
upper()/lower() - this method converts the string in uppercase/lowercase.
                  for example str = "Python programming"
                  str.upper() = "PYTHON PROGRAMMING"
                  str.lower() = "python programming"
replace(old,new) - this method is used to replace the part of the string with a new one
                   for example str = "python programming"
                   str.replace("python","java") = "java programming"
strip()/lstrip()/rstrip() - this method is used to remove the whitespaces of both sides/left side/right side from the string
                   for example str = " hello, world "
                   str.strip() = "hello,world"
                   str.lstrip() = "hello,world "
                   str.rstrip() = " hello,world"
startswith()/endswith() - this method is used to find whether the string starts/ends wih the given part or not
                    for ex. str = "machine learning"
                    str.startswith("machine") = True
                    str.endswith("programming") = False
split() - this method returns a list of the splitted parts of the string on the basis of delimiters like comma, space and colon etc.
                   for ex. str = "rohit, mohan, shyam"
                   str.split(",") = ["rohit", "mohan", "shyam"]
                   
###question 7 : What is Artificial Intelligence (AI)? Explain its importance and mention any four real-life applications of AI.
Artificial Intelligence is the branch of computer science which focuses on creating systems capable of performing tasks that normally require human like intelligence. these tasks involve natural language understanding, learning from data, reasoning, problem solving capabilities and perception.
real life applications - 
healthcare  - AI assists in diagnosing diseases, analyzing medical images and predicting patient outcomes. it is also helpful to find cures for diseases.
finance - AI is used for fraud detection, algorithmic trading and banking services.
transportation - it is used for self driving cars, traffic prediction and route optimization.
entertainment and e-commerce - in recommendation of movies, music or products based on user behaviour 

###question 8 : Identify whether the following are examples of AI and explain why
chatgpt - chatgpt is an LLM model that on the basis of probability creates text. it is somewhat nearer to artificial intelligence it functions on the training of           artificial neural networks but it still lacks human like thinking , creativity and narrow in its working.
Google Maps route prediction  - google maps uses the real time traffic data and GPS system to predict the route which will be the cheapest and takes a less time             which requires real time data analysis and has some properties of AI like reasoning and predictions.
Calculator - calculator is used to perform different mathematical operations like arithmatic, exponential, trignometric etc. but it can be achieved with fixed                programs and does not show any behaviour of AI.
Netflix recommendations - recommendations are presented by using the past data of the user (preferences) and use that in machine learning algorithms to make                  predictions which is the property of an AI.
Voice assistants (Alexa/Siri) - these cloud based assistants takes the input in the form of voice data and use the natural language processing to answer, perform
            tasks and control devices which shows the behaviour of AI.
