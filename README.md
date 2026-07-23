1. Key Evaluation Metrics
Your code should check for these criteria to determine if a password is "Weak", "Medium", or "Strong": 
Length: At least 12 to 16 characters is the modern industry standard.
Uppercase Letters: Contains at least one uppercase letter (e.g., A-Z).
Lowercase Letters: Contains at least one lowercase letter (e.g., a-z).
Numbers: Includes at least one numerical digit (0-9).
Special Characters: Includes at least one special character or punctuation mark (e.g., !@#$%^&*()_+). 

CISA (.gov)
 +4
2. Standard Python Solution
Most internship implementations use Python's built-in re (Regular Expression) module to scan user inputs. A standard script structure looks like this:
