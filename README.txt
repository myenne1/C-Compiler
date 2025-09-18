Project Members: Muhanad Yennes, Marco Garcia, and Kaden Casey
For this project we used AI to create the list for all of the identifiers and operators to include in order to be able to identify them in the lexer. Comments, strings, and white space do not get in the way of the actual code. Comments get matched 
(either with two back slashes or surrounded by two back slashes for a comment block) and are skipped over since they are not important to the compiler. Strings are read as text within double quotes, while characters are just in single quotes as singular
characters. The white space (like tab and space) are ignored while new lines are tracked for the error messages.
