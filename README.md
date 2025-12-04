def reverse_string(text):
    """Reverses the input string using Python's slicing method."""
    return text[::-1]

# Example 1: Original string
original_string_1 = "GitHub is fun!"
reversed_string_1 = reverse_string(original_string_1)

# Example 2: A different test string
original_string_2 = "Hello World"
reversed_string_2 = reverse_string(original_string_2)

# Print the results for both examples
print(f"Example 1: Original: '{original_string_1}' -> Reversed: '{reversed_string_1}'")
print(f"Example 2: Original: '{original_string_2}' -> Reversed: '{reversed_string_2}'")
