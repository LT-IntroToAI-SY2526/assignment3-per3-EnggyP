# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
While completing this assignment, I learned how to use pattern-matching function techniques to identify the user query and connect it to functions in a movie database. Additionally, I learned how to handle various types of user queries. A technique I learned was whenever the function was "year_by_title", I would set the title first, "title = (etc)", then I would lastly put "result.append(get_year(movie))". I realized how the first word/variable from the function goes last, and the last word goes first, in order to get the function to retrieve the answer.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
The overall movie chatbot system works by analyzing the user query to detect the patterns or keywords that are related to movies. Based on these patterns, the system matches the query to a function that gets a movie director, actors, or listing movies from a specific year. Then it calls the correct function using the information like a movie title or year. Lastly, the system organizes the result and returns it to the user with the answer.  


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
This type of pattern-matching chatbot system could be useful for customer support or educational apps where the people ask questions For example, it could help them with homework problems or product details or information. I would improve this system for practical use by adding machine learning so it could handle more complex inquiries. In addition, I would add a voice input that can understand different languages so it could be more diverse and helpful for others who need support understanding.