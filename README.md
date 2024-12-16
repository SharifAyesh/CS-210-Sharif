# CS-210-Sharif

Summarize the project and what problem it was solving?
For my portfolio, I chose the Corner Grocer Item-Tracking Program, which I built in C++. The program’s main goal was to help the Corner Grocer analyze their daily sales by counting how often each item was purchased from a list of text records. Manually keeping track of this information can be time consuming and prone to error, so this program automates the process. It reads through the records, counts each item, and displays the results clearly, helping the store rearrange their produce section and make smarter decisions for their customers.

What did you do particularly well?
I think I did a great job with the item frequency analysis. I made sure the program could handle the text file input efficiently, count each item accurately, and display the results in an organized way. I also focused on making the program user-friendly by providing clear instructions and output. On top of that, I paid attention to writing clean, well-documented code so that someone else could easily understand and update it if needed.

Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
While the program works well for its current purpose, there’s definitely room for improvement. For instance, I could optimize the counting process by using a hash map instead of basic loops, which would make the program run faster, especially for larger datasets. I’d also like to add more flexibility by letting users upload their own files or even generate reports in a different format, like a CSV file. These changes would make the program both more efficient and adaptable for real-world use.

Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
The hardest part of the project was getting the text parsing and counting logic to work correctly. I ran into challenges with inconsistent formatting, like extra spaces or unexpected line breaks in the file. To solve this, I broke the problem down into smaller steps, testing the program with different examples until it handled everything properly. I also relied on C++ documentation and Stack Overflow for help with file input and string manipulation. Moving forward, I plan to use tools like gdb for debugging and spend more time writing small tests as I build out features.

What skills from this project will be particularly transferable to other projects or course work?
This project taught me a lot of valuable skills that I’ll carry into future work. I got better at handling file input/output and manipulating strings in C++, which are key for many real-world applications. I also improved my problem-solving skills by breaking down challenges into manageable pieces and working through them step by step. On top of that, I learned how important it is to write clear, maintainable code, which will definitely help in larger projects and team environments.

How did you make this program maintainable, readable, and adaptable?
To make the program easy to work with, I focused on writing clean and organized code. I used clear names for variables and functions so that it’s obvious what each part of the code does. I also added comments to explain the tricky sections, which will make it easier for someone else (or even myself) to understand and update later. I broke the program into smaller functions, like one for reading the file and another for counting items, which makes the code modular and easier to extend. Finally, I avoided hardcoding values and allowed file input so the program can adapt to different needs.
