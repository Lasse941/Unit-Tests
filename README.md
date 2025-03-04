Key Features of These Unit Tests

    Comprehensive Edge Cases:
        Tests various character sets (Latin, Chinese, Arabic).
        Tests accented characters for normalization.
        Includes empty strings, spaces, and numeric input cases.

    Handling Unicode & Special Characters:
        Ensures correct behavior for multi-byte Unicode characters.
        Validates diacritic stripping in text normalization.

    Long Input Handling:
        While not explicitly tested, Python’s string functions can handle extremely long strings without issue.
        These functions are expected to work efficiently with large data sets.

    Unconventional Inputs:
        Newlines and spaces-only strings in count_words().
        Tests against special floating-point values like math.inf and -math.inf aren't applicable here but could be added for numeric processing functions.

How to Run These Tests

    Save the main script as text_utils.py.
    Save the test script as test_text_utils.py in the same directory.
    Run the tests using:

    python -m unittest test_text_utils.py
