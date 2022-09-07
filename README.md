# String-Calculator-Kata-TDD

1. In a test-first manner, create a simple class named StringCalculator and a method
int add(String numbers)

    1. The method can take numbers as a string separated by comma and will return their sum (for an 
    empty string, it will return 0). For example:
    Input: ""
    Output: 0
    Input: "1"
    Output: 1
    Input: "1,2"
    Output: 3
    2. Start with the simplest test case of an empty string and move to one & two numbers.
    3. Remember to solve things as simply as possible so that you force yourself to write tests you did 
    not think about
    4. Remember to refactor after each passing test.
    
2. Allow the add method to handle an unknown amount of numbers

3. Calling add with a negative number will throw an exception “Negatives not allowed” - and the negative 
that was passed.
4. If there are multiple negatives, show all of them in the exception message

5. Numbers bigger than 1000 should be ignored.
For example:
Input: "2,1001"
Output: 2

6. (Optional) Allow the add method to handle new lines between numbers (instead of commas).
    1. The following is ok:
    Input: "1\n2,3"
     Output: 6
    2. The following is INVALID input so do not expect it: “1,\n” (no need to write a test for it)
