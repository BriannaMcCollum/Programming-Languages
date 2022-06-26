# Programming-Languages
My work in CS-210 Programming Languages, concerning integrating C++ and Python.

# Summarize the project and what problem it was solving.
This project was a mock-up project for a grocery store company called Corner Grocer. It was designed to help the company analyze the frequency of certain items being bought in their store. The file CS210_Project_Three_Input_File contains the "data" on the purchase frequency of their items, while the program serves as a user interface to break that data down into understandable, manageable pieces.

# What did you do particularly well?
I believe the Python side of my code was done very efficiently. The use of a Dictionary to store the items and their frequencies was very helpful, and I feel the functions were very simple and highly optimized. The C++ was also very well organized, as I kept a lot of functionality separated in different areas. The bulk of the main was run in a single while loop with a switch statement.

# Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
I didn't notice this initially, but I found that every time my Python code is called, it has to re-load the text file and re-read everything. I can imagine that this would hurt the efficiency of my code. I can't think of a solution though, as writing the processed data to a new text file would take just as long if not longer, and sending the data itself to the C++ side isn't an option. I use Python-specific things like Dictionaries that can't be sent between. However, if I could find a solution, it would improve the program's efficiency greatly. This is also a very minor nitpick, but I remember using magic numbers in a few areas, and I'd go back to change those to defined variables for clarity.

# Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
I struggled a bit to figure out how to pull from and write to documents properly, in both Python and C++, but that was a simple fix as I just needed to remember the functions. I utilized Stack Overflow as a resource, which I typically do on assignments like this, to help me find more efficient ways of doing things. The biggest thing I struggled on was figuring out how to manage the data on the Python side in a way that was scalable and yet well contained. I said earlier that this was the best part of my project, and I believe that's because I spent the most time on it, fine-tuning the code and looking up ways to improve it.

# What skills from this project will be particularly transferable to other projects or coursework?
I had never worked on connecting two languages before, which makes this project incredibly helpful! This class showed me how common the practice is in the professional world, so I'm excited that I got to take a stab at it now. I think being able to connect Python and C++ is a really helpful skill, as the two languages complement each other and cover each other's weaknesses well.

# How did you make this program maintainable, readable, and adaptable?
In the C++ section, most of the code is kept in neat functions and then referred to in the main when needed. Good usage of functions keeps code separated and easily readable. They also promote adaptability, as you only have to change the function once instead of changing things throughout the entire code. The Python code is also elegant, optimized, and broken into functions, making it easy to understand and change.
