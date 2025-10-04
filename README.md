# ShantanuMishra-langsmith-MAT496
This repository is for my video-by-video progress of different modules of the Introduction to LangSmith course by LangChain Academy.

# Module 1 Video 1: Tracing Basics
So in this lesson, I learned how tracing works in LangChain and why it is useful for debugging and improving apps. 
By setting the environment variables, I could track what was happening inside the model step by step and adding metadata made it easier to organize runs in LangSmith and to review model performance over time.
I changed the question in the file to "How do I apply the @traceable decorator to a function?"

Original source code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/sourcecode/tracing_basics.ipynb

Edited code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/Module1/tracing_basics%20(2).ipynb

# Module 1 Video 2: Types of Runs
This lesson showed me how to label runs with different types, that can make outputs clearer and I saw what each part of the pipeline is doing. 
I learned about various run types like llm,chain,retriever,tool and reducing chunks using reduce_fn function.
I added run_type="llm" and model metadata to the @traceable decorator and I changed the example to say goodbye to the user instead of greeting it which helped in understanding of run_type function.

Original source code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/sourcecode/types_of_runs.ipynb

Edited code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/Module1/types_of_runs%20(1).ipynb

# Module 1 Video 3: Alternative Ways to Trace
Here, I saw that tracing does not have to be global and we can use the trace() method to track only certain parts of the code. 
This gives more control when we do not want everything to be traced at once and I learned about enabling tracing at the project level for consistency.
I changed the question to How are the clouds formed to create a more descriptive and proper example.

Original source code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/sourcecode/alternative_tracing_methods.ipynb

Edited code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/Module1/alternative_tracing_methods%20(3).ipynb

# Module 1 Video 4: Conversational Thread
This video explained how to link multiple queries together with a common thread ID. So the follow-up questions stay connected and that is important for chatbots. 
In LangChain, it shows up like a dialogue flow and makes the conversations easier to follow and manage.
So, I changed the last question here to prove that the question got answered on basis of its previous question.

Original source code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/sourcecode/conversational_threads.ipynb

Edited code file:
https://github.com/Shantanu2003-alt/ShantanuMishra-langsmith-MAT496/blob/main/Module1/conversational_threads%20(1).ipynb


# Module 2 Video 1: 
