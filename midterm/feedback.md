# Midterm Feedback
The midterm feedback will be very similar to what you receive on a weekly basis for the homework, but more specific for each problem in this case.

## Final Score: 50/50


### Step 1: Priest Score Calculation
* **5pts** - Your code computed the correct probability and returned it
  * **(-1pts) anything that wasn't in the 17-25 or 26+ range needed to have a return value other than 0**
* **2pts** - You had a docstring that described what the function was for
* **(-3pts)** - No doctests

### Step 2: Find a Hospital
* **5pts** - Your code correctly fetched the correct hospital given the inputs using requests
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring
  * **(-2 pts) doctests formatted incorrectly, so they never ran**

### Step 3: Get the Hospital Address
* **5pts** - Your code correctly fetched the JSON file, parsed it, and looked up the hospital
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring
  * **(-2 pts) doctests formatted incorrectly, so they never ran**

### Step 4: Process List of Patients
* **10pts** - Your code correctly fetched the psv file, looped through it, and ran your other functions
  * **(-1 pts) This code couldn't run as written because it used `find_hospital_name()`  but the earlier defined function was `find_hospital()`**
  * **(-1 pts) This code didn't handle the face that the hospital name returned from `find_hospial()` as not uppercase and `get_address()` didn't handle non-upper case hospital names**
* **2pts** - You had a docstring that described what the function was for

### Step 5: Compare Results
* **5pts** - Your code looped through all the results and compared them to the provided key

### Extra Credit
* Up to 15 pts based on correctness and quality of the extra credit step
* **(+10 pts) This basically worked but could not be demonstrated because your process wasn't working correctly end to end**

### Coding Best Practices:
**3 pts** - Was your code readable, efficient, and in line with what we learned in class?
* Good variable names?
* Code written into functions where appropriate?
* Appropriate comments with your code?
* Generally easy to follow and undersand?
