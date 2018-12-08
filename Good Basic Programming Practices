                    #GOOD PROGRAMMING PRACTICES 

What does good code look like?

Good Docstring Code:

def add_number(number1, number2):
  """
  WRITING A DOCSTRING AND THINGS TO CONSIDER. When making a docstring you should put it at the beginning of your function 
  and code. The reason you are writing the docstring is tell anyone who is reading the docstring your expected inputs
  and expected outputs which we call the constraints. Also tell them what your function does.
  
  Key Things to have in a Docstring:
  1) Inputs <- Are you expecting a string or an int or a list. Make sure it is clear
  2) Output/s <- What are your expected output/s? 
  3) What your function/code does. <- Write out what your function does but a simplistic version. Max 3 sentences. 
  
  For this example my docstring should look like this:
  
  '''
  Inputs: Takes two seperate integers or floats for the arguments (telling you what the number1 and number2 are). 
  Outputs: The return value will be a single integer that is the combination of the two inputs.
  Functionality: The function will add two numbers together and output a single number back. 
  '''
  """
  
  return number1 + number2 # <- This is the output and you elaborate what you have here. 
                           # If I had more code before the return I could comment on that as well if the code is hard to understand.  

WHY WRITE A CLEAR AND CONCISE DOCSTRING: Not only will this help others read and understand your code but it helps you
be able to know where to start your unit testing and debugging processes (will go into more details below). 


Bad Code:

def add_number(number1, number2):
    
    return number1 + number2

# If this code was more complex or complicated, with no comments or docstring would take more time for person reading to figure out
# what your code was doing.


The Process of Writing Good Code:

1) Break code up into modules that contain smaller pieces of code; 
these pieces of code should be easily tested.

# Taking a project and turning it into little working parts/functions, that once those parts are made and work, 
# can combine together to form the working project. 

Example: AdditionProject ---> Working Parts       ---> Combine those back together in one file/module to making a working project.
                            1) Function/Class that adds
                            2) Function/Class that ...
                            3) Function/Class that ...
                            4) Etc.

2) DOCUMENT THE CONSTRAINTS: In those modules, there should be a doc string containing exactly what
the function does, what the expected inputs are and what the output/s
should be. 

Knowing this will help you test and debug your code.

3) DOCUMENT ASSUMPTIONS: In that doc string, write your assumptions about the code down.
What was your thinking process and what assumptions were I making 
when building this code in this particular way.

4) UNIT TESTING: testing each function seperately, validate each piece of
code. 

    -use intuition about natural boundaries in the code
    -use black box testing:
        Look at the parameters written in the doc string
        -explore paths through specification 
        -what this means is use the function's documented input CONSTRAINTS (parameters written in doc string)
        to make sure the function works at those points   
    
    -use glass box testing:
        Look at the code itself to guide the design of test cases
        -explore paths through code
        Try to go through each fork/branches (if, elif, else statements), for loops, and while loops 
        to make sure the function works at those points
        Guidelines: 
            -fork/branches (if, elif, else statements)
            -for loops
            -while loops
    
    -Use print statesments everywhere:
        -Print when you enter a function
        -Print parameters of that function
        -Print the results
    
    -Use Bisection method:
        -Put a print through out the code of what you expect and what 
        the values actually are


5) REGRESSION TESTING: add test for bugs as you find them in a function.
Catch reintroduced errors that were previously fixed.

6) INTEGRATION TESTING: put each part together and does that part work?
Does the overall program work? 

                     ***BEST WAY TO RIGHT A PIECE OF CODE***

            =Write a function, then test the function using methods above,
            then debug that function. 

            Once you find a bug save a copy of the current code, and work
            on the copy. That way if something goes wrong, you have an older
            version of the code. This is called version control. 
