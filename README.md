# simple_tasks_python
Simple tasks in Python 
Answer all the questions
1. Calculate the mean, median and mode of the values 9, 11, 22, 34, 17, 22, 34, 22 and 40. Suppose the values included another 34. What problem might occur?
2. Calculate the product of a series of integers that are passed to the function product, which receives an arbitrary argument list. Test your function with several calls, each with a different number of arguments.
3. Implement a Fahrenheit function that returns the Fahrenheit equivalent of a Celsius temperature. Use the following formula:
  F = (9 / 5) * C + 32
Use this function to print a chart showing the Fahrenheit equivalents of all Celsius temperatures in the range 0–100 degrees. Use one digit of precision for the results. Print the outputs in a neat tabular format.
4. What does the following mystery function do? Assume you pass the list [1, 2, 3, 4, 5] as an argument.
def mystery(x): y=0
      for value in x:
           y += value ** 2
return y
5. What does the following function do, based on the sequence it receives as an
argument?
  def mystery(sequence):
      return sequence == sorted(sequence)
6. Create a 2-by-3 list, then use a nested loop to:
a. Seteachelement’svaluetoanintegerindicatingtheorderinwhichitwas
processed by the nested loop.
b. Displaytheelementsintabularformat.Usethecolumnindicesasheadings
across the top, and the row indices to the left of each row.
7. (IPYTHON SESSION: SLICING) Create a string called alphabet containing 'abcdefghijklmnopqrstuvwxyz', then perform the following separate slice operations to obtain:
a. Thefirsthalfofthestringusingstartingandendingindices.
b. Thefirsthalfofthestringusingonlytheendingindex.
c. The second half of the string using starting and ending indices. d. The second half of the string using only the starting index.
e. Every second letter in the string starting with 'a'.
f. The entire string in reverse.
g. Every third letter of the string in reverse starting with 'z'.
8. (IS A SEQUENCE SORTED?) Create a function is_ordered that receives a sequence and returns True if the elements are in sorted order. Test your function with sorted and unsorted lists, tuples and strings.
9. (FINDING THE PEOPLE WITH A SPECIFIED LAST NAME) Create a list of tuples containing first and last names. Use filter to locate the tuples containing the last name Jones. Ensure that several tuples in your list have that last name.
10. (FUNCTIONAL-STYLE PROGRAMMING: ORDER OF FILTER AND MAP CALLS) When combining filter and map operations, the order in which they’re performed matters. Consider a list numbers containing 10, 3, 7, 1, 9, 4, 2, 8, 5, 6 and the following code:
  In [1]: numbers = [10, 3, 7, 1, 9, 4, 2, 8, 5, 6]
  In [2]: list(map(lambda x: x * 2,
     ...:          filter(lambda x: x % 2 == 0, numbers)))
     ...:
  Out[3]: [20, 8, 4, 16, 12]
  Reorder this code to call map first and filter second. What
  happens and why?
