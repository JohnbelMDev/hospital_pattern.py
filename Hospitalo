import re
import sys

def validate_hospital_pattern(input_string):
    """
    Check if the input string matches the hospital pattern requirements.
    Example: Check if 'Doctor' or 'Nurse' is present in the input.
    """
    pattern = r'(Doctor|Nurse)'
    if re.search(pattern, input_string, re.IGNORECASE):
        return f"Valid input: {input_string} matches the hospital pattern."
    else:
        return f"Invalid input: {input_string} does not match the hospital pattern."

if __name__ == "__main__":
    if len(sys.argv) != 2:
        print("Usage: python hospital_pattern.py <input_string>")
        sys.exit(1)

    input_string = sys.argv[1]
    result = validate_hospital_pattern(input_string)
    print(result)
