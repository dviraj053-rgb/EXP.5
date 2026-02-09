# EXP.5
Aim:
To study the use of dictionaries in Python.

Theory:
Dictionaries in Python are used to store data in key–value pairs. A dictionary is an ordered, mutable collection that does not allow duplicate keys. Values can be retrieved using the syntax print(dict["key"]).
If the same key is assigned multiple values, the dictionary stores only the latest value. New key–value pairs can be added or existing ones updated using dictionary["key"] = "value".
All values in a dictionary can be displayed using dictionary.values().
The dictionary.pop("key") method removes a specific key–value pair from the dictionary.
The get() method, such as student.get(name, "Student not found"), is used to search for a key and return a default message if the key does not exist.

Algorithm:

A. Update Product Price

Initialize a dictionary named product with product names as keys and their prices as values.

Display the product dictionary to show the original prices.

Update the price of a specific product using product["Book"] = "55 Rupees".

Display the updated dictionary.

B. Search Student Marks

Initialize a dictionary named student with student names as keys and their marks as values.

Accept a name from the user and store it in the variable name.

Search for the name using student.get(name, "Student not found").

Display the marks if the student exists; otherwise, display Student not found.

C. User Login Validation

Initialize a dictionary named users with usernames as keys and passwords as values.

Accept username and password from the user.

Validate the login by checking whether users.get(username) matches the entered password.

If they match, display Login successful; otherwise, display Invalid username or password.

D. Find Highest Scorer

Initialize a dictionary named student with student names and their marks.

Find the student with the highest marks using max(student, key=student.get) and store it in topper.

Retrieve the topper’s marks using student[topper].

Display the name of the topper along with their marks.

Conclusion:
Thus, dictionaries in Python were implemented successfully, and various operations were performed on them.
