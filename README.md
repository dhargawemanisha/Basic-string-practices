# Basic-string-practices
# 1. len()
Description: Returns the length of the string (number of characters).
Usage: len("Hello, World!")
# 2. upper() and lower()
Description: upper() converts all characters to uppercase, lower() converts all characters to lowercase.
Usage: "Hello, World!".upper(), "Hello, World!".lower()
# 3. strip()
Description: Removes leading and trailing whitespaces from the string.
Usage: " Hello, World! ".strip()
# 4. split(separator)
Description: Splits the string into a list of substrings based on the specified separator.
Usage: "Hello,World!".split(',')
# 5. join(iterable)
Description: Joins elements of an iterable (like a list) with the string as a separator.
Usage: ",".join(['Hello', 'World!'])
# 6. replace(old, new)
Description: Replaces all occurrences of the specified substring with another substring.
Usage: "Hello, World!".replace("World", "Python")
# 7. startswith(prefix) and endswith(suffix)
Description: Checks if the string starts or ends with the specified prefix or suffix.
Usage: "Hello, World!".startswith("Hello"), "Hello, World!".endswith("World!")
# 8. find(substring) and index(substring)
Description: Returns the index of the first occurrence of the substring. find() returns -1 if not found, index() raises an error.
Usage: "Hello, World!".find("World"), "Hello, World!".index("World")
# 9. isalpha() and isdigit()
Description: Checks if all characters are letters or digits, respectively.
Usage: "Hello".isalpha(), "123".isdigit()
# 10. count(substring)
Description: Counts the number of occurrences of a substring in the string.
Usage: "Hello, World!".count("l")

These methods are fundamental for string manipulation in Python and are widely used in various programming scenarios.
